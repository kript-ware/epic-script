# epic-script   
-----ISK IS NOT RESPONSIBLE IF YOU GET BANNED. imagine getting banned tho lol

spawn(function()
local message = Instance.new("Message",workspace)
message.Text = "CREDITS TO THE PEOPLE WHO MADE THE SCRIPTS  HAVE FUN EXPLOITING<3"
wait(10)
message:Destroy()
end)




local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("isk hub.", "GrapeTheme")

--main
local Main = Window:NewTab("Main")
local MainSection = Main:NewSection("Main")

MainSection:NewButton("Arsenal script", "i am not responsible if you get banned", function()
   loadstring(game:HttpGet("https://raw.githubusercontent.com/CriShoux/OwlHub/master/OwlHub.txt"))();
end)

MainSection:NewToggle("owl hub", "makes you be good", function(state)
    if state then
        loadstring(game:HttpGet("https://raw.githubusercontent.com/CriShoux/OwlHub/master/OwlHub.txt"))();
    else
       loadstring(game:HttpGet("https://raw.githubusercontent.com/CriShoux/OwlHub/master/OwlHub.txt"))();
    end
end)

MainSection:NewSlider("SPEED!!!", "it increases your speed", 500, 0, function(s) -- 500 (MaxValue) | 0 (MinValue)
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = s
end)

--main
local Main = Window:NewTab("da hood!!")
local MainSection = Main:NewSection("streamble and fake macro")

MainSection:NewButton("Streamble", "i am not responsible if you get banned", function()
   -- 0.138
-- 0.11243
loadstring(game:HttpGet("https://raw.githubusercontent.com/topillesrevenge/Streamable-Silent/main/Main"))()
DaHoodSettings.Prediction = 0.121
Aiming.TargetPart = {"Head", "LeftHand", "RightHand", "LeftLowerArm", "RightLowerArm", "LeftUpperArm", "RightUpperArm", "LeftFoot", "LeftLowerLeg", "UpperTorso", "HumanoidRootPart", "LeftUpperLeg", "RightLowerLeg", "RightFoot", "LowerTorso"}
Aiming.FOV = 25
Aiming.FOVSides = 25
Aiming.HitChance = 400
Aiming.ShowFOV = false
end)

MainSection:NewToggle("Fake macro", "its insane ", function(state)
    if state then
        if game.PlaceId == 2788229376 then
    if getgenv().L_15 == true then
        game.StarterGui:SetCore("SendNotification", {
            Title = "Speed Glitch";
            Text = "Already Executed";
        })
        return
    end
    getgenv().L_15 = true -- dont change me
    
    getgenv().Notification = true
    getgenv().AutoMacro = true
    getgenv().Macro = true
    getgenv().AutoMacroKey = Enum.KeyCode.Z
    getgenv().MacroKey = Enum.KeyCode.X
    getgenv().MacroMode = "Mouse" -- Keyboard, Mouse
    getgenv().GodMacro = true
    getgenv().GodMacroKey = Enum.KeyCode.C
    getgenv().GodMacroAuto = false

    if AutoMacro == true then
        game:GetService("UserInputService").InputBegan:Connect(function(input, chatting)
            if input.UserInputType == Enum.UserInputType.Keyboard then
                if chatting then
                    IsChatting = true
                else
                    IsChatting = false
                end
                if input.KeyCode == AutoMacroKey then
                    if IsChatting ~= false then
                        return
                    end
                    if not AutoMacroToggle then
                        if Notification == true then
                            game.StarterGui:SetCore("SendNotification", {
                                Title = "AutoMacro";
                                Text = "AutoMacro: On";
                            })
                        end
                        AutoMacroToggle = true
                        Instance.new("Animation", game:GetService("ReplicatedStorage"):findFirstChild("ClientAnimations")).Name = 'Greet'
                        game:GetService("ReplicatedStorage"):findFirstChild("ClientAnimations"):findFirstChild("Greet").AnimationId = 'rbxassetid://3189777795'
                        local Greet = game.ReplicatedStorage.ClientAnimations.Greet
                        local Humanoid = game.Players.LocalPlayer.Character.Humanoid
                        local Animation = Humanoid:LoadAnimation(Greet)
                        Animation:Play()
                        wait(1.6)
                        for i, v in next, game:GetService("Players").LocalPlayer.Backpack:GetChildren() do
                            if v:IsA("Tool") and v.Name ~= "Combat" or v.Name ~= "[Boombox]" then
                                game:GetService("Players").LocalPlayer.Character:findFirstChildOfClass'Humanoid':EquipTool(v)
                            end
                        end
                        wait()
                        game:GetService("VirtualInputManager"):SendKeyEvent(true, "S", false, game)
                        spawn(function()
                            if MacroMode == "Keyboard" then
                                while AutoMacroToggle == true do
                                    wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "I", false, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "O", false, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "I", false, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "O", false, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "I", false, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "O", false, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "I", false, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "O", false, game)
                                    wait()
                                end
                            elseif MacroMode == "Mouse" then
                                while AutoMacroToggle == true do
                                    wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", true, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", false, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", true, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", false, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", true, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", false, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", true, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", false, game)
                                    wait()
                                end
                            end
                        end)
                        Animation:Stop()
                        Macro =
                            game:service'Players'.LocalPlayer.Character:findFirstChildOfClass'Humanoid'.Running:Connect(function()
                                Animation:Stop()
                            end)
                    else
                        if Notification == true then
                            game.StarterGui:SetCore("SendNotification", {
                                Title = "AutoMacro";
                                Text = "AutoMacro: Off";
                            })
                        end
                        AutoMacroToggle = false
                        local Greet = game.ReplicatedStorage.ClientAnimations.Greet
                        local Humanoid = game.Players.LocalPlayer.Character.Humanoid
                        local Animation = Humanoid:LoadAnimation(Greet)
                        Animation:Stop()
                        game:GetService("ReplicatedStorage"):findFirstChild("ClientAnimations"):findFirstChild("Greet"):Remove()
                        Macro:Disconnect()
                    end
                end
            end
        end)
    end

    if Macro == true then
        game:GetService("UserInputService").InputBegan:Connect(function(input, chatting)
            if input.UserInputType == Enum.UserInputType.Keyboard then
                if chatting then
                    IsChatting = true
                else
                    IsChatting = false
                end
                if input.KeyCode == MacroKey then
                    if IsChatting ~= false then
                        return
                    end
                    if not MacroToggle then
                        if Notification == true then
                            game.StarterGui:SetCore("SendNotification", {
                                Title = "Macro";
                                Text = "Macro: On";
                            })
                        end
                        MacroToggle = true
                        spawn(function()
                            if MacroMode == "Keyboard" then
                                while MacroToggle == true do
                                    wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "I", false, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "O", false, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "I", false, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "O", false, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "I", false, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "O", false, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "I", false, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "O", false, game)
                                    wait()
                                end
                            elseif MacroMode == "Mouse" then
                                while MacroToggle == true do
                                    wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", true, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", false, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", true, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", false, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", true, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", false, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", true, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", false, game)
                                    wait()
                                end
                            end
                        end)
                    else
                        if Notification == true then
                            game.StarterGui:SetCore("SendNotification", {
                                Title = "Macro";
                                Text = "Macro: Off";
                            })
                            MacroToggle = false
                        end
                    end
                end
            end
        end)
    end
    if GodMacro == true then
        game:GetService("UserInputService").InputBegan:Connect(function(input, chatting)
            if input.UserInputType == Enum.UserInputType.Keyboard then
                if chatting then
                    IsChatting = true
                else
                    IsChatting = false
                end
                if input.KeyCode == GodMacroKey then
                    if IsChatting ~= false then
                        return
                    end
                    if not GodMacroToggle then
                        if Notification == true then
                            game.StarterGui:SetCore("SendNotification", {
                                Title = "GodMacro";
                                Text = "GodMacro: On";
                            })
                        end
                        GodMacroToggle = true
                        if GodMacroAuto == true then
                            Instance.new("Animation", game:GetService("ReplicatedStorage"):findFirstChild("ClientAnimations")).Name = 'Greet'
                            game:GetService("ReplicatedStorage"):findFirstChild("ClientAnimations"):findFirstChild("Greet").AnimationId = 'rbxassetid://3189777795'
                            local Greet = game.ReplicatedStorage.ClientAnimations.Greet
                            local Humanoid = game.Players.LocalPlayer.Character.Humanoid
                            local Animation = Humanoid:LoadAnimation(Greet)
                            Animation:Play()
                            wait(1.6)
                            for i, v in next, game:GetService("Players").LocalPlayer.Backpack:GetChildren() do
                                if v:IsA("Tool") and v.Name ~= "Combat" or v.Name ~= "[Boombox]" then
                                    game:GetService("Players").LocalPlayer.Character:findFirstChildOfClass'Humanoid':EquipTool(v)
                                end
                            end
                            wait()
                            game:GetService("VirtualInputManager"):SendKeyEvent(true, "S", false, game)
                        end
                        spawn(function()
                            if MacroMode == "Keyboard" then
                                while GodMacroToggle == true do
                                    game:GetService("RunService").Heartbeat:wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "I", false, game)
                                    game:GetService("RunService").Heartbeat:wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "O", false, game)
                                    game:GetService("RunService").Heartbeat:wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "I", false, game)
                                    game:GetService("RunService").Heartbeat:wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "O", false, game)
                                    game:GetService("RunService").Heartbeat:wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "I", false, game)
                                    game:GetService("RunService").Heartbeat:wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "O", false, game)
                                    game:GetService("RunService").Heartbeat:wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "I", false, game)
                                    game:GetService("RunService").Heartbeat:wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "O", false, game)
                                    game:GetService("RunService").Heartbeat:wait()
                                end
                            elseif MacroMode == "Mouse" then
                                while GodMacroToggle == true do
                                    game:GetService("RunService").Heartbeat:wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", true, game)
                                    game:GetService("RunService").Heartbeat:wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", false, game)
                                    game:GetService("RunService").Heartbeat:wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", true, game)
                                    game:GetService("RunService").Heartbeat:wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", false, game)
                                    game:GetService("RunService").Heartbeat:wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", true, game)
                                    game:GetService("RunService").Heartbeat:wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", false, game)
                                    game:GetService("RunService").Heartbeat:wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", true, game)
                                    game:GetService("RunService").Heartbeat:wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", false, game)
                                    game:GetService("RunService").Heartbeat:wait()
                                end
                            end
                        end)
                        if GodMacroAuto == true then
                            Animation:Stop()
                            Macro =
                                game:service'Players'.LocalPlayer.Character:findFirstChildOfClass'Humanoid'.Running:Connect(function()
                                    Animation:Stop()
                                end)
                        end
                    else
                        if Notification == true then
                            game.StarterGui:SetCore("SendNotification", {
                                Title = "GodMacro";
                                Text = "GodMacro: Off";
                            })
                            GodMacroToggle = false
                            if GodMacroAuto == true then
                                local Greet = game.ReplicatedStorage.ClientAnimations.Greet
                                local Humanoid = game.Players.LocalPlayer.Character.Humanoid
                                local Animation = Humanoid:LoadAnimation(Greet)
                                Animation:Stop()
                                game:GetService("ReplicatedStorage"):findFirstChild("ClientAnimations"):findFirstChild("Greet"):Remove()
                                Macro:Disconnect()
                            end
                        end
                    end
                end
            end
        end)
    end
end
    else
       if game.PlaceId == 2788229376 then
    if getgenv().L_15 == true then
        game.StarterGui:SetCore("SendNotification", {
            Title = "Speed Glitch";
            Text = "Already Executed";
        })
        return
    end
    getgenv().L_15 = true -- dont change me
    
    getgenv().Notification = true
    getgenv().AutoMacro = true
    getgenv().Macro = true
    getgenv().AutoMacroKey = Enum.KeyCode.Z
    getgenv().MacroKey = Enum.KeyCode.X
    getgenv().MacroMode = "Mouse" -- Keyboard, Mouse
    getgenv().GodMacro = true
    getgenv().GodMacroKey = Enum.KeyCode.C
    getgenv().GodMacroAuto = false

    if AutoMacro == true then
        game:GetService("UserInputService").InputBegan:Connect(function(input, chatting)
            if input.UserInputType == Enum.UserInputType.Keyboard then
                if chatting then
                    IsChatting = true
                else
                    IsChatting = false
                end
                if input.KeyCode == AutoMacroKey then
                    if IsChatting ~= false then
                        return
                    end
                    if not AutoMacroToggle then
                        if Notification == true then
                            game.StarterGui:SetCore("SendNotification", {
                                Title = "AutoMacro";
                                Text = "AutoMacro: On";
                            })
                        end
                        AutoMacroToggle = true
                        Instance.new("Animation", game:GetService("ReplicatedStorage"):findFirstChild("ClientAnimations")).Name = 'Greet'
                        game:GetService("ReplicatedStorage"):findFirstChild("ClientAnimations"):findFirstChild("Greet").AnimationId = 'rbxassetid://3189777795'
                        local Greet = game.ReplicatedStorage.ClientAnimations.Greet
                        local Humanoid = game.Players.LocalPlayer.Character.Humanoid
                        local Animation = Humanoid:LoadAnimation(Greet)
                        Animation:Play()
                        wait(1.6)
                        for i, v in next, game:GetService("Players").LocalPlayer.Backpack:GetChildren() do
                            if v:IsA("Tool") and v.Name ~= "Combat" or v.Name ~= "[Boombox]" then
                                game:GetService("Players").LocalPlayer.Character:findFirstChildOfClass'Humanoid':EquipTool(v)
                            end
                        end
                        wait()
                        game:GetService("VirtualInputManager"):SendKeyEvent(true, "S", false, game)
                        spawn(function()
                            if MacroMode == "Keyboard" then
                                while AutoMacroToggle == true do
                                    wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "I", false, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "O", false, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "I", false, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "O", false, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "I", false, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "O", false, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "I", false, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "O", false, game)
                                    wait()
                                end
                            elseif MacroMode == "Mouse" then
                                while AutoMacroToggle == true do
                                    wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", true, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", false, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", true, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", false, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", true, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", false, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", true, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", false, game)
                                    wait()
                                end
                            end
                        end)
                        Animation:Stop()
                        Macro =
                            game:service'Players'.LocalPlayer.Character:findFirstChildOfClass'Humanoid'.Running:Connect(function()
                                Animation:Stop()
                            end)
                    else
                        if Notification == true then
                            game.StarterGui:SetCore("SendNotification", {
                                Title = "AutoMacro";
                                Text = "AutoMacro: Off";
                            })
                        end
                        AutoMacroToggle = false
                        local Greet = game.ReplicatedStorage.ClientAnimations.Greet
                        local Humanoid = game.Players.LocalPlayer.Character.Humanoid
                        local Animation = Humanoid:LoadAnimation(Greet)
                        Animation:Stop()
                        game:GetService("ReplicatedStorage"):findFirstChild("ClientAnimations"):findFirstChild("Greet"):Remove()
                        Macro:Disconnect()
                    end
                end
            end
        end)
    end

    if Macro == true then
        game:GetService("UserInputService").InputBegan:Connect(function(input, chatting)
            if input.UserInputType == Enum.UserInputType.Keyboard then
                if chatting then
                    IsChatting = true
                else
                    IsChatting = false
                end
                if input.KeyCode == MacroKey then
                    if IsChatting ~= false then
                        return
                    end
                    if not MacroToggle then
                        if Notification == true then
                            game.StarterGui:SetCore("SendNotification", {
                                Title = "Macro";
                                Text = "Macro: On";
                            })
                        end
                        MacroToggle = true
                        spawn(function()
                            if MacroMode == "Keyboard" then
                                while MacroToggle == true do
                                    wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "I", false, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "O", false, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "I", false, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "O", false, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "I", false, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "O", false, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "I", false, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "O", false, game)
                                    wait()
                                end
                            elseif MacroMode == "Mouse" then
                                while MacroToggle == true do
                                    wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", true, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", false, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", true, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", false, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", true, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", false, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", true, game)
                                    wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", false, game)
                                    wait()
                                end
                            end
                        end)
                    else
                        if Notification == true then
                            game.StarterGui:SetCore("SendNotification", {
                                Title = "Macro";
                                Text = "Macro: Off";
                            })
                            MacroToggle = false
                        end
                    end
                end
            end
        end)
    end
    if GodMacro == true then
        game:GetService("UserInputService").InputBegan:Connect(function(input, chatting)
            if input.UserInputType == Enum.UserInputType.Keyboard then
                if chatting then
                    IsChatting = true
                else
                    IsChatting = false
                end
                if input.KeyCode == GodMacroKey then
                    if IsChatting ~= false then
                        return
                    end
                    if not GodMacroToggle then
                        if Notification == true then
                            game.StarterGui:SetCore("SendNotification", {
                                Title = "GodMacro";
                                Text = "GodMacro: On";
                            })
                        end
                        GodMacroToggle = true
                        if GodMacroAuto == true then
                            Instance.new("Animation", game:GetService("ReplicatedStorage"):findFirstChild("ClientAnimations")).Name = 'Greet'
                            game:GetService("ReplicatedStorage"):findFirstChild("ClientAnimations"):findFirstChild("Greet").AnimationId = 'rbxassetid://3189777795'
                            local Greet = game.ReplicatedStorage.ClientAnimations.Greet
                            local Humanoid = game.Players.LocalPlayer.Character.Humanoid
                            local Animation = Humanoid:LoadAnimation(Greet)
                            Animation:Play()
                            wait(1.6)
                            for i, v in next, game:GetService("Players").LocalPlayer.Backpack:GetChildren() do
                                if v:IsA("Tool") and v.Name ~= "Combat" or v.Name ~= "[Boombox]" then
                                    game:GetService("Players").LocalPlayer.Character:findFirstChildOfClass'Humanoid':EquipTool(v)
                                end
                            end
                            wait()
                            game:GetService("VirtualInputManager"):SendKeyEvent(true, "S", false, game)
                        end
                        spawn(function()
                            if MacroMode == "Keyboard" then
                                while GodMacroToggle == true do
                                    game:GetService("RunService").Heartbeat:wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "I", false, game)
                                    game:GetService("RunService").Heartbeat:wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "O", false, game)
                                    game:GetService("RunService").Heartbeat:wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "I", false, game)
                                    game:GetService("RunService").Heartbeat:wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "O", false, game)
                                    game:GetService("RunService").Heartbeat:wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "I", false, game)
                                    game:GetService("RunService").Heartbeat:wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "O", false, game)
                                    game:GetService("RunService").Heartbeat:wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "I", false, game)
                                    game:GetService("RunService").Heartbeat:wait()
                                    game:GetService("VirtualInputManager"):SendKeyEvent(true, "O", false, game)
                                    game:GetService("RunService").Heartbeat:wait()
                                end
                            elseif MacroMode == "Mouse" then
                                while GodMacroToggle == true do
                                    game:GetService("RunService").Heartbeat:wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", true, game)
                                    game:GetService("RunService").Heartbeat:wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", false, game)
                                    game:GetService("RunService").Heartbeat:wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", true, game)
                                    game:GetService("RunService").Heartbeat:wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", false, game)
                                    game:GetService("RunService").Heartbeat:wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", true, game)
                                    game:GetService("RunService").Heartbeat:wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", false, game)
                                    game:GetService("RunService").Heartbeat:wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", true, game)
                                    game:GetService("RunService").Heartbeat:wait()
                                    game:GetService("VirtualInputManager"):SendMouseWheelEvent("0", "0", false, game)
                                    game:GetService("RunService").Heartbeat:wait()
                                end
                            end
                        end)
                        if GodMacroAuto == true then
                            Animation:Stop()
                            Macro =
                                game:service'Players'.LocalPlayer.Character:findFirstChildOfClass'Humanoid'.Running:Connect(function()
                                    Animation:Stop()
                                end)
                        end
                    else
                        if Notification == true then
                            game.StarterGui:SetCore("SendNotification", {
                                Title = "GodMacro";
                                Text = "GodMacro: Off";
                            })
                            GodMacroToggle = false
                            if GodMacroAuto == true then
                                local Greet = game.ReplicatedStorage.ClientAnimations.Greet
                                local Humanoid = game.Players.LocalPlayer.Character.Humanoid
                                local Animation = Humanoid:LoadAnimation(Greet)
                                Animation:Stop()
                                game:GetService("ReplicatedStorage"):findFirstChild("ClientAnimations"):findFirstChild("Greet"):Remove()
                                Macro:Disconnect()
                            end
                        end
                    end
                end
            end
        end)
    end
end
    end
end)

MainSection:NewToggle("ANTI AIM FINALLY", "makes people from krnl stop locking", function(state)
    if state then
        local Toggled = true
local KeyCode = 'z'
local hip = 2.80
local val = -35
 
 
 
 
 
function AA()
    local oldVelocity = game.Players.LocalPlayer.Character.HumanoidRootPart.Velocity
    game.Players.LocalPlayer.Character.HumanoidRootPart.Velocity = Vector3.new(oldVelocity.X, val, oldVelocity.Z)
    game.Players.LocalPlayer.Character.HumanoidRootPart.Velocity = Vector3.new(oldVelocity.X, oldVelocity.Y, oldVelocity.Z)
    game.Players.LocalPlayer.Character.HumanoidRootPart.Velocity = Vector3.new(oldVelocity.X, val, oldVelocity.Z)
    game.Players.LocalPlayer.Character.Humanoid.HipHeight = hip
end
 
game:GetService('UserInputService').InputBegan:Connect(function(Key)
    if Key.KeyCode == Enum.KeyCode[KeyCode:upper()] and not game:GetService('UserInputService'):GetFocusedTextBox() then
        if Toggled then
            Toggled = false
            game.Players.LocalPlayer.Character.Humanoid.HipHeight = hip
 
        elseif not Toggled then
            Toggled = true
 
            while Toggled do
                AA()
                task.wait()
            end
        end
    end
end)
    else
       local Toggled = true
local KeyCode = 'z'
local hip = 2.80
local val = -35
 
 
 
 
 
function AA()
    local oldVelocity = game.Players.LocalPlayer.Character.HumanoidRootPart.Velocity
    game.Players.LocalPlayer.Character.HumanoidRootPart.Velocity = Vector3.new(oldVelocity.X, val, oldVelocity.Z)
    game.Players.LocalPlayer.Character.HumanoidRootPart.Velocity = Vector3.new(oldVelocity.X, oldVelocity.Y, oldVelocity.Z)
    game.Players.LocalPlayer.Character.HumanoidRootPart.Velocity = Vector3.new(oldVelocity.X, val, oldVelocity.Z)
    game.Players.LocalPlayer.Character.Humanoid.HipHeight = hip
end
 
game:GetService('UserInputService').InputBegan:Connect(function(Key)
    if Key.KeyCode == Enum.KeyCode[KeyCode:upper()] and not game:GetService('UserInputService'):GetFocusedTextBox() then
        if Toggled then
            Toggled = false
            game.Players.LocalPlayer.Character.Humanoid.HipHeight = hip
 
        elseif not Toggled then
            Toggled = true
 
            while Toggled do
                AA()
                task.wait()
            end
        end
    end
end)
    end
end)

MainSection:NewToggle("Aim viewer", "view the wannabes sin bladi", function(state)
    if state then
    --KEY IS C
 
getgenv().tog = false
getgenv().key = "c"
getgenv().X = 68756
getgenv().Y = 100
getgenv().Z = -344
 
game:GetService("RunService").Heartbeat:Connect(function()
        if getgenv().tog then
                local vel = game.Players.LocalPlayer.Character.HumanoidRootPart.Velocity
                game.Players.LocalPlayer.Character.HumanoidRootPart.Velocity = Vector3.new(getgenv().X, getgenv().Y, getgenv().Z)
                game:GetService("RunService").RenderStepped:Wait()
                game.Players.LocalPlayer.Character.HumanoidRootPart.Velocity = vel
        end
end)
 
game:GetService("Players").LocalPlayer:GetMouse().KeyDown:Connect(function(keyPressed)
        if keyPressed == string.lower(getgenv().key) then
                pcall(function()
                        if getgenv().tog == false then
                                getgenv().tog = true
                                game.StarterGui:SetCore("SendNotification", {
                                        Title = "Actyrn#7104",
                                        Text = "AA Enabled" })
                        elseif getgenv().tog == true then
                                getgenv().tog = false
                                game.StarterGui:SetCore("SendNotification", {
                                        Title = "Actyrn#7104",
                                        Text = "AA Disabled" })
                        end
                end)
        end
end)
hookfunction(game.Players.LocalPlayer.IsInGroup, function() return true end)
 
loadstring(game:HttpGet("https://raw.githubusercontent.com/Nosssa/NossLock/main/VinGUI"))()
    end
end)


--hood customs xoxo
local Main = Window:NewTab("hood customs")
local MainSection = Main:NewSection("ONLY FFA HOOD CUSTOMS")

MainSection:NewButton("hood customs camlock ", "key is C to turn it off P", function()
   getgenv().Prediction = 0.1248710929171	
getgenv().AimPart = "HumanoidRootPart"	
getgenv().Key = "Q"	
getgenv().DisableKey = "P"	
	
getgenv().FOV = true	
getgenv().ShowFOV = false	
getgenv().FOVSize = 55	
	
--// Variables (Service)	
	
local Players = game:GetService("Players")	
local RS = game:GetService("RunService")	
local WS = game:GetService("Workspace")	
local GS = game:GetService("GuiService")	
local SG = game:GetService("StarterGui")	
	
--// Variables (regular)	
	
local LP = Players.LocalPlayer	
local Mouse = LP:GetMouse()	
local Camera = WS.CurrentCamera	
local GetGuiInset = GS.GetGuiInset	
	
local AimlockState = true	
local Locked	
local Victim	
	
local SelectedKey = getgenv().Key	
local SelectedDisableKey = getgenv().DisableKey	
	
--// Notification function	
	
function Notify(tx)	
    SG:SetCore("SendNotification", {	
        Title = "isks lock!",	
        Text = tx,	
Duration = 5	
    })	
end	
	
--// Check if aimlock is loaded	
	
if getgenv().Loaded == true then	
    Notify("aimlock is ready!")	
    return	
end	
	
getgenv().Loaded = true	
	
--// FOV Circle	
	
local fov = Drawing.new("Circle")	
fov.Filled = false	
fov.Transparency = 1	
fov.Thickness = 1	
fov.Color = Color3.fromRGB(255, 255, 0)	
fov.NumSides = 1000	
	
--// Functions	
	
function update()	
    if getgenv().FOV == true then	
        if fov then	
fov.Radius = getgenv().FOVSize * 2	
            fov.Visible = getgenv().ShowFOV	
fov.Position = Vector2.new(Mouse.X, Mouse.Y + GetGuiInset(GS).Y)	
	
            return fov	
        end	
    end	
end	
	
function WTVP(arg)	
    return Camera:WorldToViewportPoint(arg)	
end	
	
function WTSP(arg)	
    return Camera.WorldToScreenPoint(Camera, arg)	
end	
	
function getClosest()	
    local closestPlayer	
    local shortestDistance = math.huge	
	
    for i, v in pairs(game.Players:GetPlayers()) do	
        local notKO = v.Character:WaitForChild("BodyEffects")["K.O"].Value ~= true	
        local notGrabbed = v.Character:FindFirstChild("GRABBING_COINSTRAINT") == nil	
        	
if v ~= game.Players.LocalPlayer and v.Character and v.Character:FindFirstChild("Humanoid") and v.Character.Humanoid.Health ~= 0 and v.Character:FindFirstChild(getgenv().AimPart) and notKO and notGrabbed then	
            local pos = Camera:WorldToViewportPoint(v.Character.PrimaryPart.Position)	
local magnitude = (Vector2.new(pos.X, pos.Y) - Vector2.new(Mouse.X, Mouse.Y)).magnitude	
            	
            if (getgenv().FOV) then	
                if (fov.Radius > magnitude and magnitude < shortestDistance) then	
                    closestPlayer = v	
                    shortestDistance = magnitude	
                end	
            else	
                if (magnitude < shortestDistance) then	
                    closestPlayer = v	
                    shortestDistance = magnitude	
                end	
            end	
        end	
    end	
    return closestPlayer	
end	
	
--// Checks if key is down	
	
Mouse.KeyDown:Connect(function(k)	
    SelectedKey = SelectedKey:lower()	
    SelectedDisableKey = SelectedDisableKey:lower()	
    if k == SelectedKey then	
        if AimlockState == true then	
            Locked = not Locked	
            if Locked then	
                Victim = getClosest()	
	
                Notify("Locked onto: "..tostring(Victim.Character.Humanoid.DisplayName))	
            else	
                if Victim ~= nil then	
                    Victim = nil	
	
                    Notify("Unlocked!")	
                end	
            end	
        else	
            Notify("Aimlock is not enabled!")	
        end	
    end	
    if k == SelectedDisableKey then	
        AimlockState = not AimlockState	
    end	
end)	
	
--// Loop update FOV and loop camera lock onto target	
	
RS.RenderStepped:Connect(function()	
    update()	
    if AimlockState == true then	
        if Victim ~= nil then	
            Camera.CFrame = CFrame.new(Camera.CFrame.p, Victim.Character[getgenv().AimPart].Position + Victim.Character[getgenv().AimPart].Velocity*getgenv().Prediction)	
        end	
    end	
end)	
	while wait() do
        if getgenv().AutoPrediction == true then	
        local pingvalue = game:GetService("Stats").Network.ServerStatsItem["Data Ping"]:GetValueString()	
        local split = string.split(pingvalue,'(')	
local ping = tonumber(split[1])	
if ping < 225 then	
getgenv().Prediction = 1.4	
elseif ping < 215 then	
getgenv().Prediction = 1.2	
	elseif ping < 205 then
getgenv().Prediction = 1.0	
	elseif ping < 190 then
getgenv().Prediction = 0.10	
elseif ping < 180 then	
getgenv().Prediction = 0.12	
	elseif ping < 170 then
getgenv().Prediction = 0.15	
	elseif ping < 160 then
getgenv().Prediction = 0.18	
	elseif ping < 150 then
getgenv().Prediction = 0.110	
elseif ping < 140 then	
getgenv().Prediction = 0.113	
elseif ping < 130 then	
getgenv().Prediction = 0.116	
elseif ping < 120 then	
getgenv().Prediction = 0.120	
elseif ping < 110 then	
getgenv().Prediction = 0.124	
elseif ping < 105 then	
getgenv().Prediction = 0.127	
elseif ping < 90 then	
getgenv().Prediction = 0.130	
elseif ping < 80 then	
getgenv().Prediction = 0.133	
elseif ping < 70 then	
getgenv().Prediction = 0.136	
elseif ping < 60 then	
getgenv().Prediction = 0.140	
elseif ping < 50 then	
getgenv().Prediction = 0.143	
elseif ping < 40 then	
getgenv().Prediction = 0.145	
elseif ping < 30 then	
getgenv().Prediction = 0.155	
elseif ping < 20 then	
getgenv().Prediction = 0.157	
        end	
        end	
	end
end)

--fun?
local Main = Window:NewTab("fun stuff?")
local MainSection = Main:NewSection("i guess troll.")


MainSection:NewButton("da best rizz", "i am not responsible if you get banned", function()
 loadstring(game:HttpGet("https://pastebin.com/raw/pPMRh5YJ"))()
end)

MainSection:NewButton("Toxic spam", "Just watch ", function()
    loadstring(game:HttpGet('https://pastebin.com/raw/iLSVsnjZ'))()
end)

MainSection:NewButton("big head", "makes ur head be big.", function()
   loadstring(game:HttpGet("https://raw.githubusercontent.com/sysGhost-aka-BiKode/Scripts2022/main/BigHeadV3_Unpatched", true))()
end)

MainSection:NewButton("ClickTP", "Click Teleportation.", function()
    mouse = game.Players.LocalPlayer:GetMouse()
tool = Instance.new("Tool")
tool.RequiresHandle = false
tool.Name = "ClickTP"
tool.Activated:connect(function()
local pos = mouse.Hit+Vector3.new(0,2.5,0)
pos = CFrame.new(pos.X,pos.Y,pos.Z)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = pos
end)
tool.Parent = game.Players.LocalPlayer.Backpack
end)

MainSection:NewToggle("Infinite Jump", "just jump alot.", function(state)
    if state then
_G.infinjump = true
local Player = game:GetService("Players").LocalPlayer
local Mouse = Player:GetMouse()
Mouse.KeyDown:connect(function(k)
if _G.infinjump then
if k:byte() == 32 then
Humanoid = game:GetService("Players").LocalPlayer.Character:FindFirstChildOfClass("Humanoid")
Humanoid:ChangeState("Jumping")
wait(0.1)
Humanoid:ChangeState("Seated")
end
end
end)
local Player = game:GetService("Players").LocalPlayer
local Mouse = Player:GetMouse()
    else
if _G.infinjump == true then
_G.infinjump = false
else
_G.infinjump = true
end
end
end)

 
MainSection:NewTextBox("Goto", "Go to a player.", function(PlayerTeleportName)
local playerone = game.Players.LocalPlayer.Character
local playertwo = game.Workspace:FindFirstChild(PlayerTeleportName)
playerone.HumanoidRootPart.CFrame = playertwo.HumanoidRootPart.CFrame * CFrame.new(0,2,0)
end)

MainSection:NewButton("Noclip", "A simple noclip command, press 'V' to toggle.", function()
noclip = false
game:GetService('RunService').Stepped:connect(function()
if noclip then
game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
end
end)
plr = game.Players.LocalPlayer
mouse = plr:GetMouse()
mouse.KeyDown:connect(function(key)
 
if key == "v" then
noclip = not noclip
game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
end
end)
end)


local Tab = Window:NewTab("admin/commands")
local Section = Tab:NewSection("admin scripts")
Section:NewButton("Infinite Yield", "Launches Infinite Yield.", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source", true))()
end)
Section:NewButton("CMD-X", "Launches CMD-X.", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/CMD-X/CMD-X/master/Source", true))()
end)
Section:NewButton("Homebrew Admin", "Launches Homebrew Admin.", function()
loadstring(game:HttpGet(('https://raw.githubusercontent.com/mgamingpro/HomebrewAdmin/master/Main'),true))()
end)


 
