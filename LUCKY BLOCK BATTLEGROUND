local player = game.Players.LocalPlayer
 
local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()

local Window = OrionLib:MakeWindow({Name = "KNZ hub", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})

local Home = Window:MakeTab({
	Name = "Home",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local HomeSection = Home:AddSection({
	Name = "Spawn Blocks"
})

Home:AddButton({
	Name = "Void Block[🥶🔥😎]",
	Callback = function()  		game:GetService("ReplicatedStorage").SpawnDiamondBlock:FireServer()

game:GetService("ReplicatedStorage").SpawnRainbowBlock:FireServer()

game:GetService("ReplicatedStorage").SpawnGalaxyBlock:FireServer()
  	end    
})

Home:AddButton({
	Name = "Normal Block[😐]!",
	Callback = function()     		game:GetService("ReplicatedStorage").SpawnDiamondBlock:FireServer()
  	end    
})

Home:AddButton({
	Name = "Purple Block[🙂]!",
	Callback = function()    game:GetService("ReplicatedStorage").SpawnSuperBlock:FireServer()
  	end    
})

Home:AddButton({
	Name = "Blue Block[😎]",
	Callback = function()   game:GetService("ReplicatedStorage").SpawnDiamondBlock:FireServer()
  	end    
})

Home:AddButton({
	Name = "Rainbow Block[😎🔥]!",
	Callback = function()      game:GetService("ReplicatedStorage").SpawnDiamondBlock:FireServer()
  	end    
})

Home:AddButton({
	Name = "Galaxy Block[😈]!",
	Callback = function()  game:GetService("ReplicatedStorage").SpawnGalaxyBlock:FireServer()
  	end    
})

local Player = Window:MakeTab({
	Name = "Player",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local PlayerSection = Player:AddSection({
	Name = "Ability"
})

Player:AddButton({
	Name = "high speed-once u died u need to re-enable this",
	Callback = function() 
player.Character.Humanoid.WalkSpeed = 50
end
})

Player:AddButton({
	Name = "High Jump - once u died u need to re-enable this",
	Callback = function() 
player.Character.Humanoid.JumpPower = 100
end
})
OrionLib:Init()
