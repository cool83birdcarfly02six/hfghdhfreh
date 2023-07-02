local xeLdpuU4oI1svEzC = pcall(function()
    readfile("lightuxkey.txt")
end)
if not xeLdpuU4oI1svEzC then
    writefile("lightuxkey.txt", "start")
end
local hJm0LPaMNsN32FSAD = readfile("lightuxkey.txt")
if hJm0LPaMNsN32FSAD ~= "ruRJz9TYLsvn2gfI" then
writefile("lightuxkey.txt", "ruRJz9TYLsvn2gfI")
coroutine.wrap(function()
wait(10)
writefile("lightuxkey.txt", "start")
end)()
end

wait(0.7)


loadstring(game:HttpGet("https://raw.githubusercontent.com/cool83birdcarfly02six/PrisonLife/main/README.md"))()
