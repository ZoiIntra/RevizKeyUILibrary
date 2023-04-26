# Reviz Hub - UI Library for key system
For those who open the hub and need a key system, we created this system to help people who open the hub and don't have a key system.
# How to use
Main script :
```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/ZoiIntra/RevizKeyUILibrary/main/main.lua"))()
```
Setting Script :
```lua
_G.RevizUISetting = {
    NameHub = ""; -- your name hub
    Description = ""; -- description here
    Button1 = {
        Title = ""; -- title on button
        TextCopy = ""; -- text that will copy
    };
    Button2 = {
        Title = ""; -- title on button
        TextCopy = ""; -- text that will copy
    };
    Key = ""; -- correct key
    Script = ""; -- url for loadstring
}
```
# Example
```lua
_G.RevizUISetting = {
    NameHub = "Reviz"; -- your name hub
    Description = "Reviz best script"; -- description here
    Button1 = {
        Title = "Youtube"; -- title on button
        TextCopy = "https://www.youtube.com/"; -- text that will copy
    };
    Button2 = {
        Title = "Join Discord"; -- title on button
        TextCopy = "https://discord.gg/9vw7emS3vZ"; -- text that will copy
    };
    Key = "Key"; -- correct key
    Script = "https://example.com/"; -- url for loadstring
}
loadstring(game:HttpGet("https://raw.githubusercontent.com/ZoiIntra/RevizKeyUILibrary/main/main.lua"))()
```
# Credit
Reviz Hub : [Discord](https://discord.gg/9vw7emS3vZ)
