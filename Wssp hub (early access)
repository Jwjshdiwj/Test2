local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()

local Window = OrionLib:MakeWindow({Name = "Wssp Hub", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})

local Tab = Window:MakeTab({
	Name = "Main",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = Tab:AddSection({
	Name = "Main Tab"
})

Tab:AddButton({
	Name = "No Cooldown ",
	Callback = function()
      		local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local tool = character:FindFirstChildOfClass("Tool") or player.Backpack:FindFirstChildOfClass("Tool")

while character.Humanoid.Health ~= 0 do
local localscript = tool:FindFirstChildOfClass("LocalScript")
local localscriptclone = localscript:Clone()
localscriptclone = localscript:Clone()
localscriptclone:Clone()
localscript:Destroy()
localscriptclone.Parent = tool
wait(0.1)
end
  	end    
})
Tab:AddButton({
	Name = "Slap Farm",
	Callback = function()
      		 loadstring(game:HttpGet('https://raw.githubusercontent.com/Pro666Pro/slapfarmgui/main/main.lua'))()
  	end    
})
Tab:AddButton({
	Name = "Slap farm 2",
	Callback = function()
      		loadstring(game:HttpGet("https://pastefy.app/hSjjge54/raw"))()

  	end    
})

Tab:AddButton({
	Name = "Slap farm 3",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/Donjosx/SBS/main/Bob-Fastest-AutoFarm(OriginalByAquopi).lua"))()

  	end    
})
Tab:AddButton({
	Name = "Swapper kick",
	Callback = function()
      		
loadstring(game:HttpGet("https://raw.githubusercontent.com/AquoupiRblx/SlapBattles/main/SwapperKick.lua", true))()
  	end    
})

Tab:AddButton({
	Name = "Recall kick",
	Callback = function()
      		local mode = "Recall" -- You can change to "Swapper" if you don't have the glove.
if mode == "Recall" then
loadstring(game:HttpGet("https://raw.githubusercontent.com/AquoupiRblx/SlapBattles/refs/heads/main/KickUIRecall.lua"))()
elseif mode == "Swapper" then 
loadstring(game:HttpGet("https://raw.githubusercontent.com/AquoupiRblx/SlapBattles/refs/heads/main/KickUISwapper.lua"))()
end
  	end    
})

Tab:AddButton({
	Name = "Swapper kick v2",
	Callback = function()
      		local mode = "Swapper" -- You can change to "Swapper" if you don't have the glove.
if mode == "Recall" then
loadstring(game:HttpGet("https://raw.githubusercontent.com/AquoupiRblx/SlapBattles/refs/heads/main/KickUIRecall.lua"))()
elseif mode == "Swapper" then 
loadstring(game:HttpGet("https://raw.githubusercontent.com/AquoupiRblx/SlapBattles/refs/heads/main/KickUISwapper.lua"))()
end
  	end    
})

Tab:AddButton({
	Name = "Camlock",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/brosula123/CAMLOCK/main/SKIBIDI"))()
  	end    
})
Tab:AddButton({
	Name = "Ban evidence",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/AquoupiRblx/SlapBattles/refs/heads/main/BanEvidence.lua"))()
  	end    
})

local Tab = Window:MakeTab({
	Name = "Anti",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = Tab:AddSection({
	Name = "Anti section"
})

Tab:AddButton({
	Name = "Anti Void",
	Callback = function()
      		loadstring(game:HttpGet("https://pastebin.com/raw/DajJP5iM"))()

  	end    
})

Tab:AddButton({
	Name = "Anti cube of death",
	Callback = function()
      		workspace.Arena.CubeOfDeathArea["the cube of death(i heard it kills)"].CanTouch = false

  	end    
})

Tab:AddButton({
	Name = "Anti Ragdoll",
	Callback = function()
      		getgenv().antiragdolsb = true

-- Reset character health
game.Players.LocalPlayer.Character.Humanoid.Health = 0

-- Monitor character reset and ragdoll status
game.Players.LocalPlayer.CharacterAdded:Connect(function()
    game.Players.LocalPlayer.Character:WaitForChild("Ragdolled").Changed:Connect(function()
        if game.Players.LocalPlayer.Character:WaitForChild("Ragdolled").Value == true and getgenv().antiragdolsb then
            repeat
                task.wait()
                game.Players.LocalPlayer.Character.Torso.Anchored = true
            until game.Players.LocalPlayer.Character:WaitForChild("Ragdolled").Value == false
            game.Players.LocalPlayer.Character.Torso.Anchored = false
        end
    end)
end)

  	end    
})

Tab:AddButton({
	Name = "Anti Megarock",
	Callback = function()
      		getgenv().antimegarocksb = true

while getgenv().antimegarocksb do
    for _, v in pairs(game.Players:GetChildren()) do
        if v.Character:FindFirstChild("rock") then
            v.Character:FindFirstChild("rock").CanTouch = false
            v.Character:FindFirstChild("rock").CanQuery = false
        end
    end
    task.wait()
end

  	end    
})

Tab:AddButton({
	Name = "Anti Knockoff",
	Callback = function()
      		getgenv().Antiknokoffsb = true

while getgenv().Antiknokoffsb do
    if game.Workspace.CurrentCamera 
        and game.Players.LocalPlayer.Character 
        and game.Players.LocalPlayer.Character:FindFirstChildOfClass("Humanoid") 
        and game.Workspace.CurrentCamera.CameraSubject ~= game.Players.LocalPlayer.Character:FindFirstChildOfClass("Humanoid") 
        and game.Workspace.CurrentCamera.CameraSubject == game.Workspace:FindFirstChild(game.Players.LocalPlayer.Name.."'s_falsehead") 
    then
        game.Workspace.CurrentCamera.CameraSubject = game.Players.LocalPlayer.Character:FindFirstChildOfClass("Humanoid")
    end
    task.wait()
end

  	end    
})

Tab:AddButton({
	Name = "Anti ice",
	Callback = function()
      		getgenv().antiicesb = true

while getgenv().antiicesb do
    for _, v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
        if v.Name == "Icecube" then
            v:Destroy()
            game.Players.LocalPlayer.Character.Humanoid.PlatformStand = false
            game.Players.LocalPlayer.Character.Humanoid.AutoRotate = true
        end
    end
    task.wait()
end

  	end    
})


local Tab = Window:MakeTab({
	Name = "Teleport",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = Tab:AddSection({
	Name = "Map Teleport section"
})

Tab:AddButton({
	Name = "Lobby",
	Callback = function()
      		local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local targetPart = workspace.Lobby.MR:GetChildren()[3].MeshPart

-- Ensure the character exists and is properly loaded
if character and targetPart then
    -- Move the character to the position of the target part
    character:MoveTo(targetPart.Position)
end

  	end    
})

Tab:AddButton({
	Name = "Arena",
	Callback = function()
      		local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local targetPart = workspace.Arena["main island"].Grass

-- Ensure the character exists and is properly loaded
if character and targetPart then
    -- Move the character to the position of the target part
    character:MoveTo(targetPart.Position)
end

  	end    
})

Tab:AddButton({
	Name = "Moai island",
	Callback = function()
      		local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local targetPart = workspace.Arena.island4.Grass

-- Ensure the character exists and is properly loaded
if character and targetPart then
    -- Move the character to the position of the target part
    character:MoveTo(targetPart.Position)
end

  	end    
})

Tab:AddButton({
	Name = "Castle",
	Callback = function()
      		local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local targetPart = workspace.Arena.CannonIsland["Cannon Island"].Model:GetChildren()[16]:GetChildren()[2]

-- Ensure the character exists and is properly loaded
if character and targetPart then
    -- Move the character to the position of the target part
    character:MoveTo(targetPart.Position)
end

  	end    
})

Tab:AddButton({
	Name = "Plate",
	Callback = function()
      		local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local targetPart = workspace.Arena["main island"]:GetChildren()[13].Plate

-- Ensure the character exists and is properly loaded
if character and targetPart then
    -- Move the character to the position of the target part
    character:MoveTo(targetPart.Position)
end

  	end    
})

Tab:AddButton({
	Name = "Tournament",
	Callback = function()
      		local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
local targetPart = workspace.Battlearena.Arena

-- Ensure the character exists and is properly loaded
if character and targetPart then
    -- Move the character to the position of the target part
    character:MoveTo(targetPart.Position)
end

  	end    
})
