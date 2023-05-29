
-- init
local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/GreenDeno/Venyx-UI-Library/main/source.lua"))()
local venyx = library.new("The mimic script by TTJY", 5013109572)

-- themes
local themes = {
	Background = Color3.fromRGB(24, 24, 24),
	Glow = Color3.fromRGB(0, 0, 0),
	Accent = Color3.fromRGB(10, 10, 10),
	LightContrast = Color3.fromRGB(20, 20, 20),
	DarkContrast = Color3.fromRGB(14, 14, 14),  
	TextColor = Color3.fromRGB(255, 255, 255)
}

-- first page
local page = venyx:addPage("Teleport Game", 5012544693)
local section1 = page:addSection("GAY")

section1:addToggle("COMMING SOON", nil, function(value)
	print("Toggled", value)
end)
section1:addButton("COMMING SOON", function()
	print("Clicked")
end)
section1:addTextbox("Notification", "Default", function(value, focusLost)
	print("Input", value)

	if focusLost then
		venyx:Notify("Title", value)
	end
end)

local page = venyx:addPage("JIGOKU", 5012544693)
local section1 = page:addSection("JIGOKU EVENT")
section1:addButton("Teleport to red guy", function()
	if workspace:FindFirstChild("IdleNPC") then
	venyx:Notify("FOUND", value)
	for i, v in pairs(Workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart")  then
	game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(310.32,3.23,323.65)
        wait(0.3)
        fireproximityprompt(v)
    end
end
else
venyx:Notify("NOT FOUND", value)
	end
end)

section1:addButton("Auto Win", function()
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(607.54,11.91,1080)
        task.wait(11)
for i, v in pairs(Workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart")  then
game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
        wait(0.3)
        fireproximityprompt(v)
    end
end
end)

local page = venyx:addPage("Chapter 1", 5012544693)
local section1 = page:addSection("ALL IN ONE")
section1:addButton("Auto Win", function()
	if game.PlaceId == 6296321810 or game.PlaceId == 6479231833 then
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3507,37.65,-1539.45)
	elseif  game.PlaceId == 6301638949 or game.PlaceId == 6480994221 then
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1274.95,199.54,-2537.93)
	else
	venyx:Notify("THIS IS FOR CHAPTER 1 BRUH", value)
	end
end)
local page = venyx:addPage("Chapter 2", 5012544693)
local section1 = page:addSection("ALL IN ONE")
section1:addButton("Auto Win", function()
	if game.PlaceId == 6373539583 or game.PlaceId == 6485055338 then
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(64.88,55.28,-1590)
	elseif  game.PlaceId == 6406571212 or game.PlaceId == 6485055836 then
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(235.17,101.94,-590)
	elseif  game.PlaceId == 6425178683 or game.PlaceId == 6485056556 then
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(829.97,72.49,-353.46)
	else
	venyx:Notify("THIS IS FOR CHAPTER 2 BRUH", value)
	end
end)

local page = venyx:addPage("Chapter 3", 5012544693)
local section1 = page:addSection("ALL IN ONE")
section1:addButton("Auto Win", function()
	if game.PlaceId == 6472459099 or game.PlaceId == 6688734180 then
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(2411.93,-23.03,2300)
	elseif  game.PlaceId == 6682163754 or game.PlaceId == 6688734313 then
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(245.69,31.72,450)
	elseif  game.PlaceId == 6682164423 or game.PlaceId == 6688734395 then
	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-651,648.99,-1014.35)
      	task.wait(5)
      	game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-644.07,947.82,-1490)
	else
	venyx:Notify("THIS IS FOR CHAPTER 3 BRUH", value)
	end
end)

local page = venyx:addPage("Chapter 4", 5012544693)
local section1 = page:addSection("Map1")
section1:addButton("Auto Win", function()
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(91,-48.35,-1416.24)
end)
local section2 = page:addSection("Map2")
section2:addButton("Auto Win", function()
	for i, v in pairs(Workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Name == "Butterfly" then
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
        wait(0.5)
        fireproximityprompt(v)
    end
end
end)
local section3 = page:addSection("Map3")
section3:addButton("Auto Win", function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(665.63,18.17,2108.62)
task.wait(0.3)
for i, v in pairs(Workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart")  then
        fireproximityprompt(v)
    end
end
task.wait()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(620.22,17.87,2340.73)
task.wait(0.3)
for i, v in pairs(Workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart")  then
        fireproximityprompt(v)
    end
end
task.wait()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(756.75,16.39,2538.24)
task.wait(0.3)
for i, v in pairs(Workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart")  then
        fireproximityprompt(v)
    end
end
task.wait()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(860.18,24.85,2548.28)
task.wait(0.3)
for i, v in pairs(Workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart")  then
        fireproximityprompt(v)
    end
end
task.wait()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(855.96,15.47,2388.36)
task.wait(0.3)
for i, v in pairs(Workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart")  then
        fireproximityprompt(v)
    end
end
task.wait()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(836.29,19.01,2247.34)
task.wait(0.3)
for i, v in pairs(Workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart")  then
        fireproximityprompt(v)
    end
end
task.wait()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(688.41,28.37,2251.57)
task.wait(0.3)
for i, v in pairs(Workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart")  then
        fireproximityprompt(v)
        fireproximityprompt(v)
        fireproximityprompt(v)
        fireproximityprompt(v)
        fireproximityprompt(v)
        fireproximityprompt(v)
    end
end
end)

local page = venyx:addPage("book2 chapter1", 5012544693)
local section1 = page:addSection("Use KtollT until i update")
section1:addButton("gay execute KtollT", function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/KTollT/KTollT/main/README.md'))()
end)	
local page = venyx:addPage("book2 chapter2", 5012544693)
local section1 = page:addSection("what?")
section1:addButton("uh wait let me update u nig", function()
	
end)	



















-- second page
local theme = venyx:addPage("Theme", 5012544693)
local colors = theme:addSection("Colors")

for theme, color in pairs(themes) do -- all in one theme changer, i know, im cool
	colors:addColorPicker(theme, color, function(color3)
		venyx:setTheme(theme, color3)
	end)
end

-- load
venyx:SelectPage(venyx.pages[1], true)
