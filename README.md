local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/jensonhirst/Orion/main/source')))()
local Window = OrionLib:MakeWindow({
    Name = "StarHub BETA",
    HidePremium = false,
    SaveConfig = true,
    ConfigFolder = "StarHub",
    Theme = {
        Main = Color3.fromRGB(0, 0, 0), -- Preto
        Accent = Color3.fromRGB(255, 204, 0) -- Amarelo
    }
})

})

local Tab = Window:MakeTab({
    Name = "Nosso servidor!",
    Icon = "rbxassetid://18810599582",
    PremiumOnly = false
})

Tab:AddButton({
    Name = "Copiar Link do Discord",
    Callback = function()
        setclipboard("https://discord.gg/kBDk5YMR2R")
    end
})
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
      		print("button pressed")
  	end    
})

Tab:AddButton({
	Name = "Jãozin Hub ( Em Breve )",
	Callback = function()
      		print("button pressed")
  	end    
  
  local Tab = Window:MakeTab({
    Name = "Universal",
    Icon = "rbxassetid://18810599582",
    PremiumOnly = false
    
Tab:AddButton({
	Name = "Fly",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/zackdoesstuff/ROBLOX-Fly-Script/refs/heads/main/Fly%20Script"))()
  	end    
    
