

local Rayfield = loadstring(game:HttpGet('https://raw.githubusercontent.com/shlexware/Rayfield/main/source'))()
local Window = Rayfield:CreateWindow({
    Name = "Birdhub",
    LoadingTitle = "Birdhub",
    LoadingSubtitle = "by Trem2goated",
    ConfigurationSaving = {
       Enabled = false,
       FolderName = nil, -- Create a custom folder for your hub/game
       FileName = "Bird Hub"
    },
    Discord = {
       Enabled = false,
       Invite = "noinvitelink", -- The Discord invite code, do not include discord.gg/. E.g. discord.gg/ABCD would be ABCD.
       RememberJoins = true -- Set this to false to make them join the discord every time they load it up
    },
    KeySystem = true, -- Set this to true to use our key system
    KeySettings = {
       Title = "Birdhub",
       Subtitle = "Made by Trem2goated",
       Note = "Join discord for key",
       FileName = "SiriusKey",
       SaveKey = false,
       GrabKeyFromSite = false, -- If this is true, set Key below to the RAW site you would like Rayfield to get the key from
       Key = "0jd99902kkd0023321112334"
    }
 })
--GAMES SUPPORTED
 local Tab = Window:CreateTab("Game supported", 4483362458) -- Title, Image
 local Section = Tab:CreateSection("Games we support")



local Button = Tab:CreateButton({
   Name = "LT2 SCRIPT",
   Callback = function()
      loadstring(game:HttpGet("https://pastebin.com/raw/rymJtRNa", true))()
   end,
})


 local Button = Tab:CreateButton({
    Name = "JAILBREAK SCRIPT",
    Callback = function()
       loadstring(game:HttpGet('https://pastebin.com/raw/sT8E7s6g'))()
    end,
 })

 local Button = Tab:CreateButton({
    Name = "Arsenal SCRIPT BASIC",
    Callback = function()
       loadstring(game:HttpGet('https://pastebin.com/raw/vkGcrU5R'))()
    end,
 })

 local Button = Tab:CreateButton({
   Name = "Phantom Forces SCRIPT",
   Callback = function()
      loadstring(game:HttpGet('https://raw.githubusercontent.com/trem009932/Phantom-Forces-hack/main/README.md'))()
   end,
})

 local Button = Tab:CreateButton({
   Name = "Work at a pizza place SCRIPT",
   Callback = function()
      loadstring(game:HttpGet("https://pastebin.com/raw/91kFCFPq", true))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Tapping Legends X SCRIPT",
   Callback = function()
      loadstring(game:HttpGet("https://pastebin.com/raw/mVVu5s03", true))()
   end,
})



 --NOTES

 local Tab = Window:CreateTab("Read Before u use", 4483362458) -- Title, Image
 local Section = Tab:CreateSection("Read Before u use")

 local Label = Tab:CreateLabel("GUIS status")
 local Label = Tab:CreateLabel("LT2 Dupe Script safe to use")
 local Label = Tab:CreateLabel("LT2 Script safe to use")
 local Label = Tab:CreateLabel("JAILBREAK SCRIPT safe to use")
 local Label = Tab:CreateLabel("Arsenal SCRIPT BASIC use at your own risk")
 local Label = Tab:CreateLabel("Phantom Forces SCRIPT not safe to use on main acc")
 local Label = Tab:CreateLabel("Work at a pizza place SCRIPT safe to use")
 local Label = Tab:CreateLabel("Tapping Legends X SCRIPT safe to use")


