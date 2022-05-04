local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("PSX AUTO SCAM", "Sentinel")
local Tab = Window:NewTab("AUTOSCAM")
local Section = Tab:NewSection("Toogle on to make it work")
Section:NewToggle("AUTOSCAM", "Scam people", function(state)

    if state then

        print("Toggle On")

    else

        print("Toggle Off")

    end

end)
