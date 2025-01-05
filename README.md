local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()

local Window = OrionLib:MakeWindow({Name = "Choose The Script", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})

local Tab = Window:MakeTab({
	Name = "Credit",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = Tab:AddSection({
	Name = "by @hickini"
})

local Tab = Window:MakeTab({
	Name = "RPG",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Blox Fruit",
	Callback = function()
   loadstring(game:HttpGet("https://pastebin.com/raw/P9ZSmyNR"))()		
  	end    
})

local Tab = Window:MakeTab({
	Name = "Simulator",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Legends Of Speed",
	Callback = function()
      		loadstring(game:HttpGet("https://rawscripts.net/raw/Legends-Of-Speed-Speeeeed-Farm-Open-Source-old-code-lel-1785"))()
OrionLib:Destroy()
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

Tab:AddButton({
	Name = "Build A Boat",
	Callback = function()
      		loadstring(game:HttpGet("https://pastebin.com/raw/XjN5iEvp"))()
  	end    
})

local Tab = Window:MakeTab({
	Name = "Obby",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Tower Of Hell",
	Callback = function()
      		loadstring(game:HttpGet("https://rawscripts.net/raw/Tower-of-Hell-Starry-OP-BEST-Script-Hub-17868"))()
OrionLib:Destroy()
  	end    
})