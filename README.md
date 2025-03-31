local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/jensonhirst/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "Star Hub BETA", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})

local Tab = Window:MakeTab({
	Name = "Scripts",
	Icon = "rbxassetid://79196295054020",
	PremiumOnly = false
})

local Section = Tab:AddSection({
	Name = "Scripts Brookhaven!"
})

Tab:AddButton({
	Name = "Chaos Hub",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/Luscaa22/Calabocaa/refs/heads/main/ChaosHub"))()
  	end    
})

Tab:AddButton({
	Name = "Rael Hub",
	Callback = function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Laelmano24/Rael-Hub/main/main.txt"))()	
  	end    
})

Tab:AddButton({
	Name = "Jãozin Hub(em breve)",
	Callback = function()
      		print("button pressed")
  	end    
})

