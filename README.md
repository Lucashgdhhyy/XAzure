local ArrayField = loadstring(game:HttpGet("https://raw.githubusercontent.com/Hosvile/Refinement/main/MC%3AArrayfield%20Library"))()
ArrayField:Destroy()
local ArrayField = loadstring(game:HttpGet("https://raw.githubusercontent.com/Hosvile/Refinement/main/MC%3AArrayfield%20Library"))()
--Documentation url: https://docs.sirius.menu/community/arrayfield

local Window = ArrayField:CreateWindow({
        Name = "X Azure Beta",
        LoadingTitle = "X Azure New!",
        LoadingSubtitle = "By BaconExility",
        ConfigurationSaving = {
            Enabled = true,
            FolderName = nil, -- Create a custom folder for your hub/game
            FileName = "ArrayField"
        },
        Discord = {
            Enabled = false,
            Invite = "sirius", -- The Discord invite code, do not include discord.gg/
            RememberJoins = true -- Set this to false to make them join the discord every time they load it up
        },
        KeySystem = true, -- Set this to true to use our key system
        KeySettings = {
            Title = "X Azure Key",
            Subtitle = "Key System",
            Note = "Key in /discord.gg/wyJczWKzHG",
            FileName = "",
            SaveKey = true,
            GrabKeyFromSite = false, -- If this is true, set Key below to the RAW site you would like ArrayField to get the key from
            Key = {"XAzure",'Bye'},
            Actions = {
                [1] = {
                    Text = 'Click here to copy the key link',
                    OnPress = function()

                    end,
                }
            },
        }
    })


local Tab = Window:CreateTab("Main", 4483362458) -- Title, Image

ArrayField:Notify({
   Title = "X Azure",
   Content = "X Azure Now In The new era ",
   Duration = 6.5,	
   Image = 4483362458,
   Actions = { -- Notification Buttons
      Ignore = {
         Name = "Okay!",
         Callback = function()
         print("The user tapped Okay!")
      end
   },
 },
})


local Section = Tab:CreateSection("Wait 4 Seconds for load all",false)

local Tab = Window:CreateTab("Blox Fruit", 4483362458) -- Title, Image

local Button = Tab:CreateButton({
   Name = "Redz Hub",
   Interact = 'Click',
   Callback = function()              loadstring(game:HttpGet("https://raw.githubusercontent.com/REDzHUB/BloxFruits/main/redz9999"))()
   end,
})

local Tab = Window:CreateTab("Pet Simulator 99", 4483362458) -- Title, Image

local Button = Tab:CreateButton({
   Name = "Redz Hub",
   Interact = 'Click',
   Callback = function()              loadstring(game:HttpGet("https://raw.githubusercontent.com/REDzHUB/PetSimulator99/main/redz9999.lua"))()
   end,
})

local Tab = Window:CreateTab("Blade Ball", 4483362458) -- Title, Image

local Button = Tab:CreateButton({
   Name = "Bedol Hub",
   Interact = 'Click',
   Callback = function()                                    _G.UI_Size = 200 -- config ui size
loadstring(game:HttpGet("https://raw.githubusercontent.com/3345-c-a-t-s-u-s/-beta-/main/AutoParry.lua"))()
   end,
})

local Tab = Window:CreateTab("Muncher Master", 4483362458) -- Title, Image

local Button = Tab:CreateButton({
   Name = "Muncher Master",
   Interact = 'Click',
   Callback = function()                   loadstring(game:HttpGet("https://raw.githubusercontent.com/Lucashgdhhyy/Muncj/main/README.md"))()   
   -- The function that takes place when the button is pressed
   end,
})

local Tab = Window:CreateTab("Cmds Admin", 4483362458) -- Title, Image

local Button = Tab:CreateButton({
   Name = "Infinity Yield",
   Interact = 'Click',
   Callback = function()               loadstring(game:HttpGet(('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'),true))()
   -- The function that takes place when the button is pressed
   end,
})
