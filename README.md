if game.PlaceId == 126884695634066 then
    repeat task.wait() until game:IsLoaded()
    repeat task.wait() until game:GetService("ReplicatedStorage"):FindFirstChild("GameEvents")

    local ReplicatedStorage = game:GetService("ReplicatedStorage")
    local OrionLib = loadstring(game:HttpGet('https://raw.githubusercontent.com/jensonhirst/Orion/main/source'))()

    local Window = OrionLib:MakeWindow({
        Name = "R",
        HidePremium = false,
        SaveConfig = true,
        ConfigFolder = "MeuHubConfig",
        IntroText = "Seja Bem-vindo!",
        Icon = "rbxassetid://4483345998"
    })

    local function formatarNumero(num)
        local str = tostring(num):reverse()
        local resultado = str:gsub("(%d%d%d)", "%1,")
        if resultado:sub(-1) == "," then
            resultado = resultado:sub(1, -2)
        end
        return resultado:reverse()
    end

    ----------------------
    -- TWILIGHT EVENT TAB
    ----------------------
    local twilightlist = {
        {Name = "Night Seed Pack", Price = 25000000, Rarity = "Rare"},
        {Name = "Night Egg", Price = 50000000, Rarity = "Rare"},
        {Name = "Twilight Crate", Price = 120000000, Rarity = "Legendary"},
        {Name = "Star Caller", Price = 12000000, Rarity = "Legendary"},
        {Name = "Moon Cat", Price = 100000000, Rarity = "Legendary"},
        {Name = "Celestiberry", Price = 15000000, Rarity = "Mythical"},
        {Name = "Moon Mango", Price = 1000000000, Rarity = "Divine"}
    }

    local TwilightEventTab = Window:MakeTab({
        Name = "Twilight Event",
        Icon = "rbxassetid://4483345998",
        PremiumOnly = false
    })

    local TwilightEventSection = TwilightEventTab:AddSection({ Name = "Auto Buy Event Items" })

    for _, item in ipairs(twilightlist) do
        TwilightEventSection:AddToggle({
            Name = item.Name .. " - $" .. formatarNumero(item.Price) .. " (" .. item.Rarity .. ")",
            Default = false,
            Callback = function(state)
                _G["Auto" .. item.Name:gsub(" ", "")] = state
            end
        })
    end

    ----------------------
    -- BLOODILIF SHOP TAB
    ----------------------
    local bloodiliflist = {
        {Name = "Mysterious Crate", Price = 10000000, Rarity = "Legendary"},
        {Name = "Night Egg", Price = 25000000, Rarity = "Rare"},
        {Name = "Night Seed Pack", Price = 10000000, Rarity = "Rare"},
        {Name = "Blood Banana", Price = 200000, Rarity = "Mythical"},
        {Name = "Moon Melon", Price = 500000, Rarity = "Mythical"},
        {Name = "Star Caller", Price = 12000000, Rarity = "Legendary"},
        {Name = "Blood Kiwi", Price = 20000000, Rarity = "Legendary"},
        {Name = "Blood Hedgehog", Price = 23000000, Rarity = "Legendary"},
        {Name = "Blood Owl", Price = 60000000, Rarity = "Divine"}
    }

    local BloodilifEventTab = Window:MakeTab({
        Name = "Bloodilif Event",
        Icon = "rbxassetid://4483345998",
        PremiumOnly = false
    })

    local BloodilifEventSection = BloodilifEventTab:AddSection({ Name = "Auto Buy Items" })

    for _, item in ipairs(bloodiliflist) do
        BloodilifEventSection:AddToggle({
            Name = item.Name .. " - $" .. formatarNumero(item.Price) .. " (" .. item.Rarity .. ")",
            Default = false,
            Callback = function(state)
                _G["Auto" .. item.Name:gsub(" ", "")] = state
            end
        })
    end
    
    ----------------------
   -- COSMETICS SHOP TAB
    ----------------------
local cosmeticslist = {
    {Name = "Compost Bin", Price = 1000000, Rarity = "Common"},
    {Name = "Rock Pile", Price = 1000000, Rarity = "Common"},
    {Name = "Torch", Price = 850000, Rarity = "Common"},
    {Name = "Rake", Price = 1000000, Rarity = "Common"},
    {Name = "Brick Stack", Price = 350000, Rarity = "Common"},
    {Name = "Shovel", Price = 1000000, Rarity = "Common"},
    {Name = "White Pottery", Price = 800000, Rarity = "Common"},
    {Name = "Red Pottery", Price = 800000, Rarity = "Uncommon"},
    {Name = "Orange Umbrella", Price = 1000000, Rarity = "Common"},
    {Name = "Yellow Umbrella", Price = 1000000, Rarity = "Common"},
    {Name = "Medium Circle Tile", Price = 250000, Rarity = "Common"},
    {Name = "Small Circle Tile", Price = 1000000, Rarity = "Common"},
    {Name = "Log", Price = 750000, Rarity = "Common"},
    {Name = "Large Path Tile", Price = 650000, Rarity = "Common"},
    {Name = "Medium Path Tile", Price = 550000, Rarity = "Common"},
    {Name = "Small Path Tile", Price = 250000, Rarity = "Common"},
    {Name = "Shovel Grave", Price = 1000000, Rarity = "Uncommon"},
    {Name = "Light On Ground", Price = 1000000, Rarity = "Uncommon"},
    {Name = "Water Trough", Price = 2000000, Rarity = "Uncommon"},
    {Name = "Viney Beam", Price = 1000000, Rarity = "Uncommon"},
    {Name = "Large Wood Flooring", Price = 1000000, Rarity = "Uncommon"},
    {Name = "Medium Wood Flooring", Price = 1000000, Rarity = "Uncommon"},
    {Name = "Mini Tv", Price = 1000000, Rarity = "Uncommon"},
    {Name = "Small Wood Flooring", Price = 850000, Rarity = "Uncommon"},
    {Name = "Hay Bale", Price = 750000, Rarity = "Uncommon"},
    {Name = "Bookshelf", Price = 2000000, Rarity = "Uncommon"},
    {Name = "Axe Stump", Price = 2000000, Rarity = "Uncommon"},
    {Name = "Long Stone Table", Price = 2000000, Rarity = "Uncommon"},
    {Name = "Small Stone Table", Price = 1000000, Rarity = "Uncommon"},
    {Name = "Small Stone Lantern", Price = 1000000, Rarity = "Uncommon"},
    {Name = "Stone Lantern", Price = 2000000, Rarity = "Uncommon"},
    {Name = "Medium Stone Table", Price = 2000000, Rarity = "Uncommon"},
    {Name = "Large Stone Pad", Price = 2000000, Rarity = "Uncommon"},
    {Name = "Small Stone Pad", Price = 1000000, Rarity = "Uncommon"},
    {Name = "Brown Bench", Price = 1000000, Rarity = "Uncommon"},
    {Name = "Wood Fence", Price = 750000, Rarity = "Uncommon"},
    {Name = "Log Bench", Price = 1000000, Rarity = "Uncommon"},
    {Name = "White Bench", Price = 1000000, Rarity = "Uncommon"},
    {Name = "Campfire", Price = 12000000, Rarity = "Rare"},
    {Name = "Cooking Pot", Price = 12000000, Rarity = "Rare"},
    {Name = "Dark Stone Pillar", Price = 12000000, Rarity = "Rare"},
    {Name = "Grey Stone Pillar", Price = 12000000, Rarity = "Rare"},
    {Name = "Bamboo Wind Chime", Price = 350000, Rarity = "Rare"},
    {Name = "Brown Stone Pillar", Price = 12000000, Rarity = "Rare"},
    {Name = "Metal Wind Chime", Price = 12000000, Rarity = "Rare"},
    {Name = "Wheelbarrow", Price = 13000000, Rarity = "Rare"},
    {Name = "Clothesline", Price = 12000000, Rarity = "Rare"},
    {Name = "Small Wood Table", Price = 1000000, Rarity = "Rare"},
    {Name = "Large Wood Table", Price = 12000000, Rarity = "Rare"},
    {Name = "Bird Bath", Price = 12000000, Rarity = "Rare"},
    {Name = "Lamp Post", Price = 12000000, Rarity = "Rare"},
    {Name = "Square Metal Arbour", Price = 13000000, Rarity = "Rare"},
    {Name = "Small Wood Arbour", Price = 13000000, Rarity = "Rare"},
    {Name = "Curved Canopy", Price = 12000000, Rarity = "Rare"},
    {Name = "Flat Canopy", Price = 12000000, Rarity = "Rare"},
    {Name = "Large Wood Arbour", Price = 56000000, Rarity = "Legendary"},
    {Name = "Round Metal Arbour", Price = 56000000, Rarity = "Legendary"},
    {Name = "Viney Ring Walkway", Price = 55000000, Rarity = "Legendary"},
    {Name = "Ring Walkway", Price = 55000000, Rarity = "Legendary"},
    {Name = "Frog Fountain", Price = 65000000, Rarity = "Legendary"},
    {Name = "Red Well", Price = 60000000, Rarity = "Legendary"},
    {Name = "Brown Well", Price = 60000000, Rarity = "Legendary"},
    {Name = "Blue Well", Price = 60000000, Rarity = "Legendary"},
    {Name = "Green Tractor", Price = 556000000, Rarity = "Legendary"},
    {Name = "Red Tractor", Price = 556000000, Rarity = "Legendary"}
    }
    
local CosmeticsShopTab = Window:MakeTab({
    Name = "Cosmetics Shop",
    Icon = "rbxassetid://4483345998",
    PremiumOnly = false
})

local CosmeticsShopSection = CosmeticsShopTab:AddSection({ Name = "Auto Buy Cosmetics" })

for _, item in ipairs(cosmeticslist) do
    CosmeticsShopSection:AddToggle({
        Name = item.Name .. " - $" .. formatarNumero(item.Price) .. " (" .. item.Rarity .. ")",
        Default = false,
        Callback = function(state)
            _G["Auto" .. item.Name:gsub(" ", "")] = state
        end
    })
end

    local CosmeticsShopSection = CosmeticsShopTab:AddSection({ Name = "Open Crates" })

    local openAllCrates = false

    CosmeticsShopSection:AddToggle({
        Name = "Open ALL Crates",
        Default = false,
        Callback = function(state)
            openAllCrates = state

            while openAllCrates do
                task.wait(1)
                for _, crate in pairs(workspace:GetDescendants()) do
                    if crate:IsA("Model") and crate.Name:lower():find("crate") then
                            local args = {
    [1] = "OpenCrate",
    [2] = workspace.Farm.Farm.Important.Objects_Physical.CosmeticCrate
}

game:GetService("ReplicatedStorage").GameEvents.CosmeticCrateService:FireServer(unpack(args))
                    end
                end
            end
        end
    })

    ----------------------
    -- SEED SHOP TAB
    ----------------------
    local seedlist = {
        {Name = "Carrot", Price = 10, Rarity = "Common"},
        {Name = "Strawberry", Price = 50, Rarity = "Common"},
        {Name = "Blueberry", Price = 400, Rarity = "Uncommon"},
        {Name = "Orange Tulip", Price = 600, Rarity = "Uncommon"},
        {Name = "Tomato", Price = 800, Rarity = "Rare"},
        {Name = "Corn", Price = 1300, Rarity = "Rare"},
        {Name = "Daffodil", Price = 1000, Rarity = "Rare"},
        {Name = "Watermelon", Price = 2500, Rarity = "Legendary"},
        {Name = "Pumpkin", Price = 3000, Rarity = "Legendary"},
        {Name = "Apple", Price = 3250, Rarity = "Legendary"},
        {Name = "Bamboo", Price = 4000, Rarity = "Legendary"},
        {Name = "Coconut", Price = 6000, Rarity = "Mythical"},
        {Name = "Cactus", Price = 15000, Rarity = "Mythical"},
        {Name = "Dragon Fruit", Price = 50000, Rarity = "Mythical"},
        {Name = "Mango", Price = 100000, Rarity = "Mythical"},
        {Name = "Grape", Price = 850000, Rarity = "Divine"},
        {Name = "Mushroom", Price = 150000, Rarity = "Divine"},
        {Name = "Pepper", Price = 1000000, Rarity = "Divine"},
        {Name = "Cacao", Price = 2500000, Rarity = "Divine"},
        {Name = "Beanstalk", Price = 10000000, Rarity = "Prismatic"}
    }

    local SeedShopTab = Window:MakeTab({
        Name = "Seed Shop",
        Icon = "rbxassetid://4483345998",
        PremiumOnly = false
    })

    local SeedShopSection = SeedShopTab:AddSection({ Name = "Auto Buy Seeds" })

    for _, seed in ipairs(seedlist) do
        SeedShopSection:AddToggle({
            Name = seed.Name .. " - $" .. formatarNumero(seed.Price) .. " (" .. seed.Rarity .. ")",
            Default = false,
            Callback = function(state)
                _G["Auto" .. seed.Name:gsub(" ", "")] = state
            end
        })
    end

    ----------------------
    -- GEAR SHOP TAB
    ----------------------
    local gearlist = {
        {Name = "Watering Can", Price = 50000, Rarity = "Common"},
        {Name = "Trowel", Price = 100000, Rarity = "Uncommon"},
        {Name = "Recall Wrench", Price = 150000, Rarity = "Uncommon"},
        {Name = "Basic Sprinkler", Price = 25000, Rarity = "Rare"},
        {Name = "Advanced Sprinkler", Price = 50000, Rarity = "Legendary"},
        {Name = "Godly Sprinkler", Price = 120000, Rarity = "Mythical"},
        {Name = "Lightning Rod", Price = 1000000, Rarity = "Mythical"},
        {Name = "Master Sprinkler", Price = 10000000, Rarity = "Divine"},
        {Name = "Favorite Tool", Price = 20000000, Rarity = "Divine"},
        {Name = "Harvest Tool", Price = 30000000, Rarity = "Divine"}
    }

    local GearShopTab = Window:MakeTab({
        Name = "Gear Shop",
        Icon = "rbxassetid://4483345998",
        PremiumOnly = false
    })

    local GearShopSection = GearShopTab:AddSection({ Name = "Auto Buy Equipments" })

    for _, gear in ipairs(gearlist) do
        GearShopSection:AddToggle({
            Name = gear.Name .. " - $" .. formatarNumero(gear.Price) .. " (" .. gear.Rarity .. ")",
            Default = false,
            Callback = function(state)
                _G["Auto" .. gear.Name:gsub(" ", "")] = state
            end
        })
    end
    
    ----------------------
    -- SETTINGS TAB
    ----------------------
    local SettingsTab = Window:MakeTab({
        Name = "Settings",
        Icon = "rbxassetid://4483345998",
        PremiumOnly = false
    })

    local SettingsSection = SettingsTab:AddSection({ Name = "Settings" })

    local antiAFKEnabled = false
    local antiAFKConnection

    SettingsSection:AddToggle({
        Name = "Anti AFK",
        Default = false,
        Callback = function(state)
            antiAFKEnabled = state
            if antiAFKEnabled then
                OrionLib:MakeNotification({
                    Name = "Anti AFK",
                    Content = "Anti Afk is Active!.",
                    Time = 3
                })
                local vu = game:GetService("VirtualUser")
                antiAFKConnection = game:GetService("Players").LocalPlayer.Idled:Connect(function()
                    vu:Button2Down(Vector2.new(0,0), workspace.CurrentCamera.CFrame)
                    wait(1)
                    vu:Button2Up(Vector2.new(0,0), workspace.CurrentCamera.CFrame)
                end)
            else
                OrionLib:MakeNotification({
                    Name = "Anti AFK",
                    Content = "Anti Afk is Disabled!.",
                    Time = 3
                })
                if antiAFKConnection then
                    antiAFKConnection:Disconnect()
                    antiAFKConnection = nil
                end
            end
        end
    })
    
                  SettingsSection:AddButton({
    Name = "Destroy Hub",
    Callback = function()
        OrionLib:Destroy()
    end
})

    ----------------------
    -- SCRIPT TAB
    ----------------------
    local ScriptsTab = Window:MakeTab({
        Name = "Scripts",
        Icon = "rbxassetid://4483345998",
        PremiumOnly = false
    })

    local ScriptsSection = ScriptsTab:AddSection({ Name = "Scripts Useful" })

    ScriptsSection:AddButton({
        Name = "Infinity Yield",
        Callback = function()
            loadstring(game:HttpGet("https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source"))()
            OrionLib:MakeNotification({
                Name = "Infinity Yield",
                Content = "Successfully executed!",
                Time = 3
            })
        end
    })  
   
    ----------------------
    -- LOOPS AUTOMÁTICOS
    ----------------------
    task.spawn(function()
        while task.wait(0.1) do
            for _, seed in ipairs(seedlist) do
                if _G["Auto" .. seed.Name:gsub(" ", "")] then
                    ReplicatedStorage.GameEvents.BuySeedStock:FireServer(seed.Name)
                end
            end
        end
    end)

    task.spawn(function()
        while task.wait(0.1) do
            for _, gear in ipairs(gearlist) do
                if _G["Auto" .. gear.Name:gsub(" ", "")] then
                    ReplicatedStorage.GameEvents.BuyGearStock:FireServer(gear.Name)
                end
            end
        end
    end)
    
    task.spawn(function()
        while task.wait(0.1) do
            for _, twilight in ipairs(twilightlist) do
                if _G["Auto" .. twilight.Name:gsub(" ", "")] then
                     ReplicatedStorage.GameEvents.BuyNightEventShopStock:FireServer(twilight.Name)
                end
            end
        end
    end)
    
    task.spawn(function()
        while task.wait(0.1) do
            for _, bloodilif in ipairs(bloodiliflist) do
                if _G["Auto" .. bloodilif.Name:gsub(" ", "")] then
                    ReplicatedStorage.GameEvents.BuyEventShopStock:FireServer(bloodilif.Name)
                end
            end
        end
    end)
    
    task.spawn(function()
        while task.wait(0.1) do
            for _, cosmetics in ipairs(cosmeticslist) do
                if _G["Auto" .. cosmetics.Name:gsub(" ", "")] then
                   ReplicatedStorage.GameEvents.BuyCosmeticItem:FireServer(cosmetics.Name)
                end
            end
        end
    end)
    
    OrionLib:Init()
    end
