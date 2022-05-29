local DiscordLib = loadstring(game:HttpGet"https://raw.githubusercontent.com/dawid-scripts/UI-Libs/main/discord%20lib.txt")()

local win = DiscordLib:Window("Anything Hub")

local serv = win:Server("Bingus Hub", "http://www.roblox.com/asset/?id=9633780578")

local btns = serv:Channel("Bingus")

btns:Label("Welcome to bingus hub")

btns:Label("Pls go to any Tabs you like :)")

local btns = serv:Channel("Games1")

btns:Button("Noob Crushers", function()
loadstring(game:HttpGet("https://github.com/VxidHub/scripts/raw/main/8158394866.lua"))()
end)

btns:Button("Epic Minigames", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/SlamminPig/rblxgames/main/Epic%20Minigames/EpicMinigamesGUI"))()
end)

btns:Button("Bee Swarm Simulator", function()
shared.autoload = false -- change to profile name if you want to autoload (afking/autojoin). eg. shared.autoload = "profile"


loadstring(game:GetObjects("rbxassetid://4384103988")[0X1].Source)("Pepsi Swarm")
end)

local etns = serv:Channel("Games2")

etns:Button("arsenal", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/CriShoux/OwlHub/master/OwlHub.txt"))();
end)


etns:Button("Sword battles", function()
local function load(file,lib,win)
  local loaded = loadstring(game:HttpGet("https://raw.githubusercontent.com/TheLolik/sb-script/main/"..file..".lua"))()
  loaded:start(lib,win)
end

local lib = loadstring(game:HttpGet"https://raw.githubusercontent.com/TheLolik/vape-lite-update/main/lib.lua")()
local win = lib:Window("SB Script",Color3.fromRGB(44, 120, 224), Enum.KeyCode.RightControl)
load("misc",lib,win)
wait()
load("swords",lib,win)
wait()
load("players",lib,win)
wait()
load("other",lib,win)
end)

etns:Button("Bedwars", function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/joeengo/Future/main/loadstring.lua', true))()
end)

local serv = win:Server("120 Flags", "http://www.roblox.com/asset/?id=251068840")

local btns = serv:Channel("Main")

btns:Label("Welcome to 120 flags hub")

btns:Label("coming soon!")
