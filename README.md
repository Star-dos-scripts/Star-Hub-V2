local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/jensonhirst/Orion/main/source')))()
local Window = OrionLib:MakeWindow({Name = "Star Hub BETA", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})


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
  })
  local Tab = Window:MakeTab({
    Name = "Funções",
    Icon = "rbxassetid://4483345998",
    PremiumOnly = false
})

Tab:AddButton({
    Name = "Ativar Fly",
    Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/zackdoesstuff/ROBLOX-Fly-Script/refs/heads/main/Fly%20Script"))()
    end
})
