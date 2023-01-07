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

_G.Egg10M = false
tgls1:Toggle("Egg10M",false, function(bool)
  _G.Egg10M = bool
end)
spawn(function()
  while wait(0.5) do
    if _G.Egg10M then
      pcall(function() 
          


local args = {
    [1] = "MagmaEgg",
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

_G.BOSS10 = true
tgls2:Toggle("BOSS10 ",true, function(bool)
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
end
  
