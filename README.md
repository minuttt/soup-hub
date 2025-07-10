IS THIS PUBLIC 
yes it is^
SCRIPT: 
local success, err = pcall(function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/minuttt/soup-hub/main/Main.lua", true))()
end)
if not success then
    warn("Error loading script: " .. err)
end
