local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("14PRO HUB x หมวกกันน็อคแมน  -  Last City", "DarkTheme")
local Tab = Window:NewTab("Dupe")
local Section = Tab:NewSection("Function")

Section:NewToggle("เสกเงิน (Dupe Money)", "", function(state)
    if state then
        _G.H = true
while _G.H do wait()
wait(0.1)

local item = "Money" --ชื่อของ
local val = 1000000   --จำนวน

local args = {
    [1] = item,
    [2] = -val
}

game:GetService("ReplicatedStorage").Remote.Gacha:InvokeServer(unpack(args))

end
    else
        _G.H = false
while _G.H do wait()
wait(0.1)

local item = "Money" --ชื่อของ
local val = 1000000   --จำนวน

local args = {
    [1] = item,
    [2] = -val
}

game:GetService("ReplicatedStorage").Remote.Gacha:InvokeServer(unpack(args))

end
    end
end)



Section:NewToggle("เสกกาชา (Dupe Gacha)", "", function(state)
    if state then
        _G.H = true
while _G.H do wait()
wait(0.1)

local item = "Support Gacha" --ชื่อของ
local val = 1000  --จำนวน

local args = {
    [1] = item,
    [2] = -val
}

game:GetService("ReplicatedStorage").Remote.Gacha:InvokeServer(unpack(args))

end
    else
        _G.H = false
while _G.H do wait()
wait(0.1)

local item = "Support Gacha" --ชื่อของ
local val = 1000  --จำนวน

local args = {
    [1] = item,
    [2] = -val
}

game:GetService("ReplicatedStorage").Remote.Gacha:InvokeServer(unpack(args))

end
    end
end)
