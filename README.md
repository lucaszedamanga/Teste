local player = game.Players.LocalPlayer
if player.Name == "Carneassadagotoza" then
    player:Kick("Você foi expulso do jogo.") -- Mensagem opcional ao expulsar o jogador
end



local DrRayLibrary = loadstring(game:HttpGet("https://raw.githubusercontent.com/AZYsGithub/DrRay-UI-Library/main/DrRay.lua"))()
local window = DrRayLibrary:Load("DrRay", "Default")

local tab = DrRayLibrary.newTab("Farm", "ImageIdHere")
local laap = falss
tab.newToggle("auto rebirth", "Da rebirth automático ", false, function(valuri)
 laap = valuri
    if laap then
    while laap do
    if laap then
    wait()
    local multiplicador = 2


local args = {
    [1] = game:GetService("Players").LocalPlayer
}


for i = 1, multiplicador - 1 do
    table.insert(args, game:GetService("Players").LocalPlayer)
end


game:GetService("ReplicatedStorage").Functions.Rebirth:InvokeServer(unpack(args))
         end
      end
    end
end)


local loop = false
tab.newToggle("auto fighters 30", "Fighers 30", false, function(value)
  loop = value
  
    if loop then
      while loop do
        if loop then
            
                wait()
            if loop then    
          local player = game.Players.LocalPlayer
    local char = player.Character

    char.HumanoidRootPart.CFrame = CFrame.new(-1067, 12, -1307)
    wait(5)

    fireclickdetector(workspace.Interactive.NPCQUEST.NpcTalk.ClickDetector)
    wait(7)
            end
            
    local player = game.Players.LocalPlayer
    local character = player.Character or player.CharacterAdded:Wait()
    local Humanoid = character:FindFirstChildOfClass("Humanoid")
    local HumanoidRootPart = character:FindFirstChild("HumanoidRootPart")

    local pasta = workspace:WaitForChild("Npcs")
    local subpasta = pasta:WaitForChild("Fighters3")
    for _, npc in pairs(subpasta:GetChildren()) do
        local humanoidRootPart = npc:FindFirstChild("HumanoidRootPart")
        local humanoid = npc:FindFirstChildOfClass("Humanoid")

        if humanoidRootPart and humanoid and loop  then
            wait(0.5)
            
            if loop then
                
            local npcPosition = humanoidRootPart.Position
            print(npcPosition) 
                      
                      
            local direction = (HumanoidRootPart.Position - npcPosition).Unit 
            local newPosition = npcPosition + direction * 3 

            
            HumanoidRootPart.CFrame = CFrame.lookAt(newPosition, npcPosition)
            end
            wait(0.2)

            
            
local player = game.Players.LocalPlayer
local backpack = player:WaitForChild("Backpack")
local character = player.Character or player.CharacterAdded:Wait()

local function equipCombat()
    local tool = backpack:FindFirstChild("Combat")
    if tool then
        character.Humanoid:EquipTool(tool)
    else
        print("Item 'Combat' não encontrado na mochila.")
    end
end

equipCombat()
            
            

humanoid.Health = humanoid.Health -1
      wait(0.2)
            humanoid.Health = 0 
            
local function checarnpc()
while true do 
wait(0.1)
local pasta = workspace:WaitForChild("Npcs")
    local subpasta = pasta:WaitForChild("Fighters3")
    for _, npc in pairs(subpasta:GetChildren()) do
        local humanoidRootPart = npc:FindFirstChild("HumanoidRootPart")
        local humanoid = npc:FindFirstChildOfClass("Humanoid")

    
        
    if  not humanoid or not humanoidRootPart then
        wait(0.4)
        
        print("sem npcs")
              end
         end
     end
end
            
            coroutine.wrap(checarnpc)()
            wait(0.5)
            if loop then
            local args = {
                [1] = game:GetService("Players").LocalPlayer
            }

            game:GetService("ReplicatedStorage").Events.boxing:FireServer(unpack(args))
            wait(0.5)
            end
            
local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()

local function unequipCombat()
    local tool = character:FindFirstChild("Combat")
    if tool then
        tool.Parent = player:WaitForChild("Backpack")
    else
        print("Item 'Combat' não está equipado.")
    end
end

unequipCombat()

            
            humanoid.Health = 100
            humanoid.Health = 900
Humanoid.Health = Humanoid.Health +1
        end
    end
                
                
          
        end
      end
    end
end)

local inf = false 
tab.newToggle("Auto sensei karatê", "Karatê sensei", false, function(Value)
           inf = Value
          if inf then
                    while inf do
                              if inf then
                                        wait()
                                        if inf then
          local player = game.Players.LocalPlayer
local char = player.Character
char.HumanoidRootPart.CFrame = CFrame.new(-802, 26, -2000)
                                        end
wait(5)
                                        if inf then
fireclickdetector(workspace.Interactive.NPCQUESTBOSSKARATE.NpcTalk.ClickDetector)
                                        end
wait(7)
                                        
    local player = game.Players.LocalPlayer
    local character = player.Character or player.CharacterAdded:Wait()
    local Humanoid = character:FindFirstChildOfClass("Humanoid")
    local HumanoidRootPart = character:FindFirstChild("HumanoidRootPart")

    local pasta = workspace:WaitForChild("Npcs")
    local npc = pasta:WaitForChild("Karate_Boss")
        local humanoidRootPart = npc:FindFirstChild("HumanoidRootPart")
        local humanoid = npc:FindFirstChildOfClass("Humanoid")

        if humanoidRootPart and humanoid and inf then
            wait(0.5)
            
            local npcPosition = humanoidRootPart.Position
            print(npcPosition) 

            
            local direction = (HumanoidRootPart.Position - npcPosition).Unit
            local newPosition = npcPosition + direction * 3 

            
            HumanoidRootPart.CFrame = CFrame.lookAt(newPosition, npcPosition)

            wait(0.4)
if inf then
local player = game.Players.LocalPlayer
local backpack = player:WaitForChild("Backpack")
local character = player.Character or player.CharacterAdded:Wait()

local function equipCombat()
    local tool = backpack:FindFirstChild("Combat")
    if tool then
        character.Humanoid:EquipTool(tool)
    else
        print("Item 'Combat' não encontrado na mochila.")
    end
end

equipCombat()
end
humanoid.Health = humanoid.Health - 1
if inf then
for i = 1, 8 do 
            humanoid.Health = 0 
wait(0.1)
end
end
            wait(0.3)
humanoid.Health = 0
                  if inf then
            local args = {
                [1] = game:GetService("Players").LocalPlayer
            }

            game:GetService("ReplicatedStorage").Events.boxing:FireServer(unpack(args))
                  end
            wait(0.6)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()

local function unequipCombat()
    local tool = character:FindFirstChild("Combat")
    if tool then
        tool.Parent = player:WaitForChild("Backpack")
    else
        print("Item 'Combat' não está equipado.")
    end
end

unequipCombat()

            
            humanoid.Health = 100
            humanoid.Health = 900
Humanoid.Health = Humanoid.Health +1
        end
                              end
                    end
          end
          
end)


local anf = false
tab.newToggle("auto sensei kong fu", "Kong fu sensei", false, function(valo)
  anf = valo
  
    if anf then
      while anf do
        if anf then
            
                  
                wait()
                  if anf then
                  local player = game.Players.LocalPlayer
local char = player.Character
char.HumanoidRootPart.CFrame = CFrame.new(-580, 23, -1164)
                  end
wait(5)
                  if anf then
fireclickdetector(workspace.Interactive.NPCQUESTBOSSKUNGFU.NpcTalk.ClickDetector)
                  end
wait(7)
            

    local player = game.Players.LocalPlayer
    local character = player.Character or player.CharacterAdded:Wait()
    local Humanoid = character:FindFirstChildOfClass("Humanoid")
    local HumanoidRootPart = character:FindFirstChild("HumanoidRootPart")

    local pasta = workspace:WaitForChild("Npcs")
    local npc = pasta:WaitForChild("KungFu_Boss")
        local humanoidRootPart = npc:FindFirstChild("HumanoidRootPart")
        local humanoid = npc:FindFirstChildOfClass("Humanoid")

        if humanoidRootPart and humanoid and anf then
            wait(0.5)
            
            local npcPosition = humanoidRootPart.Position
            print(npcPosition) 

            
            local direction = (HumanoidRootPart.Position - npcPosition).Unit 
            local newPosition = npcPosition + direction * 3 
            
          
            HumanoidRootPart.CFrame = CFrame.lookAt(newPosition, npcPosition)
            
            wait(0.4)
if anf then
local player = game.Players.LocalPlayer
local backpack = player:WaitForChild("Backpack")
local character = player.Character or player.CharacterAdded:Wait()
local function equipCombat()
    local tool = backpack:FindFirstChild("Combat")
    if tool then
        character.Humanoid:EquipTool(tool)
    else
        print("Item 'Combat' não encontrado na mochila.")
    end
end

equipCombat()
end
                  if anf then
humanoid.Health = humanoid.Health -1
for i = 1, 8 do
            humanoid.Health = 0
end
                  end
            wait(0.2)
humanoid.Health = 0
wait(0.3)
                  if anf then
            local args = {
                [1] = game:GetService("Players").LocalPlayer
            }

            game:GetService("ReplicatedStorage").Events.boxing:FireServer(unpack(args))

            wait(0.6)
                  end
local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()

local function unequipCombat()
    local tool = character:FindFirstChild("Combat")
    if tool then
        tool.Parent = player:WaitForChild("Backpack")
    else
        print("Item 'Combat' não está equipado.")
    end
end

unequipCombat()

            
            humanoid.Health = 100
            humanoid.Health = 900
Humanoid.Health = Humanoid.Health +1
        end
        end
      end
    end
end)

local sp = false
tab.newToggle("alto farm supremo", "Matar todos npcs principais( xp não para de cair) ", false, function(valor)
  sp = valor
  
    if sp then
      while sp do
        if sp then
            
                wait()
            if sp then    
                
wait()
if sp then
 local player = game.Players.LocalPlayer
local char = player.Character
char.HumanoidRootPart.CFrame = CFrame.new(-802, 26, -2000)
end
                      if sp then
wait(5)
fireclickdetector(workspace.Interactive.NPCQUESTBOSSKARATE.NpcTalk.ClickDetector)
                      end
wait(7)



    local player = game.Players.LocalPlayer
    local character = player.Character or player.CharacterAdded:Wait()
    local Humanoid = character:FindFirstChildOfClass("Humanoid")
    local HumanoidRootPart = character:FindFirstChild("HumanoidRootPart")

    local pasta = workspace:WaitForChild("Npcs")
    local npc = pasta:WaitForChild("Karate_Boss")
        local humanoidRootPart = npc:FindFirstChild("HumanoidRootPart")
        local humanoid = npc:FindFirstChildOfClass("Humanoid")

        if humanoidRootPart and humanoid and sp  then
            wait(0.5)
            
            local npcPosition = humanoidRootPart.Position
            print(npcPosition) 

            
            local direction = (HumanoidRootPart.Position - npcPosition).Unit 
            local newPosition = npcPosition + direction * 3 
            
            
            HumanoidRootPart.CFrame = CFrame.lookAt(newPosition, npcPosition)

            wait(0.4)
if sp then
local player = game.Players.LocalPlayer
local backpack = player:WaitForChild("Backpack")
local character = player.Character or player.CharacterAdded:Wait()

local function equipCombat()
    local tool = backpack:FindFirstChild("Combat")
    if tool then
        character.Humanoid:EquipTool(tool)
    else
        print("Item 'Combat' não encontrado na mochila.")
    end
end

equipCombat()
end
                  if sp then
humanoid.Health = humanoid.Health - 1

for i = 1, 8 do 
            humanoid.Health = 0 
wait(0.1)
end
                  end
                  
            wait(0.3)
humanoid.Health = 0
                  if sp then
            local args = {
                [1] = game:GetService("Players").LocalPlayer
            }

            game:GetService("ReplicatedStorage").Events.boxing:FireServer(unpack(args))
                  end
            wait(0.6)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()

local function unequipCombat()
    local tool = character:FindFirstChild("Combat")
    if tool then
        tool.Parent = player:WaitForChild("Backpack")
    else
        print("Item 'Combat' não está equipado.")
    end
end

unequipCombat()

            
            humanoid.Health = 100
            humanoid.Health = 900
Humanoid.Health = Humanoid.Health +1
if sp then
       local player = game.Players.LocalPlayer
local char = player.Character
char.HumanoidRootPart.CFrame = CFrame.new(-580, 23, -1164)
end
wait(5)
                  if sp then
fireclickdetector(workspace.Interactive.NPCQUESTBOSSKUNGFU.NpcTalk.ClickDetector)
wait(7)
                  end
            

    local player = game.Players.LocalPlayer
    local character = player.Character or player.CharacterAdded:Wait()
    local Humanoid = character:FindFirstChildOfClass("Humanoid")
    local HumanoidRootPart = character:FindFirstChild("HumanoidRootPart")

    local pasta = workspace:WaitForChild("Npcs")
    local npc = pasta:WaitForChild("KungFu_Boss")
        local humanoidRootPart = npc:FindFirstChild("HumanoidRootPart")
        local humanoid = npc:FindFirstChildOfClass("Humanoid")

        if humanoidRootPart and humanoid and sp then
            wait(0.5)
            
            local npcPosition = humanoidRootPart.Position
            print(npcPosition) 

            
            local direction = (HumanoidRootPart.Position - npcPosition).Unit
            local newPosition = npcPosition + direction * 3 

            
            HumanoidRootPart.CFrame = CFrame.lookAt(newPosition, npcPosition)

            wait(0.4)
if sp then
local player = game.Players.LocalPlayer
local backpack = player:WaitForChild("Backpack")
local character = player.Character or player.CharacterAdded:Wait()

local function equipCombat()
    local tool = backpack:FindFirstChild("Combat")
    if tool then
        character.Humanoid:EquipTool(tool)
    else
        print("Item 'Combat' não encontrado na mochila.")
    end
end

equipCombat()
end
                  if sp then
humanoid.Health = humanoid.Health -1
for i = 1, 8 do
            humanoid.Health = 0
end
            wait(0.2)
humanoid.Health = 0
wait(0.3)
                  end
                  if sp then
            local args = {
                [1] = game:GetService("Players").LocalPlayer
            }

            game:GetService("ReplicatedStorage").Events.boxing:FireServer(unpack(args))
                  end
            wait(0.6)

local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()

local function unequipCombat()
    local tool = character:FindFirstChild("Combat")
    if tool then
        tool.Parent = player:WaitForChild("Backpack")
    else
        print("Item 'Combat' não está equipado.")
    end
end

unequipCombat()

            
            humanoid.Health = 100
            humanoid.Health = 900
Humanoid.Health = Humanoid.Health +1
for i = 1, 6  do
    wait()
if sp then
    local player = game.Players.LocalPlayer
    local char = player.Character

    char.HumanoidRootPart.CFrame = CFrame.new(-1067, 12, -1307)
end
    wait(5)
if sp then
    fireclickdetector(workspace.Interactive.NPCQUEST.NpcTalk.ClickDetector)
    wait(7)
end
    local player = game.Players.LocalPlayer
    local character = player.Character or player.CharacterAdded:Wait()
    local Humanoid = character:FindFirstChildOfClass("Humanoid")
    local HumanoidRootPart = character:FindFirstChild("HumanoidRootPart")

    local pasta = workspace:WaitForChild("Npcs")
    local subpasta = pasta:WaitForChild("Fighters3")
    for _, npc in pairs(subpasta:GetChildren()) do
        local humanoidRootPart = npc:FindFirstChild("HumanoidRootPart")
        local humanoid = npc:FindFirstChildOfClass("Humanoid")

        if humanoidRootPart and humanoid and sp then
            wait(0.5)
            local npcPosition = humanoidRootPart.Position
            print(npcPosition) 

            
            local direction = (HumanoidRootPart.Position - npcPosition).Unit 
            local newPosition = npcPosition + direction * 3 

            
            HumanoidRootPart.CFrame = CFrame.lookAt(newPosition, npcPosition)

            wait(0.2)

            
            if sp then
local player = game.Players.LocalPlayer
local backpack = player:WaitForChild("Backpack")
local character = player.Character or player.CharacterAdded:Wait()

local function equipCombat()
    local tool = backpack:FindFirstChild("Combat")
    if tool then
        character.Humanoid:EquipTool(tool)
    else
        print("Item 'Combat' não encontrado na mochila.")
    end
end
            
equipCombat()
            
            end          

humanoid.Health = humanoid.Health -1
      wait(0.2)
            humanoid.Health = 0 
            
local function checarnpc()
while true do 
wait(0.1)
local pasta = workspace:WaitForChild("Npcs")
    local subpasta = pasta:WaitForChild("Fighters3")
    for _, npc in pairs(subpasta:GetChildren()) do
        local humanoidRootPart = npc:FindFirstChild("HumanoidRootPart")
        local humanoid = npc:FindFirstChildOfClass("Humanoid")

    
        
    if  not humanoid or not humanoidRootPart then
        wait(0.4)
        
        print("sem npcs")
              end
         end
     end
end
            
            coroutine.wrap(checarnpc)()
            wait(0.5)
                  if sp then
            local args = {
                [1] = game:GetService("Players").LocalPlayer
            }

            game:GetService("ReplicatedStorage").Events.boxing:FireServer(unpack(args))
                  end
            wait(0.5)
            
            
local player = game.Players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()

local function unequipCombat()
    local tool = character:FindFirstChild("Combat")
    if tool then
        tool.Parent = player:WaitForChild("Backpack")
    else
        print("Item 'Combat' não está equipado.")
    end
end

unequipCombat()

            
            humanoid.Health = 100
            humanoid.Health = 900
Humanoid.Health = Humanoid.Health + 1
end
        end
    end
end
        end






     
                
                
                
            end
        end
end
end
    end)



    local tab = DrRayLibrary.newTab("Teleport", "ImageIdHere")
    
tab.newButton("Ir para toman", "te teleporta na HQ da toman", function()
   

--- ir para hq toman 

local plr = game.Players.LocalPlayer
local chr = plr.Character 
chr.HumanoidRootPart.CFrame = CFrame.new(-323, 9, 27) 
end)

tab.newButton("ir para spawn", "rodar a sacola no spawn", function()
    

--- ir para spawn

local plr = game.Players.LocalPlayer
local chr = plr.Character 
chr.HumanoidRootPart.CFrame = CFrame.new(-985, 9, -563)
end)

tab.newButton("ir para academia", "Te teleporta na academia", function()
    

--- ir para academia

local plr = game.Players.LocalPlayer
local chr = plr.Character 
chr.HumanoidRootPart.CFrame = CFrame.new(-917, 9, -700)
end)



tab.newButton("ir para mercado", "te teleporta no mercadinho de alimentos", function()
    

--- ir para mercadinho de comida

local plr = game.Players.LocalPlayer
local chr = plr.Character 
chr.HumanoidRootPart.CFrame = CFrame.new(-574, 9, -517)
end)


tab.newButton("ir para store equipamentos", "te teleporta no store equipamentos de treino", function()
    

--- ir para store de equipamentos de treino

local plr = game.Players.LocalPlayer
local chr = plr.Character 
chr.HumanoidRootPart.CFrame = CFrame.new(-383, 9, -660)
end)



tab.newButton("ir para kong fu sensei", "te teleporte na área do kong fu sensei", function()
    

--- ir para kong fu sensei

local plr = game.Players.LocalPlayer
local chr = plr.Character 
chr.HumanoidRootPart.CFrame = CFrame.new(-585, 23, -1163)
end)



tab.newButton("ir para sensei karatê", "te teleporta na área do sensei karatê", function()
    

--- ir para sensei karatê 

local plr = game.Players.LocalPlayer
local chr = plr.Character 
chr.HumanoidRootPart.CFrame = CFrame.new(-891, 24, -2007)
end)

tab.newButton("ir para dojo", "te teleporta no dojo", function()
    

--- ir para dojo

local plr = game.Players.LocalPlayer
local chr = plr.Character 
chr.HumanoidRootPart.CFrame = CFrame.new(-1048, 10, -1194)
end)

local tab = DrRayLibrary.newTab("PVP", "ImageIdHere")

tab.newButton("ativa spawn kill", "fazer spawn kill em outros jogadores ( assista o tutorial para aprender a usar) ", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/lucaszedamanga/Fighting-academy-spawn-kill/main/README.md"))()
end)

tab.newButton("god mod", "deixa você imortal", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/zephyr10101/ignore-touchinterests/main/main",true))()
end)


local tab = DrRayLibrary.newTab("Outros", "ImageIdHere")




tab.newButton("Infinite yield", "carrega comandos de administração", function()
    loadstring(game:HttpGet(('https://pastebin.com/raw/yRHbQADj'),true))()
end)

tab.newButton("anti ban", "Remove seu historico de mensagens do chat", function()
    --[[
    WARNING: Heads up! This script has not been verified by ScriptBlox. Use at your own risk!
]]
loadstring(game:HttpGet("https://raw.githubusercontent.com/AnthonyIsntHere/anthonysrepository/main/scripts/AntiChatLogger.lua", true))()
end)

tab.newButton("ghost hub", "carrega o menu fantasma 👻", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/GhostPlayer352/Test4/main/GhostHub'))()
end)


window:Open()
