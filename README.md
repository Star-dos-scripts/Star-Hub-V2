local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/jensonhirst/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "Star Hub BETA", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})

--[[
Name = <Star Hub Beta> - The name of the UI.
HidePremium = <bool> - Whether or not the user details shows Premium status or not.
SaveConfig = <bool> - Toggles the config saving in the UI.
ConfigFolder = <string> - The name of the folder where the configs are saved.
IntroEnabled = <true> - Whether or not to show the intro animation.
IntroText = <O pior script kkj> - Text to show in the intro animation.
IntroIcon = <rbxassetid://79196295054020> - URL to the image you want to use in the intro animation.
Icon = <rbxassetid://79196295054020> - URL to the image you want displayed on the window.
CloseCallback = <print(Hello desgraça)> - Function to execute when the window is closed.
]]
local Tab = Window:MakeTab({
	Name = "Seção BETA",
	Icon = "rbxassetid://79196295054020",
	PremiumOnly = false
})

--[[
Name = <string> - The name of the tab.
Icon = <string> - The icon of the tab.
PremiumOnly = <bool> - Makes the tab accessible to Sirus Premium users only.
]]
local Section = Tab:AddSection({
	Name = "beta"
})

--[[
Name = <string> - The name of the section.
]]
