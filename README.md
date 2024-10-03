local player = game.Players.LocalPlayer
    local char = player.Character

    char.HumanoidRootPart.CFrame = CFrame.new(-1067, 12, -1307)
    wait(5)

    fireclickdetector(workspace.Interactive.NPCQUEST.NpcTalk.ClickDetector)
    wait(7)

    local player = game.Players.LocalPlayer
    local character = player.Character or player.CharacterAdded:Wait()
    local Humanoid = character:FindFirstChildOfClass("Humanoid")
    local HumanoidRootPart = character:FindFirstChild("HumanoidRootPart")

    local pasta = workspace:WaitForChild("Npcs")
    local subpasta = pasta:WaitForChild("Fighters3")
    for _, npc in pairs(subpasta:GetChildren()) do
        local humanoidRootPart = npc:FindFirstChild("HumanoidRootPart")
        local humanoid = npc:FindFirstChildOfClass("Humanoid")

        if humanoidRootPart and humanoid then
            wait(0.5)
            -- Armazena a posição atual do NPC em uma variável
            local npcPosition = humanoidRootPart.Position
            print(npcPosition) -- Exibe a posição do NPC

            -- Calcula a posição um stud atrás do NPC
            local direction = (HumanoidRootPart.Position - npcPosition).Unit -- Calcula a direção oposta ao NPC
            local newPosition = npcPosition + direction * 3 -- Define a nova posição a um stud atrás do NPC

            -- Teleporta o personagem para a nova posição e faz ele olhar para o NPC
            HumanoidRootPart.CFrame = CFrame.lookAt(newPosition, npcPosition)

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
            local args = {
                [1] = game:GetService("Players").LocalPlayer
            }

            game:GetService("ReplicatedStorage").Events.boxing:FireServer(unpack(args))

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

            -- Restaura a vida do NPC, se necessário
            humanoid.Health = 100
            humanoid.Health = 900
Humanoid.Health = Humanoid.Health +1
end
        end
    
