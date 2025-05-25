if game.PlaceId == 126884695634066 then
	
  local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/jensonhirst/Orion/main/source')))()
  local Window = OrionLib:MakeWindow({Name = "R", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})
  
-- Values SeedShop
_G.AutoCarrot = true
_G.AutoStrawberry = true
_G.AutoBlueberry = true
_G.AutoOrangeTulip = true
_G.AutoTomato = true
_G.AutoCorn = true
_G.AutoDaffodil = true
_G.AutoWatermelon = true
_G.AutoPumpkin = true
_G.AutoApple = true
_G.AutoBamboo = true
_G.AutoCoconut = true
_G.AutoCactus = true
_G.AutoDragonFruit = true
_G.AutoMango = true
_G.AutoGrape = true
_G.AutoMushroom = true
_G.AutoPepper = true
_G.AutoCacao = true
_G.AutoBeanstalk = true
  
-- Values GearShop
_G.AutoWateringCan = true  
_G.AutoTrowel = true
_G.AutoRecallWrench = true
_G.AutoBasicSprinkler = true
_G.AutoAdvancedSprinkler = true
_G.AutoGodlySprinkler = true
_G.AutoLightningRod = true
_G.AutoMasterSprinkler = true
_G.AutoFavoriteTool = true
_G.AutoHarvestTool = true	
	
	-- Values CosmeticsShop
	_G.AutoTorch = true
	_G.AutoYellowUmbrella = true
	_G.AutoWoodFence = true
	_G.AutoHayBale = true
	_G.AutoWhileBench = true
	_G.AutoMediumWoodFlooring = true
	_G.AutoSignCrate = true
	_G.AutoCookingPot = true
	_G.AutoBlueWell = true
	_G.AutoBookshelf = true
	_G.AutoOrangeUmbrella = true
	_G.AutoShovelGrave = true
	_G.AutoLightOnGround = true
	_G.AutoSmallCircleTlle = true
	_G.AutoRockPlle = true
	_G.AutoCommonGnomeCrate = true
	_G.AutoSmallWoodArbour = true
	_G.AutoOpenSign = true
	
-- Values EventShop
	_G.AutoMysteriousCrate = true
	_G.AutoNightEgg = true
	_G.AutoNightSeedPack = true
	_G.AutoBloodBananaSeed = true
	_G.AutoMoonMelonSeed = true
	_G.AutoStarCaller = true
	_G.AutoBloodHedgehog = true
	_G.AutoBloodKiwi = true
	_G.AutoBloodOwl = true
  
-- Functions
  
  function AutoCarrot()
	while _G.AutoCarrot == true do
		local args = {
			[1] = "Carrot"
		}
		game:GetService("ReplicatedStorage").GameEvents.BuySeedStock:FireServer(unpack(args))
		task.wait(0.1)
	end
end

function AutoStrawberry()
	while _G.AutoStrawberry == true do
		local args = {
			[1] = "Strawberry"
		}
		game:GetService("ReplicatedStorage").GameEvents.BuySeedStock:FireServer(unpack(args))
		task.wait(0.1)
	end
end

function AutoBlueberry()
	while _G.AutoBlueberry == true do
		local args = {
			[1] = "Blueberry"
		}
		game:GetService("ReplicatedStorage").GameEvents.BuySeedStock:FireServer(unpack(args))
		task.wait(0.1)
	end
end

function AutoOrangeTulip()
	while _G.AutoOrangeTulip == true do
		local args = {
			[1] = "Orange Tulip"
		}
		game:GetService("ReplicatedStorage").GameEvents.BuySeedStock:FireServer(unpack(args))
		task.wait(0.1)
	end
end

function AutoTomato()
	while _G.AutoTomato == true do
		local args = {
			[1] = "Tomato"
		}
		game:GetService("ReplicatedStorage").GameEvents.BuySeedStock:FireServer(unpack(args))
		task.wait(0.1)
	end
end

function AutoCorn()
	while _G.AutoCorn == true do
		local args = {
			[1] = "Corn"
		}
		game:GetService("ReplicatedStorage").GameEvents.BuySeedStock:FireServer(unpack(args))
		task.wait(0.1)
	end
end

function AutoDaffodil()
	while _G.AutoDaffodil == true do
		local args = {
			[1] = "Daffodil"
		}
		game:GetService("ReplicatedStorage").GameEvents.BuySeedStock:FireServer(unpack(args))
		task.wait(0.1)
	end
end

function AutoWatermelon()
	while _G.AutoWatermelon == true do
		local args = {
			[1] = "Watermelon"
		}
		game:GetService("ReplicatedStorage").GameEvents.BuySeedStock:FireServer(unpack(args))
		task.wait(0.1)
	end
end

function AutoPumpkin()
	while _G.AutoPumpkin == true do
		local args = {
			[1] = "Pumpkin"
		}
		game:GetService("ReplicatedStorage").GameEvents.BuySeedStock:FireServer(unpack(args))
		task.wait(0.1)
	end
end

function AutoApple()
	while _G.AutoApple == true do
		local args = {
			[1] = "Apple"
		}
		game:GetService("ReplicatedStorage").GameEvents.BuySeedStock:FireServer(unpack(args))
		task.wait(0.1)
	end
end

function AutoBamboo()
	while _G.AutoBamboo == true do
		local args = {
			[1] = "Bamboo"
		}
		game:GetService("ReplicatedStorage").GameEvents.BuySeedStock:FireServer(unpack(args))
		task.wait(0.1)
	end
end

function AutoCoconut()
	while _G.AutoCoconut == true do
		local args = {
			[1] = "Coconut"
		}
		game:GetService("ReplicatedStorage").GameEvents.BuySeedStock:FireServer(unpack(args))
		task.wait(0.1)
	end
end

function AutoCactus()
	while _G.AutoCactus == true do
		local args = {
			[1] = "Cactus"
		}
		game:GetService("ReplicatedStorage").GameEvents.BuySeedStock:FireServer(unpack(args))
		task.wait(0.1)
	end
end

function AutoDragonFruit()
	while _G.AutoDragonFruit == true do
		local args = {
			[1] = "Dragon Fruit"
		}
		game:GetService("ReplicatedStorage").GameEvents.BuySeedStock:FireServer(unpack(args))
		task.wait(0.1)
	end
end

function AutoMango()
	while _G.AutoMango == true do
		local args = {
			[1] = "Mango"
		}
		game:GetService("ReplicatedStorage").GameEvents.BuySeedStock:FireServer(unpack(args))
		task.wait(0.1)
	end
end

function AutoGrape()
	while _G.AutoGrape == true do
		local args = {
			[1] = "Grape"
		}
		game:GetService("ReplicatedStorage").GameEvents.BuySeedStock:FireServer(unpack(args))
		task.wait(0.1)
	end
end

function AutoMushroom()
	while _G.AutoMushroom == true do
		local args = {
			[1] = "Mushroom"
		}
		game:GetService("ReplicatedStorage").GameEvents.BuySeedStock:FireServer(unpack(args))
		task.wait(0.1)
	end
end

function AutoPepper()
	while _G.AutoPepper == true do
		local args = {
			[1] = "Pepper"
		}
		game:GetService("ReplicatedStorage").GameEvents.BuySeedStock:FireServer(unpack(args))
		task.wait(0.1)
	end
end

function AutoCacao()
	while _G.AutoCacao == true do
		local args = {
			[1] = "Cacao"
		}
		game:GetService("ReplicatedStorage").GameEvents.BuySeedStock:FireServer(unpack(args))
		task.wait(0.1)
	end
end

function AutoBeanstalk()
	while _G.AutoBeanstalk == true do
		local args = {
			[1] = "Beanstalk"
		}
		game:GetService("ReplicatedStorage").GameEvents.BuySeedStock:FireServer(unpack(args))
		task.wait(0.1)
	end
end
  
  function AutoWateringCan()
	while _G.AutoWateringCan == true do
		local args = {
			[1] = "Watering Can"
		}
		game:GetService("ReplicatedStorage").GameEvents.BuyGearStock:FireServer(unpack(args))
		task.wait(0.1)
	end
end

function AutoTrowel()
	while _G.AutoTrowel == true do
		local args = {
			[1] = "Trowel"
		}
		game:GetService("ReplicatedStorage").GameEvents.BuyGearStock:FireServer(unpack(args))
		task.wait(0.1)
	end
end

function AutoRecallWrench()
	while _G.AutoRecallWrench == true do
		local args = {
			[1] = "Recall Wrench"
		}
		game:GetService("ReplicatedStorage").GameEvents.BuyGearStock:FireServer(unpack(args))
		task.wait(0.1)
	end
end

function AutoBasicSprinkler()
	while _G.AutoBasicSprinkler == true do
		local args = {
			[1] = "Basic Sprinkler"
		}
		game:GetService("ReplicatedStorage").GameEvents.BuyGearStock:FireServer(unpack(args))
		task.wait(0.1)
	end
end

function AutoAdvancedSprinkler()
	while _G.AutoAdvancedSprinkler == true do
		local args = {
			[1] = "Advanced Sprinkler"
		}
		game:GetService("ReplicatedStorage").GameEvents.BuyGearStock:FireServer(unpack(args))
		task.wait(0.1)
	end
end

function AutoGodlySprinkler()
	while _G.AutoGodlySprinkler == true do
		local args = {
			[1] = "Godly Sprinkler"
		}
		game:GetService("ReplicatedStorage").GameEvents.BuyGearStock:FireServer(unpack(args))
		task.wait(0.1)
	end
end

function AutoLightningRod()
	while _G.AutoLightningRod == true do
		local args = {
			[1] = "Lightning Rod"
		}
		game:GetService("ReplicatedStorage").GameEvents.BuyGearStock:FireServer(unpack(args))
		task.wait(0.1)
	end
end

function AutoMasterSprinkler()
	while _G.AutoMasterSprinkler == true do
		local args = {
			[1] = "Master Sprinkler"
		}
		game:GetService("ReplicatedStorage").GameEvents.BuyGearStock:FireServer(unpack(args))
		task.wait(0.1)
	end
end

function AutoFavoriteTool()
	while _G.AutoFavoriteTool == true do
		local args = {
			[1] = "Favorite Tool"
		}
		game:GetService("ReplicatedStorage").GameEvents.BuyGearStock:FireServer(unpack(args))
		task.wait(0.1)
	end
end
	
	function AutoHarvestTool()
		while _G.AutoHarvestTool == true do
			local args = {
    [1] = "Harvest Tool"
}

game:GetService("ReplicatedStorage").GameEvents.BuyGearStock:FireServer(unpack(args))
			task.wait(0.1)
		  end
	end
	
	function AutoTorch()
		while _G.AutoTorch == true do
			local args = {
    [1] = "Torch"
}

game:GetService("ReplicatedStorage").GameEvents.BuyCosmeticItem:FireServer(unpack(args))
			task.wait(0.1)
		  end
	end
	
	function AutoYellowUmbrella()
		while _G.AutoYellowUmbrella == true do
			local args = {
    [1] = "Yellow Umbrella"
}

game:GetService("ReplicatedStorage").GameEvents.BuyCosmeticItem:FireServer(unpack(args))
			task.wait(0.1)
			  end
		end
	
	function AutoWhiteBench()
		while _G.AutoWhiteBench == true do
			local args = {
    [1] = "White Bench"
}

game:GetService("ReplicatedStorage").GameEvents.BuyCosmeticItem:FireServer(unpack(args))
			task.wait(0.1)
		  end
	end
	
	function AutoWoodFence()
		while _G.AutoWoodFence == true do
			local args = {
    [1] = "Wood Fence"
}

game:GetService("ReplicatedStorage").GameEvents.BuyCosmeticItem:FireServer(unpack(args))
			task.wait(0.1)
	  	end
	end
	
	function AutoMediumWoodFlooring()
		while _G.AutoMediumWoodFlooring == true do
			local args = {
    [1] = "Medium Wood Flooring"
}

game:GetService("ReplicatedStorage").GameEvents.BuyCosmeticItem:FireServer(unpack(args))
			task.wait(0.1)
	  	end
	end
	
	function AutoHayBale()
		while _G.AutoHayBale == true do
			local args = {
    [1] = "Hay Bale"
}

game:GetService("ReplicatedStorage").GameEvents.BuyCosmeticItem:FireServer(unpack(args))
			task.wait(0.1)
	  	end
	end
	
	function AutoSignCrate()
		while _G.AutoSignCrate == true do
			local args = {
    [1] = "Sign Crate"
}

game:GetService("ReplicatedStorage").GameEvents.BuyCosmeticCrate:FireServer(unpack(args))
			task.wait(0.1)
		  end
	end
	
	function AutoCookingPot()
		while _G.AutoCookingPot == true do
			local args = {
    [1] = "Cooking Pot"
}

game:GetService("ReplicatedStorage").GameEvents.BuyCosmeticItem:FireServer(unpack(args))
			task.wait(0.1)
		  end
	end
	
	function AutoBlueWell()
		while _G.AutoBlueWell == true do
			local args = {
    [1] = "Blue Well"
}

game:GetService("ReplicatedStorage").GameEvents.BuyCosmeticItem:FireServer(unpack(args))
			task.wait(0.1)
		  end
	end
	
	function AutoBookshelf()
		while _G.AutoBookshelf == true do
		local args = {
    [1] = "Bookshelf"
}

game:GetService("ReplicatedStorage").GameEvents.BuyCosmeticItem:FireServer(unpack(args))
			task.wait(0.1)
			  end
		end
	
	function AutoOrangeUmbrella()
		while _G.AutoOrangeUmbrella == true do
			local args = {
    [1] = "Orange Umbrella"
}

game:GetService("ReplicatedStorage").GameEvents.BuyCosmeticItem:FireServer(unpack(args))
			task.wait(0.1)
		  	end
		end
	
	function AutoShovelGrave()
		while _G.AutoShovelGrave == true do
			local args = {
    [1] = "Shovel Grave"
}

game:GetService("ReplicatedStorage").GameEvents.BuyCosmeticItem:FireServer(unpack(args))
			task.wait(0.1)
	  	end
	end
	
	function AutoLightOnGround()
		while _G.AutoLightOnGround == true do
		local args = {
    [1] = "Light On Ground"
}

game:GetService("ReplicatedStorage").GameEvents.BuyCosmeticItem:FireServer(unpack(args))
			task.wait(0.1)
		  end
	end
	
	function AutoSmallCircleTile()
		while _G.AutoSmallCircleTile == true do
		local args = {
    [1] = "Small Circle Tile"
}

game:GetService("ReplicatedStorage").GameEvents.BuyCosmeticItem:FireServer(unpack(args))
		task.wait(0.1)
	  end
end
	
	function AutoSmallWoodArbour()
		while _G.AutoSmallWoodArbour == true do
			local args = {
    [1] = "Small Wood Arbour"
}

game:GetService("ReplicatedStorage").GameEvents.BuyCosmeticItem:FireServer(unpack(args))
			task.wait(0.1)
		  end
	end
	
	function AutoCommonGnomeCrate()
		while _G.AutoCommonGnomeCrate == true do
			local args = {
    [1] = "Common Gnome Crate"
}

game:GetService("ReplicatedStorage").GameEvents.BuyCosmeticCrate:FireServer(unpack(args))
			task.wait(0.1)
			  end
		end
	
	function AutoMysteriousCrate()
		while _G.AutoMysteriousCrate == true do
			local args = {
    [1] = "Mysterious Crate"
}

game:GetService("ReplicatedStorage").GameEvents.BuyEventShopStock:FireServer(unpack(args))
			task.wait(0.1)
		  end
	end
	
	function AutoNightEgg()
		while _G.AutoNightEgg == true do
			local args = {
    [1] = "Night Egg"
}

game:GetService("ReplicatedStorage").GameEvents.BuyEventShopStock:FireServer(unpack(args))
			task.wait(0.1)
	  	end
	end
	
	function AutoNightSeedPack()
		while _G.AutoNightSeedPack == true do
			local args = {
    [1] = "Night Seed Pack"
}

game:GetService("ReplicatedStorage").GameEvents.BuyEventShopStock:FireServer(unpack(args))
			task.wait(0.1)
		  end
	end
	
	function AutoBloodBanana()
		while _G.AutoBloodBanana == true do
			local args = {
    [1] = "Blood Banana"
}

game:GetService("ReplicatedStorage").GameEvents.BuyEventShopStock:FireServer(unpack(args))
			task.wait(0.1)
		  end
	end
	
	function AutoMoonMelon()
		while _G.AutoMoonMelon == true do
			local args = {
    [1] = "Moon Melon"
}

game:GetService("ReplicatedStorage").GameEvents.BuyEventShopStock:FireServer(unpack(args))
			task.wait(0.1)
		  end
	end
	
	function AutoStarCaller()
		while _G.AutoStarCaller == true do
			local args = {
    [1] = "Star Caller"
}

game:GetService("ReplicatedStorage").GameEvents.BuyEventShopStock:FireServer(unpack(args))
			task.wait(0.1)
		  end
	end
	
	function AutoBloodHedgehog()
		while _G.AutoBloodHedgehog == true do
			local args = {
    [1] = "Blood Hedgehog"
}

game:GetService("ReplicatedStorage").GameEvents.BuyEventShopStock:FireServer(unpack(args))
			task.wait(0.1)
		  	end
		end
	
	function AutoBloodKiwi()
		while _G.AutoBloodKiwi == true do
			local args = {
    [1] = "Blood Kiwi"
}

game:GetService("ReplicatedStorage").GameEvents.BuyEventShopStock:FireServer(unpack(args))
			task.wait(0.1)
			  end
	end
	
	function AutoBloodOwl()
		while _G.AutoBloodOwl == true do
			local args = {
    [1] = "Blood Owl"
}

game:GetService("ReplicatedStorage").GameEvents.BuyEventShopStock:FireServer(unpack(args))
			task.wait(0.1)
		  end
	end
	
	function AutoOpenSign()
		while _G.AutoOpenSign == true do
			local args = {
    [1] = "OpenCrate",
    [2] = workspace.Farm.Farm.Important.Objects_Physical.CosmeticCrate
}

game:GetService("ReplicatedStorage").GameEvents.CosmeticCrateService:FireServer(unpack(args))
			task.wait(0.1)
		  end
	end
	
	local BloodilifShopTab = Window:MakeTab({
	Name = "Bloodilif Shop",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})
	
	local CosmeticsShopTab = Window:MakeTab({
	Name = "Cosmetics Shop",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})
	
  local SeedShopTab = Window:MakeTab({
	Name = "Seed Shop",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})
  
  local GearShopTab = Window:MakeTab({
	Name = "Gear Shop",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})
	
	local SettingsTab = Window:MakeTab({
	Name = "Settings",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})
  
-- Toggles + Seccoes
  
-- SeedShop  
  local Section = SeedShopTab:AddSection({
	Name = "Auto Buy Seeds"
})
  
  SeedShopTab:AddToggle({
	Name = "Buy Carrot ｢ 10$ 」Common",
	Default = false,
	Callback = function(Value)
		_G.AutoCarrot = Value
		AutoCarrot()
	end    
})
  
  SeedShopTab:AddToggle({
	Name = "Buy Strawberry「 50$ 」Common",
	Default = false,
	Callback = function(Value)
		_G.AutoStrawberry = Value
		AutoStrawberry()
	end    
})

SeedShopTab:AddToggle({
	Name = "Buy Blueberry「 400$ 」Uncommon",
	Default = false,
	Callback = function(Value)
		_G.AutoBlueberry = Value
		AutoBlueberry()
	end    
})

SeedShopTab:AddToggle({
	Name = "Buy Orange Tulip「 600$ 」Uncommon",
	Default = false,
	Callback = function(Value)
		_G.AutoOrangeTulip = Value
		AutoOrangeTulip()
	end    
})

SeedShopTab:AddToggle({
	Name = "Buy Tomato「 800$ 」Rare",
	Default = false,
	Callback = function(Value)
		_G.AutoTomato = Value
		AutoTomato()
	end    
})

SeedShopTab:AddToggle({
	Name = "Buy Corn「 1,300$ 」Rare",
	Default = false,
	Callback = function(Value)
		_G.AutoCorn = Value
		AutoCorn()
	end    
})

SeedShopTab:AddToggle({
	Name = "Buy Daffodil「 1,000$ 」Rare",
	Default = false,
	Callback = function(Value)
		_G.AutoDaffodil = Value
		AutoDaffodil()
	end    
})

SeedShopTab:AddToggle({
	Name = "Buy Watermelon「 2,500$ 」Legendary",
	Default = false,
	Callback = function(Value)
		_G.AutoWatermelon = Value
		AutoWatermelon()
	end    
})

SeedShopTab:AddToggle({
	Name = "Buy Pumpkin「 3,000$ 」Legendary",
	Default = false,
	Callback = function(Value)
		_G.AutoPumpkin = Value
		AutoPumpkin()
	end    
})

SeedShopTab:AddToggle({
	Name = "Buy Apple「 3,250$ 」Legendary",
	Default = false,
	Callback = function(Value)
		_G.AutoApple = Value
		AutoApple()
	end    
})

SeedShopTab:AddToggle({
	Name = "Buy Bamboo「 4,000$ 」Legendary",
	Default = false,
	Callback = function(Value)
		_G.AutoBamboo = Value
		AutoBamboo()
	end    
})

SeedShopTab:AddToggle({
	Name = "Buy Coconut「 6,000$ 」Mythical",
	Default = false,
	Callback = function(Value)
		_G.AutoCoconut = Value
		AutoCoconut()
	end    
})

SeedShopTab:AddToggle({
	Name = "Buy Cactus「 15,000$ 」Mythical",
	Default = false,
	Callback = function(Value)
		_G.AutoCactus = Value
		AutoCactus()
	end    
})

SeedShopTab:AddToggle({
	Name = "Buy Dragon Fruit「 50,000$ 」Mythical",
	Default = false,
	Callback = function(Value)
		_G.AutoDragonFruit = Value
		AutoDragonFruit()
	end    
})

SeedShopTab:AddToggle({
	Name = "Buy Mango「 100,000$ 」Mythical",
	Default = false,
	Callback = function(Value)
		_G.AutoMango = Value
		AutoMango()
	end    
})

SeedShopTab:AddToggle({
	Name = "Buy Grape「 850,000$ 」Divine",
	Default = false,
	Callback = function(Value)
		_G.AutoGrape = Value
		AutoGrape()
	end    
})

SeedShopTab:AddToggle({
	Name = "Buy Mushroom「 150,000$ 」Divine",
	Default = false,
	Callback = function(Value)
		_G.AutoMushroom = Value
		AutoMushroom()
	end    
})

SeedShopTab:AddToggle({
	Name = "Buy Pepper「 1,000,000$ 」Divine",
	Default = false,
	Callback = function(Value)
		_G.AutoPepper = Value
		AutoPepper()
	end    
})

SeedShopTab:AddToggle({
	Name = "Buy Cacao「 2,500,000$ 」Divine",
	Default = false,
	Callback = function(Value)
		_G.AutoCacao = Value
		AutoCacao()
	end    
})

SeedShopTab:AddToggle({
	Name = "Buy Beanstalk「 10,000,000$ 」Prismatic",
	Default = false,
	Callback = function(Value)
		_G.AutoBeanstalk = Value
		AutoBeanstalk()
	end    
})
  
-- GearShop  
  local Section = GearShopTab:AddSection({
	Name = "Buy Equipament"
})
  
  GearShopTab:AddToggle({
	Name = "Buy Watering Can「 50,000$ 」Common",
	Default = false,
	Callback = function(Value)
		_G.AutoWateringCan = Value
		AutoWateringCan()
	end
})

GearShopTab:AddToggle({
	Name = "Buy Trowel「 100,000$ 」Uncommon",
	Default = false,
	Callback = function(Value)
		_G.AutoTrowel = Value
		AutoTrowel()
	end
})

GearShopTab:AddToggle({
	Name = "Buy Recall Wrench「 150,000$ 」Uncommon",
	Default = false,
	Callback = function(Value)
		_G.AutoRecallWrench = Value
		AutoRecallWrench()
	end
})

GearShopTab:AddToggle({
	Name = "Buy Basic Sprinkler「 25,000$ 」Rare",
	Default = false,
	Callback = function(Value)
		_G.AutoBasicSprinkler = Value
		AutoBasicSprinkler()
	end
})

GearShopTab:AddToggle({
	Name = "Buy Advanced Sprinkler「 50,000$ 」Legendary",
	Default = false,
	Callback = function(Value)
		_G.AutoAdvancedSprinkler = Value
		AutoAdvancedSprinkler()
	end
})

GearShopTab:AddToggle({
	Name = "Buy Godly Sprinkler「 120,000$ 」Mythical",
	Default = false,
	Callback = function(Value)
		_G.AutoGodlySprinkler = Value
		AutoGodlySprinkler()
	end
})

GearShopTab:AddToggle({
	Name = "Buy Lightning Rod「 1,000,000$ 」Mythical",
	Default = false,
	Callback = function(Value)
		_G.AutoLightningRod = Value
		AutoLightningRod()
	end
})

GearShopTab:AddToggle({
	Name = "Buy Master Sprinkler「 10,000,000$ 」Divine",
	Default = false,
	Callback = function(Value)
		_G.AutoMasterSprinkler = Value
		AutoMasterSprinkler()
	end
})

GearShopTab:AddToggle({
	Name = "Buy Favorite Tool「 20,000,000$ 」Divine",
	Default = false,
	Callback = function(Value)
		_G.AutoFavoriteTool = Value
		AutoFavoriteTool()
	end
})
	
	GearShopTab:AddToggle({
	Name = "Buy Harvest Tool「 30,000,000$ 」Divine",
	Default = false,
	Callback = function(Value)
		_G.AutoHarvestTool = Value
		AutoHarvestTool()
	end
})
  
-- CosmeticsShop   
  local Section = CosmeticsShopTab:AddSection({
	Name = "Buy Decorations"
})
	
	CosmeticsShopTab:AddToggle({
	Name = "Buy Torch「 800,000$ 」Common",
	Default = false,
	Callback = function(Value)
		_G.AutoTorch = Value
		AutoTorch()
	end
})
	
	CosmeticsShopTab:AddToggle({
	Name = "Buy Yellow Umbrella「 1,000,000$ 」Common",
	Default = false,
	Callback = function(Value)
		_G.AutoYellowUmbrella = Value
		AutoYellowUmbrella()
	end
})
	
	CosmeticsShopTab:AddToggle({
	Name = "Buy Orange Umbrella「 1,000,000$ 」Common",
	Default = false,
	Callback = function(Value)
		_G.AutoOrangeUmbrella = Value
		AutoOrangeUmbrella()
	end
})

CosmeticsShopTab:AddToggle({
	Name = "Buy Small Circle Tile「 150,000$ 」Common",
	Default = false,
	Callback = function(Value)
		_G.AutoSmallCircleTile = Value
		AutoSmallCircleTile()
	end
})
	
	CosmeticsShopTab:AddToggle({
	Name = "Buy White Bench「 1,000,000$ 」Uncommon",
	Default = false,
	Callback = function(Value)
		_G.AutoWhiteBench = Value
		AutoWhiteBench()
	end
})
	
	CosmeticsShopTab:AddToggle({
	Name = "Buy Wood Fence「 750,000$ 」Uncommon",
	Default = false,
	Callback = function(Value)
		_G.AutoWoodFence = Value
		AutoWoodFence() 
	end
})
	
	CosmeticsShopTab:AddToggle({
	Name = "Buy Medium Wood Flooring「 1,000,000$ 」Uncommon ",
	Default = false,
	Callback = function(Value)
		_G.AutoMediumWoodFlooring = Value
		AutoMediumWoodFlooring() 
	end
})
	
	CosmeticsShopTab:AddToggle({
	Name = "Buy Hay Bale「 750,000$ 」Uncommon ",
	Default = false,
	Callback = function(Value)
		_G.AutoHayBale = Value
		AutoHayBale() 
	end
})
	
	CosmeticsShopTab:AddToggle({
	Name = "Buy Bookshelf「 1,000,000$ 」Uncommun",
	Default = false,
	Callback = function(Value)
		_G.AutoBookshelf = Value
		AutoBookshelf() 
	end
})
	
	CosmeticsShopTab:AddToggle({
	Name = "Buy Shovel Grave「 1,000,000$ 」Uncommun",
	Default = false,
	Callback = function(Value)
		_G.AutoShovelGrave = Value
		AutoShovelGrave() 
	end
})
	
	CosmeticsShopTab:AddToggle({
	Name = "Buy Light On Ground「 1,000,000$ 」Uncommun",
	Default = false,
	Callback = function(Value)
		_G.AutoLightOnGround = Value
		AutoLightOnGround() 
	end
})
	
	CosmeticsShopTab:AddToggle({
	Name = "Buy Sign Crate「 55,000,000$ 」Rare",
	Default = false,
	Callback = function(Value)
		_G.AutoSignCrate = Value
		AutoSignCrate() 
	end
})
	
	CosmeticsShopTab:AddToggle({
	Name = "Buy Cooking Pot「 12,000,000$ 」Rare",
	Default = false,
	Callback = function(Value)
		_G.AutoCookingPot = Value
		AutoCookingPot() 
	end
})
	
	CosmeticsShopTab:AddToggle({
	Name = "Buy Small Wood Arbour「 13,000,000$ 」Rare",
	Default = false,
	Callback = function(Value)
		_G.AutoSmallWoodArbour = Value
		AutoCookingPot() 
	end
})
	
	CosmeticsShopTab:AddToggle({
	Name = "Buy Common Gnome Crate「 13,000,000$ 」Rare",
	Default = false,
	Callback = function(Value)
		_G.AutoCommonGnomeCrate = Value
		AutoCommonGnomeCrate() 
	end
})
	
	CosmeticsShopTab:AddToggle({
	Name = "Buy Blue Well「 60,000,000$ 」Legendary",
	Default = false,
	Callback = function(Value)
		_G.AutoBlueWell = Value
		AutoBlueWell() 
	end
})
	
	local Section = BloodilifShopTab:AddSection({
	Name = "Buy Itens Event"
})
	
	BloodilifShopTab:AddToggle({
	Name = "Buy Mysterious Crate「 10,000,000$ 」Legendary",
	Default = false,
	Callback = function(Value)
		_G.AutoMysteriousCrate = Value
		AutoMysteriousCrate() 
	end
})
	
	BloodilifShopTab:AddToggle({
	Name = "Buy Night Egg「 25,000,000$ 」Rare",
	Default = false,
	Callback = function(Value)
		_G.AutoNightEgg = Value
		AutoNightEgg() 
	end
})
	
	BloodilifShopTab:AddToggle({
	Name = "Buy Night Seed Pack「 25,000,000$ 」Rare",
	Default = false,
	Callback = function(Value)
		_G.AutoNightSeedPack = Value
		AutoNightSeedPack() 
	end
})
	
	BloodilifShopTab:AddToggle({
	Name = "Buy Blood Banana「 200,000$ 」Mythical",
	Default = false,
	Callback = function(Value)
		_G.AutoBloodBanana = Value
		AutoBloodBanana() 
	end
})
	
	BloodilifShopTab:AddToggle({
	Name = "Buy Moon Melon「 500,000$ 」Mythical",
	Default = false,
	Callback = function(Value)
		_G.AutoMoonMelon = Value
		AutoMoonMelon() 
	end
})
	
	BloodilifShopTab:AddToggle({
	Name = "Buy Star Caller「 12,000,000$ 」Legendary",
	Default = false,
	Callback = function(Value)
		_G.AutoStarCaller = Value
		AutoStarCaller() 
	end
})
	
	BloodilifShopTab:AddToggle({
	Name = "Buy Blood Hedgehog「 23,000,000$ 」Mythical",
	Default = false,
	Callback = function(Value)
		_G.AutoBloodHedgehog = Value
		AutoBloodHedgehog() 
	end
})
	
BloodilifShopTab:AddToggle({
	Name = "Buy Blood Kiwi「 20,000,000$ 」Legendary",
	Default = false,
	Callback = function(Value)
		_G.AutoBloodKiwi = Value
		AutoBloodKiwi() 
	end
})
	
	BloodilifShopTab:AddToggle({
	Name = "Buy Blood Owl「 60,000,000$ 」divine",
	Default = false,
	Callback = function(Value)
		_G.AutoBloodOwl = Value
		AutoBloodOwl() 
	end
})
	
	local Section = CosmeticsShopTab:AddSection({
	Name = "Crates"
})
	
	CosmeticsShopTab:AddToggle({
	Name = "Open Sign Crate",
	Default = false,
	Callback = function(Value)
		_G.AutoOpenSign = Value
		AutoOpenSign() 
	end
})
	
	-- Fps Booster
	local originalProperties = {}

SettingsTab:AddToggle({
	Name = "FPS Boost (Disable Graphics)",
	Default = false,
	Callback = function(Value)
		if Value then
			-- Ativando FPS Boost
			for _, v in pairs(game:GetDescendants()) do
				if v:IsA("BasePart") and not v:IsDescendantOf(game.Players) then
					originalProperties[v] = {
						Material = v.Material,
						Reflectance = v.Reflectance
					}
					v.Material = Enum.Material.SmoothPlastic
					v.Reflectance = 0
				elseif v:IsA("Decal") or v:IsA("Texture") then
					originalProperties[v] = {
						Transparency = v.Transparency
					}
					v.Transparency = 1
				elseif v:IsA("ParticleEmitter") or v:IsA("Trail") then
					originalProperties[v] = {
						Enabled = v.Enabled
					}
					v.Enabled = false
				end
			end
			settings().Rendering.QualityLevel = Enum.QualityLevel.Level01
			setfpscap(30)

		else
			-- Restaurando as propriedades originais
			for v, props in pairs(originalProperties) do
				if v and v.Parent then
					for prop, val in pairs(props) do
						pcall(function()
							v[prop] = val
						end)
					end
				end
			end
			originalProperties = {}
			settings().Rendering.QualityLevel = Enum.QualityLevel.Automatic
			setfpscap(999)
		end
	end
})

	-- Anti Afk
local antiAfkEnabled = false
local antiAfkConnection

SettingsTab:AddToggle({
    Name = "Anti AFK",
    Default = false,
    Callback = function(Value)
        antiAfkEnabled = Value
        if antiAfkEnabled then
            antiAfkConnection = game:GetService("Players").LocalPlayer.Idled:Connect(function()
                VirtualUser = game:service'VirtualUser'
                VirtualUser:Button2Down(Vector2.new(0,0), workspace.CurrentCamera.CFrame)
                VirtualUser:Button2Up(Vector2.new(0,0), workspace.CurrentCamera.CFrame)
            end)
            OrionLib:MakeNotification({
                Name = "Anti AFK",
                Content = "Anti AFK Enabled!",
                Time = 3
            })
        else
            if antiAfkConnection then
                antiAfkConnection:Disconnect()
                antiAfkConnection = nil
            end
            OrionLib:MakeNotification({
                Name = "Anti AFK",
                Content = "Anti AFK Disabled!",
                Time = 3
            })
        end
    end
})
	
end
OrionLib:Init()
