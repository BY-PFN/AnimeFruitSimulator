task.wait(7)
repeat  task.wait() until game:IsLoaded()
local vu = game:GetService("VirtualUser")
game:GetService("Players").LocalPlayer.Idled:connect(function()
   vu:Button2Down(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
   wait(1)
   vu:Button2Up(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
end)
if game.PlaceId == 10446125875 then -- [NEW MOCHI FRUIT] Anime Fruit Simulator
 

local DiscordLib = loadstring(game:HttpGet("https://pastebin.com/raw/xcdmdnw0"))()
local win = DiscordLib:Window("[NEW MOCHI FRUIT] Anime Fruit Simulator")

local serv = win:Server("PNonShopByPFN", "")



local tgls = serv:Channel("AutoFarm")
local tgls1 = serv:Channel("Egg")
local tgls2 = serv:Channel("BOSS")
local tgls3 = serv:Channel("TP")
-----------------------------------------------------------------------------
_G.Click = true
tgls:Toggle("ClickAFK",true, function(bool)
   _G.Click = bool
end)
local ViSendMouseButtonEvent = game:service'VirtualInputManager'

spawn(function()
    while wait() do
      if _G.Click then
        pcall(function()
            ViSendMouseButtonEvent:SendMouseButtonEvent(795, 595, 0, true, game, 1)
wait(10)
ViSendMouseButtonEvent:SendMouseButtonEvent(795, 595, 0, false, game, 1)    
            
        end)
      end
    end
end)

_G.Attack = true
tgls:Toggle("Attack",true, function(bool)
  _G.Attack = bool
end)
spawn(function()
  while wait(0.5) do
    if _G.Attack then
      pcall(function() 
         
game:GetService("ReplicatedStorage").Remotes.Attack:FireServer()
         
      end)
    end
  end
end)

_G.One = true
tgls:Toggle("One",true, function(bool)
  _G.One = bool
end)
spawn(function()
  while wait(0.5) do
    if _G.One then
      pcall(function() 
          


local args = {
   [1] = "One"
}

game:GetService("ReplicatedStorage").Remotes.Validate:FireServer(unpack(args))

        

           
          
      end)
    end
  end
end)

_G.Two = true
tgls:Toggle("Two",true, function(bool)
  _G.Two = bool
end)
spawn(function()
  while wait(0.5) do
    if _G.Two then
      pcall(function() 
          
local args = {
   [1] = "Two"
}

game:GetService("ReplicatedStorage").Remotes.Validate:FireServer(unpack(args))
       
          
      end)
    end
  end
end)

_G.Three = true
tgls:Toggle("Three",true, function(bool)
  _G.Three = bool
end)
spawn(function()
  while wait(0.5) do
    if _G.Three then
      pcall(function() 
          

local args = {
   [1] = "Three"
}

game:GetService("ReplicatedStorage").Remotes.Validate:FireServer(unpack(args))

       
          
      end)
    end
  end
end)


_G.UnlockZone = true
tgls:Toggle("UnlockZone",true, function(bool)
  _G.UnlockZone = bool
end)
spawn(function()
  while wait(0.5) do
    if _G.UnlockZone then
      pcall(function() 
          

        local args = {
          [1] = 1,
          [2] = workspace.ZoneEntrances:FindFirstChild("1")
        }
        
        game:GetService("ReplicatedStorage").Remotes.UnlockZone:FireServer(unpack(args))
        local args = {
          [1] = 2,
          [2] = workspace.ZoneEntrances:FindFirstChild("2")
        }
        
        game:GetService("ReplicatedStorage").Remotes.UnlockZone:FireServer(unpack(args))
        local args = {
          [1] = 3,
          [2] = workspace.ZoneEntrances:FindFirstChild("3")
        }
        
        game:GetService("ReplicatedStorage").Remotes.UnlockZone:FireServer(unpack(args))
       
        local args = {
          [1] = 4,
          [2] = workspace.ZoneEntrances:FindFirstChild("4")
        }
        
        game:GetService("ReplicatedStorage").Remotes.UnlockZone:FireServer(unpack(args))


        local args = {
          [1] = 5,
          [2] = workspace.ZoneEntrances:FindFirstChild("5")
        }
        
        game:GetService("ReplicatedStorage").Remotes.UnlockZone:FireServer(unpack(args))

        local args = {
          [1] = 6,
          [2] = workspace.ZoneEntrances:FindFirstChild("6")
        }
        
        game:GetService("ReplicatedStorage").Remotes.UnlockZone:FireServer(unpack(args))

        local args = {
          [1] = 7,
          [2] = workspace.ZoneEntrances:FindFirstChild("7")
        }
        
        game:GetService("ReplicatedStorage").Remotes.UnlockZone:FireServer(unpack(args))

        local args = {
          [1] = 8,
          [2] = workspace.ZoneEntrances:FindFirstChild("8")
        }
        
        game:GetService("ReplicatedStorage").Remotes.UnlockZone:FireServer(unpack(args))

        local args = {
          [1] = 9,
          [2] = workspace.ZoneEntrances:FindFirstChild("9")
        }
        
        game:GetService("ReplicatedStorage").Remotes.UnlockZone:FireServer(unpack(args))

        local args = {
          [1] = 10,
          [2] = workspace.ZoneEntrances:FindFirstChild("10")
        }
        
        game:GetService("ReplicatedStorage").Remotes.UnlockZone:FireServer(unpack(args))

        local args = {
          [1] = 11,
          [2] = workspace.ZoneEntrances:FindFirstChild("11")
        }
        
        game:GetService("ReplicatedStorage").Remotes.UnlockZone:FireServer(unpack(args))

        local args = {
          [1] = 11,
          [2] = workspace.ZoneEntrances:FindFirstChild("11")
        }
        
        game:GetService("ReplicatedStorage").Remotes.UnlockZone:FireServer(unpack(args))

        local args = {
          [1] = 12,
          [2] = workspace.ZoneEntrances:FindFirstChild("11")
        }
        
        game:GetService("ReplicatedStorage").Remotes.UnlockZone:FireServer(unpack(args))

        local args = {
          [1] = 13,
          [2] = workspace.ZoneEntrances:FindFirstChild("11")
        }
        
        game:GetService("ReplicatedStorage").Remotes.UnlockZone:FireServer(unpack(args))

        local args = {
          [1] = 14,
          [2] = workspace.ZoneEntrances:FindFirstChild("11")
        }
        
        game:GetService("ReplicatedStorage").Remotes.UnlockZone:FireServer(unpack(args))

        local args = {
          [1] = 15,
          [2] = workspace.ZoneEntrances:FindFirstChild("11")
        }
        
        game:GetService("ReplicatedStorage").Remotes.UnlockZone:FireServer(unpack(args))

        local args = {
          [1] = 16,
          [2] = workspace.ZoneEntrances:FindFirstChild("11")
        }
        
        game:GetService("ReplicatedStorage").Remotes.UnlockZone:FireServer(unpack(args))

      end)
    end
  end
end)

local args = {
  [1] = 5,
  [2] = workspace.ZoneEntrances:FindFirstChild("5")
}

game:GetService("ReplicatedStorage").Remotes.UnlockZone:FireServer(unpack(args))


-----

_G.FruitEgg = false
tgls1:Toggle("FruitEgg",false, function(bool)
  _G.FruitEgg = bool
end)
spawn(function()
  while wait(0.5) do
    if _G.FruitEgg then
      pcall(function() 
          

local args = {
   [1] = "FruitEgg",
   [2] = "HatchBtn"
}

game:GetService("ReplicatedStorage").Remotes.Egg:FireServer(unpack(args))


       
          
      end)
    end
  end
end)

tgls1:Seperator()

_G.EggZONE12 = false
tgls1:Toggle("EggZONE12",false, function(bool)
  _G.EggZONE12 = bool
end)
spawn(function()
  while wait(0.5) do
    if _G.EggZONE12 then
      pcall(function() 
          

local args = {
  [1] = "CrystalEgg",
  [2] = "HatchBtn"
}

game:GetService("ReplicatedStorage").Remotes.Egg:FireServer(unpack(args))






       
          
      end)
    end
  end
end)


tgls1:Seperator()

_G.EggZONE13 = false
tgls1:Toggle("EggZONE13",false, function(bool)
  _G.EggZONE13 = bool
end)
spawn(function()
  while wait(0.5) do
    if _G.EggZONE13 then
      pcall(function() 
          

local args = {
  [1] = "AncientEgg",
  [2] = "HatchBtn"
}

game:GetService("ReplicatedStorage").Remotes.Egg:FireServer(unpack(args))





       
          
      end)
    end
  end
end)

tgls1:Seperator()

_G.EggZONE14 = false
tgls1:Toggle("EggZONE14",false, function(bool)
  _G.EggZONE14 = bool
end)
spawn(function()
  while wait(0.5) do
    if _G.EggZONE14 then
      pcall(function() 
          


local args = {
  [1] = "MushroomEgg",
  [2] = "HatchBtn"
}

game:GetService("ReplicatedStorage").Remotes.Egg:FireServer(unpack(args))




       
          
      end)
    end
  end
end)

tgls:Seperator()

_G.EggZONE15 = false
tgls1:Toggle("EggZONE15",false, function(bool)
  _G.EggZONE15 = bool
end)
spawn(function()
  while wait(0.5) do
    if _G.EggZONE15 then
      pcall(function() 
          


local args = {
  [1] = "VolcanoEgg",
  [2] = "HatchBtn"
}

game:GetService("ReplicatedStorage").Remotes.Egg:FireServer(unpack(args))



       
          
      end)
    end
  end
end)



tgls1:Seperator()


_G.EggZONE16 = true
tgls1:Toggle("EggZONE16",true, function(bool)
  _G.EggZONE16 = bool
end)
spawn(function()
  while wait(0.5) do
    if _G.EggZONE16 then
      pcall(function() 
          


        local args = {
          [1] = "MetalicEgg",
          [2] = "HatchBtn"
        }
        
        game:GetService("ReplicatedStorage").Remotes.Egg:FireServer(unpack(args))



       
          
      end)
    end
  end
end)

-----------------------------------------------------------------------------
_G.BOSS1 = false
tgls2:Toggle("BOSS1 ",false, function(bool)
  _G.BOSS1 = bool
end)
    
spawn(function()
  while wait(5) do
    if _G.BOSS1 then
      pcall(function() 
          

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-235.81590270996094, 14.008026123046875, -143.8977508544922)
if (CFrame.new(-235.81590270996094, 14.008026123046875, -143.8977508544922).Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position) >= 5 then
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-235.81590270996094, 14.008026123046875, -143.8977508544922)
end


          wait(10)
          
          
      end)
    end
  end
end) 

_G.BOSS2 = false
tgls2:Toggle("BOSS2 ",false, function(bool)
  _G.BOSS2 = bool
end)
    
spawn(function()
  while wait(5) do
    if _G.BOSS2 then
      pcall(function() 
          

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-426.2984924316406, 13.998026847839355, -139.5566864013672)
if (CFrame.new(-426.2984924316406, 13.998026847839355, -139.5566864013672).Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position) >= 5 then
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-426.2984924316406, 13.998026847839355, -139.5566864013672)
end


          wait(10)
          
          
      end)
    end
  end
end) 

_G.BOSS3 = false
tgls2:Toggle("BOSS3 ",false, function(bool)
  _G.BOSS3 = bool
end)
    
spawn(function()
  while wait(5) do
    if _G.BOSS3 then
      pcall(function() 
          

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-591.2839965820312, 14.003022193908691, -42.912593841552734)
if (CFrame.new(-591.2839965820312, 14.003022193908691, -42.912593841552734).Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position) >= 5 then
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-591.2839965820312, 14.003022193908691, -42.912593841552734)
end


          wait(10)
          
          
      end)
    end
  end
end) 

_G.BOSS4 = false
tgls2:Toggle("BOSS4 ",false, function(bool)
  _G.BOSS4 = bool
end)
    
spawn(function()
  while wait(5) do
    if _G.BOSS4 then
      pcall(function() 
          

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-742.4168701171875, 13.99802303314209, -141.8807373046875)
if (CFrame.new(-742.4168701171875, 13.99802303314209, -141.8807373046875).Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position) >= 5 then
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-742.4168701171875, 13.99802303314209, -141.8807373046875)
end


          wait(10)
          
          
      end)
    end
  end
end) 

_G.BOSS5 = false
tgls2:Toggle("BOSS5 ",false, function(bool)
  _G.BOSS5 = bool
end)
    
spawn(function()
  while wait(5) do
    if _G.BOSS5 then
      pcall(function() 
          

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2068.556884765625, 13.99802303314209, -139.2130584716797)
if (CFrame.new(-2068.556884765625, 13.99802303314209, -139.2130584716797).Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position) >= 5 then
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2068.556884765625, 13.99802303314209, -139.2130584716797)
end


          wait(10)
          
          
      end)
    end
  end
end) 

_G.BOSS6 = false
tgls2:Toggle("BOSS6 ",false, function(bool)
  _G.BOSS6 = bool
end)
    
spawn(function()
  while wait(5) do
    if _G.BOSS6 then
      pcall(function() 
          

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2275.870361328125, 13.998022079467773, -134.99856567382812)
if (CFrame.new(-2275.870361328125, 13.998022079467773, -134.99856567382812).Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position) >= 5 then
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2275.870361328125, 13.998022079467773, -134.99856567382812)
end


          wait(10)
          
          
      end)
    end
  end
end) 

_G.BOSS7 = false
tgls2:Toggle("BOSS7 ",false, function(bool)
  _G.BOSS7 = bool
end)
    
spawn(function()
  while wait(5) do
    if _G.BOSS7 then
      pcall(function() 
          

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2488.9755859375, 14.008024215698242, -205.35731506347656)
if (CFrame.new(-2488.9755859375, 14.008024215698242, -205.35731506347656).Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position) >= 5 then
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2488.9755859375, 14.008024215698242, -205.35731506347656)
end


          wait(10)
          
          
      end)
    end
  end
end) 


_G.BOSS8 = false
tgls2:Toggle("BOSS8 ",false, function(bool)
  _G.BOSS8 = bool
end)
    
spawn(function()
  while wait(5) do
    if _G.BOSS8 then
      pcall(function() 
          

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2714.853515625, 14.357771873474121, -134.6840057373047)
if (CFrame.new(-2714.853515625, 14.357771873474121, -134.6840057373047).Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position) >= 5 then
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2714.853515625, 14.357771873474121, -134.6840057373047)
end


          wait(10)
          
          
      end)
    end
  end
end) 

_G.BOSS9 = false
tgls2:Toggle("BOSS9 ",false, function(bool)
  _G.BOSS9 = bool
end)
    
spawn(function()
  while wait(5) do
    if _G.BOSS9 then
      pcall(function() 
          

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2882.8603515625, 13.998023986816406, -123.23009490966797)
if (CFrame.new(-2882.8603515625, 13.998023986816406, -123.23009490966797).Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position) >= 5 then
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2882.8603515625, 13.998023986816406, -123.23009490966797)
end


          wait(10)
          
          
      end)
    end
  end
end) 

_G.BOSS10 = false
tgls2:Toggle("BOSS10 ",false, function(bool)
  _G.BOSS10 = bool
end)
    
spawn(function()
  while wait(5) do
    if _G.BOSS10 then
      pcall(function() 
          

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-3096.33740234375, 13.99802303314209, -139.51014709472656)
if (CFrame.new(-3096.33740234375, 13.99802303314209, -139.51014709472656).Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position) >= 5 then
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-3096.33740234375, 13.99802303314209, -139.51014709472656)
end


          wait(10)
          
          
      end)
    end
  end
end) 




----

tgls2:Button("ZONE11", function()
    
  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-3391.25927734375, 23.2437744140625, -137.75489807128906)    
      
  
end)

tgls2:Seperator()

_G.PoneglyphBOSS12 = false
tgls2:Toggle("PoneglyphBOSS12 ",false, function(bool)
  _G.PoneglyphBOSS12 = bool
end)
    
spawn(function()
  while wait(5) do
    if _G.PoneglyphBOSS12 then
      pcall(function() 
          

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-178.0515594482422, 10.222049713134766, -6624.64208984375)
if (CFrame.new(-178.0515594482422, 10.222049713134766, -6624.64208984375).Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position) >= 5 then
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-178.0515594482422, 10.222049713134766, -6624.64208984375)
end


          wait(10)
          
          
      end)
    end
  end
end) 


tgls2:Seperator()

_G.PoneglyphBOSS13 = false
tgls2:Toggle("PoneglyphBOSS13 ",false, function(bool)
  _G.PoneglyphBOSS13 = bool
end)
    
spawn(function()
  while wait(5) do
    if _G.PoneglyphBOSS13 then
      pcall(function() 
          

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-475.409912109375, 18.663297653198242, -6623.6259765625)
if (CFrame.new(-475.409912109375, 18.663297653198242, -6623.6259765625).Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position) >= 5 then
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-475.409912109375, 18.663297653198242, -6623.6259765625)
end


          wait(10)
          
          
      end)
    end
  end
end) 


tgls2:Seperator()

_G.PoneglyphBOSS14 = false
tgls2:Toggle("PoneglyphBOSS14 ",false, function(bool)
  _G.PoneglyphBOSS14 = bool
end)
    
spawn(function()
  while wait(5) do
    if _G.PoneglyphBOSS14 then
      pcall(function() 
          

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-778.7122802734375, 10.221704483032227, -6565.5048828125)
if (CFrame.new(-778.7122802734375, 10.221704483032227, -6565.5048828125).Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position) >= 5 then
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-778.7122802734375, 10.221704483032227, -6565.5048828125)
end


          wait(10)
          
          
      end)
    end
  end
end) 


tgls2:Seperator()


_G.PoneglyphBOSS15 = false
tgls2:Toggle("PoneglyphBOSS15 ",false, function(bool)
  _G.PoneglyphBOSS15 = bool
end)
    
spawn(function()
  while wait(5) do
    if _G.PoneglyphBOSS15 then
      pcall(function() 
          

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1165.843505859375, 10.413412094116211, -6579.56005859375)
if (CFrame.new(-1165.843505859375, 10.413412094116211, -6579.56005859375).Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position) >= 5 then
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1165.843505859375, 10.413412094116211, -6579.56005859375)
end


          wait(10)
          
          
      end)
    end
  end
end) 


tgls2:Seperator()


_G.PoneglyphBOSS16 = true
tgls2:Toggle("PoneglyphBOSS16 ",true, function(bool)
  _G.PoneglyphBOSS16 = bool
end)
    
spawn(function()
  while wait(5) do
    if _G.PoneglyphBOSS16 then
      pcall(function() 
          

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1430.378662109375, 10.41330623626709, -6727.16943359375)
if (CFrame.new(-1430.378662109375, 10.41330623626709, -6727.16943359375).Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position) >= 5 then
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1430.378662109375, 10.41330623626709, -6727.16943359375)
end


          wait(10)
          
          
      end)
    end
  end
end) 
--------------------------------------------------------------


tgls3:Seperator()

tgls3:Button("ZONE1", function()
    
  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-48.262176513671875, 8.998024940490723, -130.1291961669922)    
      
  
end)

tgls3:Seperator()
tgls3:Button("ZONE2", function()
    
  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-300.875, 13.99802303314209, -139.75)    
      
  
end)

tgls3:Seperator()
tgls3:Button("ZONE3", function()
    
  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-470.15972900390625, 13.99802303314209, -139.75)    
      
  
end)

tgls3:Seperator()
tgls3:Button("ZONE4", function()
    
  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-643.849853515625, 13.99802303314209, -139.75)    
      
  
end)

tgls3:Seperator()
tgls3:Button("ZONE5", function()
    
  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-943.8048095703125, 11.8285493850708, -142.84011840820312)    
      
  
end)

tgls3:Seperator()
tgls3:Button("ZONE6", function()
    
  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2189.125, 13.99802303314209, -139.75)    
      
  
end)

tgls3:Seperator()
tgls3:Button("ZONE7", function()
    
  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2398.625, 14.008025169372559, -139.75)    
      
  
end)

tgls3:Seperator()
tgls3:Button("ZONE8", function()
    
  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2608.125, 14.024022102355957, -139.75)    
      
  
end)

tgls3:Seperator()
tgls3:Button("ZONE9", function()
    
  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2818.125, 13.99802303314209, -139.75)    
      
  
end)

tgls3:Seperator()
tgls3:Button("ZONE10", function()
    
  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-3027.875, 13.99802303314209, -139.75)    
      
  
end)

tgls3:Seperator()
tgls3:Button("ZONE11", function()
    
  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-3391.25927734375, 23.2437744140625, -137.75489807128906)    
      
  
end)

tgls3:Seperator()
tgls3:Button("Word2", function()
    
  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(47.553287506103516, 6.424801349639893, -6611.669921875)    
      
  
end)

tgls3:Seperator()
tgls3:Button("ZONE12", function()
    
  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-292.86920166015625, 6.424800395965576, -6734.72412109375)    
      
  
end)

tgls3:Seperator()
tgls3:Button("ZONE13", function()
    
  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-633.264892578125, 6.424800395965576, -6497.91650390625)    
      
  
end)

tgls3:Seperator()
tgls3:Button("ZONE14", function()
    
  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-972.72900390625, 6.424800395965576, -6496.00439453125)    
      
  
end)

tgls3:Seperator()
tgls3:Button("ZONE15", function()
    
  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1312.516357421875, 6.298173427581787, -6729.02392578125)    
      
  
end)

tgls3:Seperator()

tgls3:Button("ZONE16", function()
    
  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1653.21337890625, 6.424801349639893, -6733.16015625)    
      
  
end)

tgls3:Seperator()
----
end
  

