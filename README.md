local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("ZacH OMNIGOD", "GrapeTheme")

local Tab = Window:NewTab("Main")
local Section = Tab:NewSection("GOD Command")

Section:NewButton("Get Command", "Command", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
end)
