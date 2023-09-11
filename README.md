# Linona-UI-Lib
### Linona UI for Script Hub
![Screenshot 2023-09-11 133040](https://github.com/3345-c-a-t-s-u-s/Linona-UI-Lib/assets/117000269/08f9887d-62e3-4c23-a063-7a50a921cdf5)

## Example Code
```lua
local LIB = loadstring(game:HttpGet("https"))()

local Window = LIB:NewWindow("HELLO")

local HOME = Window:NewTab("HOME")
local MISC = Window:NewTab("MISC")

HOME:NewSection("Section 1")

HOME:NewLabel("This is Label","right"):Position("center") -- right : left : center

HOME:NewToggle("This is Toggle",false,function()
	
end)

HOME:NewButton("This is Button",function()
	Window:Notify("Notifications"..tostring(math.random(0,10)),2)
end)

HOME:NewTextBox("This is TextBox","Send",function()
	
end)

HOME:NewSlider("This is Slider",1,1000,function()
	
end)


HOME:NewKeybind("This is Keybinid",Enum.KeyCode.A,function()
	
end)

HOME:NewDropdown("This is Dropdown",{1,2,3},function()
	
end)
```
