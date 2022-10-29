local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("PremXlinhub test", "Synapse")

local Tab = Window:NewTab("BloxFruit")
local Section = Tab:NewSection("Unique hub")

Section:NewButton("GetUnique", "ButtonInfo", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/AkiraNus/UniquehubKak/main/FreeCr.Xenonhub"))();

end)
local Section = Tab:NewSection("Ripper Hub")

Section:NewButton("Get Ripper hub", "ButtonInfo", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/hajibeza/RIPPER-HUB/main/RIPPERHUBV2.lua"))()
end)
local Section = Tab:NewSection("Maluro Hub")

Section:NewButton("Get Makuro", "ButtonInfo", function()
    loadstring(game:HttpGet"https://raw.githubusercontent.com/xQuartyx/DonateMe/main/ScriptLoader")()
end)
local Section = Tab:NewSection("Neva hub")

Section:NewButton("Get Neva hub", "ButtonInfo", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/VEZ2/NEVAHUB/main/2'))()
end)

local Tab = Window:NewTab("Air Plane Simulator")
local Section = Tab:NewSection("Air Plane Script hub")

Section:NewButton("Get Air Plane Simulator hub", "ButtonInfo", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Marco8642/science/main/airplane%20simulator", true))()
end)
local Tab = Window:NewTab("Ro-Ghoul")
local Section = Tab:NewSection("Ro-Ghoul")

Section:NewButton("GetScript Ro-Ghoul", "ButtonInfo", function()
    loadstring(game:HttpGetAsync(("https://raw.githubusercontent.com/z4gs/scripts/master/Ro-Ghoul%20Auto%20Farm.lua")))()
end)
