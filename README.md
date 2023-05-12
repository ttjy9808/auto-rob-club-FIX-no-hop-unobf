localplayer = game.Players.LocalPlayer
 Char = localplayer.Character or workspace:FindFirstChild(localplayer.Name)
         HRP = Char and Char:FindFirstChild("HumanoidRootPart")
        if not Char or not HRP then
           
        end
         p = HRP.Position
         hrd = game.Players.LocalPlayer.Character.HumanoidRootPart
     x = 1691.64
     y = 73.82
     z = -1229.9
        hrd.CFrame = CFrame.new(p.x, 1000, p.z)
        wait(0.5)
         currentPos = Vector3.new(p.x, 1000, p.z)
         targetPos = Vector3.new(x, 1000, z)

         direction = (targetPos - currentPos).Unit
         distance = (targetPos - currentPos).Magnitude
         steps = math.floor(distance / 5) 
        for i = 1, steps do
            currentPos = currentPos + direction * 5
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end

        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait(0.1)
         p = hrd.Position
        
         currentPos = Vector3.new(x, 1000, z)
         targetPos = Vector3.new(x, y, z)

         direction = (targetPos - currentPos).Unit
         distance = (targetPos - currentPos).Magnitude
         steps = math.floor(distance / 5) 
        for i = 1, steps do
            currentPos = currentPos + direction * 5 
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end
        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait(0.5)
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1691.64,270,-1229.9)
        task.wait(0.5)
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1764.43,229.17,-1224.63)
        task.wait(0.8)
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1807.7,225.41,-1183.49)
        task.wait(0.5)
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1807.7,192.71,-1183.49)
        task.wait(0.5)
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1819.84,192.71,-1164.03)
        task.wait(0.5)
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1819.84,225.51,-1164.03)
        task.wait(0.1)
        local GamePassId = 5275408

local player = game.Players.LocalPlayer
local MarketplaceService = game:GetService("MarketplaceService")

local function checkGamePass()
    local hasGamePass = MarketplaceService:UserOwnsGamePassAsync(player.UserId, GamePassId)

    if hasGamePass then
        task.wait(50)
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1819.84,192.71,-1164.03)
        task.wait(0.5)
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1807.7,192.71,-1183.49)
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1807.7,225.41,-1183.49)
        task.wait(0.5)
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1764.43,229.17,-1224.63)
        task.wait(0.8)
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1691.64,270,-1229.9)
        task.wait(0.1)
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1691.64,73.82,-1229.9)
        local part = Instance.new("Part")
part.Name = "floorairport"
part.CanCollide = true
part.Anchored = true
part.Color = Color3.new(1, 1, 1)
part.Parent = workspace 
part.Position = Vector3.new(57.01,35,-152.27)
        localplayer = game.Players.LocalPlayer
 Char = localplayer.Character or workspace:FindFirstChild(localplayer.Name)
         HRP = Char and Char:FindFirstChild("HumanoidRootPart")
        if not Char or not HRP then
           
        end
         p = HRP.Position
         hrd = game.Players.LocalPlayer.Character.HumanoidRootPart
     x = 57.01
     y = 25.34
     z = -152.27
        hrd.CFrame = CFrame.new(p.x, 1000, p.z)
        wait(0.5)
         currentPos = Vector3.new(p.x, 1000, p.z)
         targetPos = Vector3.new(x, 1000, z)

         direction = (targetPos - currentPos).Unit
         distance = (targetPos - currentPos).Magnitude
         steps = math.floor(distance / 5) 
        for i = 1, steps do
            currentPos = currentPos + direction * 5
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end

        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait(0.1)
         p = hrd.Position
        
         currentPos = Vector3.new(x, 1000, z)
         targetPos = Vector3.new(x, y, z)

         direction = (targetPos - currentPos).Unit
         distance = (targetPos - currentPos).Magnitude
         steps = math.floor(distance / 5) 
        for i = 1, steps do
            currentPos = currentPos + direction * 5 
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end
        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait(1)
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(123.58,26.57,-178.41)
    else
        task.wait(25)
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1819.84,192.71,-1164.03)
        task.wait(0.5)
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1807.7,192.71,-1183.49)
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1807.7,225.41,-1183.49)
        task.wait(0.5)
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1764.43,229.17,-1224.63)
        task.wait(0.8)
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1691.64,270,-1229.9)
        task.wait(0.1)
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1691.64,73.82,-1229.9)
        local part = Instance.new("Part")
part.Name = "floorairport"
part.CanCollide = true
part.Anchored = true
part.Color = Color3.new(1, 1, 1)
part.Parent = workspace 
part.Position = Vector3.new(57.01,35,-152.27)
        localplayer = game.Players.LocalPlayer
 Char = localplayer.Character or workspace:FindFirstChild(localplayer.Name)
         HRP = Char and Char:FindFirstChild("HumanoidRootPart")
        if not Char or not HRP then
           
        end
         p = HRP.Position
         hrd = game.Players.LocalPlayer.Character.HumanoidRootPart
     x = 57.01
     y = 25.34
     z = -152.27
        hrd.CFrame = CFrame.new(p.x, 1000, p.z)
        wait(0.5)
         currentPos = Vector3.new(p.x, 1000, p.z)
         targetPos = Vector3.new(x, 1000, z)

         direction = (targetPos - currentPos).Unit
         distance = (targetPos - currentPos).Magnitude
         steps = math.floor(distance / 5) 
        for i = 1, steps do
            currentPos = currentPos + direction * 5
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end

        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait(0.1)
         p = hrd.Position
        
         currentPos = Vector3.new(x, 1000, z)
         targetPos = Vector3.new(x, y, z)

         direction = (targetPos - currentPos).Unit
         distance = (targetPos - currentPos).Magnitude
         steps = math.floor(distance / 5) 
        for i = 1, steps do
            currentPos = currentPos + direction * 5 
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
            task.wait()
        end
        
        currentPos = targetPos
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(currentPos)
        task.wait(1)
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(123.58,26.57,-178.41)
    end
end
checkGamePass()   
