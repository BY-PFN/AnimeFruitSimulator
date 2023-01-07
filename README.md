
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
-----------------------------------------------------------------------------
_G.BOSSAyden = true
tgls2:Toggle("BOSSAyden ",true, function(bool)
  _G.BOSSAyden = bool
end)
    
spawn(function()
  while wait(2) do
    if _G.BOSSAyden then
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


----
end
  
