getgenv().Setting = {
    ["Hunt"] = {
        ["Team"] = "Pirates",
        ["Min"] = 0,
        ["Max"] = 30000000,
    },
    ["Webhook"] = {
        ["Enabled"] = false, -- set true/halse
        ["Url"] = "Your link webhook"
    },
    ["Skip"] = {
        ["V4"] = true,
        ["Fruit"] = true,
        ["FruitList"] = {
            "Leopard",
            "Venom",
            "Dough",
            "Portal"
        }
    },
    ["Chat"] = {
        ["Enabled"] = false,
        ["List"] = {""},
    },
    ["Click"] = {
        ["AlwaysClick"] = true,
        ["FastClick"] = false
    },
    ["Another"] = {
        ["V3"] = true,
        ["CustomHealth"] = true,
        ["Health"] = 12000,
        ["V4"] = true,
        ["LockCamera"] = false,
        ["FPSBoots"] = false,
        ["WhiteScreen"] = false,
        ["BypassTp"] = true
    },
    ["SafeHealth"] = {
        ["Health"] = 6000,
        ["HighY"] = 1500
    },
    ["Melee"] = {
        ["Enable"] = true,
        ["Delay"] = 2.5,
        ["Z"] = {["Enable"] = true, ["HoldTime"] = 1.25},
        ["X"] = {["Enable"] = true, ["HoldTime"] = 1},
        ["C"] = {["Enable"] = true, ["HoldTime"] = 1},
        ["V"] = {["Enable"] = false, ["HoldTime"] = 0}
    },
    ["Fruit"] = {
        ["Enable"] = false,
        ["Delay"] = 2,
        ["Z"] = {["Enable"] = true, ["HoldTime"] = 1,5},
        ["X"] = {["Enable"] = true, ["HoldTime"] = 1},
        ["C"] = {["Enable"] = true, ["HoldTime"] = 1},
        ["V"] = {["Enable"] = false, ["HoldTime"] = 1.25},
        ["F"] = {["Enable"] = true, ["HoldTime"] = 1,25}
    },
    ["Sword"] = {
        ["Enable"] = true,
        ["Delay"] = 1,
        ["Z"] = {["Enable"] = true, ["HoldTime"] = 1},
        ["X"] = {["Enable"] = true, ["HoldTime"] = 1}
    },
    ["Gun"] = {
        ["Enable"] = false,
        ["GunMode"] = false, 
        ["Delay"] = 1.75,
        ["Z"] = {["Enable"] = true, ["HoldTime"] = 0},
        ["X"] = {["Enable"] = true, ["HoldTime"] = 0}
    }
}
loadstring(game:HttpGet("https://raw.githubusercontent.com/vuquocoai123/lua/main/LoaderBounty.lua"))()
