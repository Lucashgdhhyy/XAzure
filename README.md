-- By BaconExility
print("By BaconExility")
warn("Idea server discord")
local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
  local Window = OrionLib:MakeWindow({
		Name = "X Azure Beta| V0.5",
		HidePremium = false,
		SaveConfig = true,
		ConfigFolder = "X Azure Random Game:D",
        IntroText = "Loading X Azure"       
})

local Tab = Window:MakeTab({
	Name = "Main",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddParagraph("Loading All Wait 3 secounds for load all","Wait the search box for use script")
wait(3)
OrionLib:MakeNotification({
	Name = "Loading Hub",
	Content = "Sucefull for loading All",
	Image = "rbxassetid://4483345998",
	Time = 5
})

Tab:AddParagraph("Hello!","Thank you for use my hub")

Tab:AddTextbox({
	Name = "Notepad",
	Default = "X Azure on top",
	TextDisappear = false,
	Callback = function(Value)
		warn(Value)
	end	  
})

Tab:AddButton({
	Name = "Destoy Ui",
	Callback = function()         OrionLib:Destroy()
      		print("Deleting Ui")                 
  	end    
})


OrionLib:Init()

local Tab2 = Window:MakeTab({
	Name = "Blox Fruit",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Tab3 = Window:MakeTab({
	Name = "Pet Simulator 99",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Tab4 = Window:MakeTab({
	Name = "Blade Ball",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab4:AddButton({
	Name = "Bedol Hub",
	Callback = function()
      		print("button pressed")            _G.UI_Size = 200 -- config ui size
loadstring(game:HttpGet("https://raw.githubusercontent.com/3345-c-a-t-s-u-s/-beta-/main/AutoParry.lua"))() 
  	end    
})


Tab2:AddButton({
	Name = "Redz Hub",
	Callback = function()
      		print("button pressed")                 loadstring(game:HttpGet("https://raw.githubusercontent.com/REDzHUB/BloxFruits/main/redz9999"))()
  	end    
})

local Tab5 = Window:MakeTab({
	Name = "Admins CMDS",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})


Tab3:AddButton({
	Name = "Redz hub",
	Callback = function()
      		print("button pressed")         loadstring(game:HttpGet("https://raw.githubusercontent.com/REDzHUB/PetSimulator99/main/redz9999.lua"))()
  	end    
})

Tab5:AddButton({
	Name = "Infinity Yield",
	Callback = function()
      		print("button pressed")                 loadstring(game:HttpGet(('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'),true))()
  	end    
})

