local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("GGPRO", "BloodTheme")

local Tab = Window:NewTab("World 1")
local Section = Tab:NewSection("TPMAP")

Section:NewButton("Pirate Island lv.50", "ButtonInfo", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3411.96021, 39.6031227, -482.1651, -0.772881806, -3.1927712e-08, -0.634550035, -3.29693677e-08, 1, -1.01588347e-08, 0.634550035, 1.30691342e-08, -0.772881806)
end)

Section:NewButton("Soldier Town lv.100", "ButtonInfo", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1747.97937, 39.8139877, 129.026276, 0.405908257, 7.93705226e-08, 0.913913846, -8.29380724e-08, 1, -5.00104846e-08, -0.913913846, -5.54985853e-08, 0.405908257)
end)

Section:NewButton("Snow Island lv.400", "ButtonInfo", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-1192.74536, 19.8805447, 1434.36938, 0.208112091, -3.46119644e-09, -0.978105009, 1.56574949e-08, 1, -2.07219519e-10, 0.978105009, -1.52715494e-08, 0.208112091)
end)

Section:NewButton("Desert Island lv.525", "ButtonInfo", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1248.2854, 12.8412962, 2092.69336, -0.422780067, 8.98373198e-09, -0.906232297, 2.18747367e-08, 1, -2.91835306e-10, 0.906232297, -1.99469756e-08, -0.422780067)
end)

Section:NewButton("Shark Island lv.180", "ButtonInfo", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3278.24146, 11.8388433, 1428.89917, -0.573683619, -1.24583011e-09, -0.819076955, -2.2138209e-09, 1, 2.9548787e-11, 0.819076955, 1.8302414e-09, -0.573683619)
end)

Section:NewButton("Chef Ship lv.250", "ButtonInfo", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-28.8066406, 102.684029, 85.7923584, 1, 0, 0, 0, 1, 0, 0, 0, 1)
end)

Section:NewButton("Bubbleland lv.1000", "ButtonInfo", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(5851.77051, 12.2159128, 3539.27246, 0.369597316, 3.45035254e-08, 0.929192007, -9.65803935e-08, 1, 1.28319e-09, -0.929192007, -9.02159911e-08, 0.369597316)
end)

Section:NewButton("Skyland lv.800", "ButtonInfo", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-85.9745026, 200.70256, 3891.61523, 0.992767096, 6.83166022e-08, -0.120056137, -6.87034074e-08, 1, 9.17282028e-10, 0.120056137, 7.33761807e-09, 0.992767096)
end)

Section:NewButton("LobbyIsland lv.1250", "ButtonInfo", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3008.60059, 14.6785393, 5032.15771, 0.996203363, 3.5691393e-08, 0.0870568603, -3.58691601e-08, 1, 4.77687168e-10, -0.0870568603, -3.59853014e-09, 0.996203363)
end)

Section:NewButton("Town lv.0", "ButtonInfo", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(2130.36914, 50.3857689, -1626.34595, -0.790067494, 8.29689455e-08, -0.613019884, 1.06109461e-07, 1, -1.41054313e-09, 0.613019884, -6.61616326e-08, -0.790067494)
end)

Section:NewButton("ZombieIsland lv.1500", "ButtonInfo", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1633.63855, 26.4423466, 6663.95264, 0.87643379, -9.68825731e-08, -0.481522381, 1.09735318e-07, 1, -1.46790524e-09, 0.481522381, -5.15534921e-08, 0.87643379)
end)

Section:NewButton("WarIsland lv.1750", "ButtonInfo", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(6574.22363, 50.9643936, 780.072083, -0.910830498, -3.38524835e-08, -0.412780613, -3.66523167e-08, 1, -1.13483545e-09, 0.412780613, 1.40957228e-08, -0.910830498)
end)

Section:NewButton("Fishland lv.2000", "ButtonInfo", function()
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3037.96411, 7.28140974, 9111.66797, -0.86611563, -3.22682077e-08, -0.499843687, -3.75469398e-08, 1, 5.03719011e-10, 0.499843687, 1.92038794e-08, -0.86611563)
end)

Section:NewKeybind("KeybindText", "KeybindInfo", Enum.KeyCode.RightShift, function()
	Library:ToggleUI()
end)
