local KeySystemUI = loadstring(game:HttpGet("https://raw.githubusercontent.com/MaGiXxScripter0/keysystemv2api/master/ui/xrer_mstudio45.lua"))()
KeySystemUI.New({
    ApplicationName = "Marhub", -- Your Key System Application Name
    Name = "Steal a Brainrot script", -- Your Script name
    Info = "This script is free but have premium functions buy for 7 eur", -- Info text in the GUI, keep empty for default text.
    DiscordInvite = "YtM3r32rhA" -- Optional.
})
repeat task.wait() until KeySystemUI.Finished() or KeySystemUI.Closed
if KeySystemUI.Finished() and KeySystemUI.Closed == false then

  loadstring(game:HttpGet("https://raw.githubusercontent.com/Youifpg/Steal-a-Brianrot/refs/heads/main/ArbixHubV4.lua"))()

else
    game.Players.LocalPlayer:kick("Compra la key a marchoso")
end
