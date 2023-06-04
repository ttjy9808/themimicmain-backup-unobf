if game.CoreGui:FindFirstChild("TTJY X POOM HUB X CAT SUS X KTOLLT BETA") then
local ddddddddestroy = game.CoreGui["TTJY X POOM HUB X CAT SUS X KTOLLT BETA"]
ddddddddestroy:Destroy()
end
task.wait()
-- init
local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/GreenDeno/Venyx-UI-Library/main/source.lua"))()
local venyx = library.new("TTJY X POOM HUB X CAT SUS X KTOLLT BETA", 5013109572)

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
local section1 = page:addSection("Start")
section1:addButton("Auto win", function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(252.78,1000,-73.17)
local player = game.Players.LocalPlayer.Character.HumanoidRootPart

  for _, v in pairs(game.Workspace:GetDescendants()) do
                   if v:IsA("TouchTransmitter") or v:IsA("TouchInterest") then
                       firetouchinterest(game.Players.LocalPlayer.Character.HumanoidRootPart or game.Players.LocalPlayer.Character.Torso, v:FindFirstAncestorWhichIsA("Part"),0)
                   end
               end
task.wait()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(252.78,1000,-73.17)
task.wait()
local tweenService = game:GetService("TweenService")
local tweenInfo = TweenInfo.new(30, Enum.EasingStyle.Linear)

local tween = tweenService:Create(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart, tweenInfo, {CFrame = CFrame.new(-550, 30, -87.29)})
tween:Play()
end)
local section2 = page:addSection("someone eat meat")
section2:addButton("Auto win", function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-3953.17,594.22,317.07)
		task.wait(1)
		for i, v in pairs(Workspace:GetDescendants()) do
    	if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "TeleportDoor" then
    	wait(0.3)
        fireproximityprompt(v)
    end
end
venyx:Notify("error02", "report this to ttjy")
end)
local section3 = page:addSection("Meat")
section3:addButton("Talk", function()
venyx:Notify("error03", "report this to ttjy")
local TalkDebounce = false
local Client = game.Players.LocalPlayer
local VirtualUser = game:GetService("VirtualUser")
if not TalkDebounce then 
        if Client.Character then 
            if Client.Character:FindFirstChild('HumanoidRootPart') then 
                TalkDebounce = true
                Client.Character:FindFirstChild('HumanoidRootPart').CFrame = CFrame.new(-4443, 711, 1164)
                task.wait(0.28)
                for Index, v in ipairs(game:GetService("Workspace"):GetDescendants()) do 
                    if v.Name == "NoppeNPC" then 
                        local Prompt = v.RootPart:FindFirstChildOfClass('ProximityPrompt')
                        fireproximityprompt(Prompt, 1)
                    end 
                end 
                for i = 1,100 do 
                    VirtualUser:ClickButton1(Vector2.new(500,0))
                    task.wait(0.001)
                end 
                TalkDebounce = false
            end 
        end 
    end
end)





local section4 = page:addSection("Auto Meat")
section4:addButton("Auto win", function()
if game.Players.LocalPlayer.PlayerGui["00_Marker"].Markers:FindFirstChild("Frame") then
for Index, v in ipairs(game:GetService('Workspace'):GetDescendants()) do 
    if v.Name == "DoorTele" then
        local Pivot = v.WorldPivot 
        game:GetService('Players').LocalPlayer.Character:FindFirstChild('HumanoidRootPart').CFrame = Pivot
    end
end
task.wait()
for i, v in pairs(Workspace:GetDescendants()) do
    	if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "DoorTele" then
    	wait(0.3)
        fireproximityprompt(v)
    end
end
else
local success = 0
local successbowl = 0
task.wait()
for i, v in ipairs(Workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Parent.Name == "RestaurantRoom" and successbowl == 0 and v.Parent.Parent.Name == "BowlGiver" then
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
        wait(0.3)
        fireproximityprompt(v)
        task.wait()
        successbowl = successbowl + 1
    end
end
task.wait()
for i, v in ipairs(Workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and success < 6 and v.Parent.Parent.Parent.Name == "RestaurantRoom" and v.Parent.Transparency == 0 then
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
        wait(0.3)
        fireproximityprompt(v)
        success = success + 1
    end
end
venyx:Notify("DONT TALK,wait 10 second", value)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-4443.11,711.37,1163.78)
task.wait(10)
venyx:Notify("NOW TALK", value)
end
end)







local section5 = page:addSection("RUN")
section5:addButton("ENTER ZONE", function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-4590,843.64,-35.54)
end)
section5:addButton("AUTO RUN", function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-5364,900,29.63)
task.wait(5)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-5364,682.12,29.63)
end)
section5:addButton("FULL AUTO WIN", function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-4590,843.64,-35.54)
task.wait(10)
local tweenService = game:GetService("TweenService")
local tweenInfo = TweenInfo.new(5, Enum.EasingStyle.Linear)

local tween = tweenService:Create(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart, tweenInfo, {CFrame = CFrame.new(-5364,682.12,29.63)})
tween:Play()
end)

local section6 = page:addSection("LEVER")
section6:addButton("ENTER ZONE", function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-11035,-81.4,-12.56)
end)

section6:addButton("AUTO LEVER", function()
for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Name == "Lever" then
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
        wait(0.3)
        fireproximityprompt(v)
    end
end

		task.wait(6)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-10060,484.1,-9.52)
end)

section6:addButton("FULL AUTO WIN", function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-11035,-81.4,-12.56)
task.wait(5)
for i, v in pairs(workspace:GetDescendants()) do
    if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Name == "Lever" then
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
        wait(0.3)
        fireproximityprompt(v)
    end
end

		task.wait(6)
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-10060,484.1,-9.52)
end)

local section7 = page:addSection("SKIP NUMBER PUZZLE")
section7:addButton("teleport", function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2005.8,968.25,-4909.48)
end)

local section7point1 = page:addSection("COOK")
section7point1:addButton("AUTO COOK EYEBALL", function()
for _, v in pairs(Workspace:GetDescendants()) do -- eyeball
    if v.Parent:IsA("BasePart") and v:IsA("ProximityPrompt") and v.Parent.Parent.Name == "Bowl" then
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
        wait(0.3)
        fireproximityprompt(v)
    end
end

wait(0.5)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2741.79, 968.25, -4906.07)

for _, v in pairs(Workspace:GetDescendants()) do
    if v.Parent:IsA("BasePart") and v:IsA("ProximityPrompt") and v.Parent.Parent.Name == "WoodenCounter" then
        wait(2)
        fireproximityprompt(v)
        task.wait(1)

        for _, e in pairs(Workspace:GetDescendants()) do
            if e.Parent:IsA("BasePart") and e:IsA("ProximityPrompt") and e.Parent.Parent.Name == "Eyeball" and e.Parent.Parent:IsA("Model") then
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = e.Parent.CFrame
                wait(0.3)
                fireproximityprompt(e)
                task.wait(0.5)
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2741.79, 968.25, -4906.07)

                for _, j in pairs(Workspace:GetDescendants()) do
                    if j.Parent:IsA("BasePart") and j:IsA("ProximityPrompt") and j.Parent.Parent.Name == "WoodenCounter" then
                        wait(1)
                        fireproximityprompt(j)
                        task.wait(2)

                        for _, q in pairs(Workspace:GetDescendants()) do
                            if q.Parent:IsA("BasePart") and q:IsA("ProximityPrompt") and q.Parent.Parent.Name == "Spaghetti" and q.Parent.Parent:IsA("Model") then
                                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = q.Parent.CFrame
                                wait(0.3)
                                fireproximityprompt(q)
                                task.wait(0.5)
                                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-2741.79, 968.25, -4906.07)

                                for _, l in pairs(Workspace:GetDescendants()) do
                                    if l.Parent:IsA("BasePart") and l:IsA("ProximityPrompt") and l.Parent.Parent.Name == "WoodenCounter" then
                                        wait(2)
                                        fireproximityprompt(l)
                                        task.wait(1)
                                    end
                                end
                                break
                            end
                        end
                        break
                    end
                end
                break
            end
        end
        break
    end
end
end)

local section7point5 = page:addSection("AFTER COOK")
section7point5:addButton("Auto Run", function()
local tweenService = game:GetService("TweenService")
local tweenInfo = TweenInfo.new(3, Enum.EasingStyle.Linear)

local tween = tweenService:Create(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart, tweenInfo, {CFrame = CFrame.new(-3345.78,1205,-6794.84)})
tween:Play()
venyx:Notify("Wait For Time", value)
task.wait(4)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-3347.32,1205,-6824)
end)

local section8 = page:addSection("CURSED ZONE")
section8:addButton("Auto win cursed zone1", function()
local tweenService = game:GetService("TweenService")
local tweenInfo = TweenInfo.new(3, Enum.EasingStyle.Linear)

local tween = tweenService:Create(game:GetService("Players").LocalPlayer.Character.HumanoidRootPart, tweenInfo, {CFrame = CFrame.new(-4250.71,613.7,-968.13)})
tween:Play()
end)
section8:addButton("TELEPORT TO CURSED ZONE 2", function()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-4079.71,613.7,-968.13)
end)
section8:addButton("Remove monster(singleplayer)", function()
for i, v in pairs(workspace:GetDescendants()) do
            if v.Parent:IsA("BasePart") and v.Parent.Name == "GAMESTART" then
                v:Destroy()
            end
        end
end)

section8:addDropdown("Select hide spot", {"Hide Spot1", "Hide Spot2", "Hide Spot3"}, function(hide)
	gaysexhod = hide
end)
section8:addButton("Hide", function(hide)
	if gaysexhod == "Hide Spot1" then
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-4066.81,630.67,-985.54)
		elseif gaysexhod == "Hide Spot2" then
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-4053.62,666.31,-951.76)
		elseif gaysexhod == "Hide Spot3" then
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-4088.17,743.82,-959.96)
		else
		venyx:Notify("", "Select one")
	end
end)

local section9 = page:addSection("KID")
section9:addButton("Click this first", function()
for i,v in pairs(workspace:GetDescendants()) do
  		if v.Name == "SquidGames" then
     	v:Destroy()
     	end
	end
end)
section9:addButton("Auto find kid", function()
for i,v in pairs(workspace:GetDescendants()) do
  if v:IsA("BasePart") and v.Name == "IndicatorPic" then
     game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = v.CFrame
     end
end
end)
section9:addButton("Teleport to Gate", function()
for i,v in pairs(workspace:GetDescendants()) do
  if v:IsA("BasePart") and v.Name == "Formation" then
     game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = v.CFrame
     end
end
end)
section9:addButton("Auto Get Notes", function()
for i, v in pairs(workspace:GetDescendants()) do
            if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Name == "Note" then
                game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
                wait(0.3)
                fireproximityprompt(v)
            end
        end
end)

local section10 = page:addSection("Nagisa")
section10:addButton("Anti Nagisa laser", function()
while true do
		for i, v in pairs(workspace:GetDescendants()) do
            if v.Name == "POISON" then
local distance = 100

while true do
	localplayer = game.Players.LocalPlayer 
 	Char = localplayer.Character or workspace:FindFirstChild(localplayer.Name)
         HRP = Char and Char:FindFirstChild("HumanoidRootPart")
        if not Char or not HRP then
           
        end
         p = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
         hrd = game.Players.LocalPlayer.Character.HumanoidRootPart
         py = game.Players.LocalPlayer.Character.HumanoidRootPart.Position.y
         
    local character = game.Players.LocalPlayer.Character
    local position = v and v.Position or nil
    currentPos = Vector3.new(p.x, 100, p.z)
    if position and (position - character.HumanoidRootPart.Position).Magnitude <= distance then
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1982.58,100,-4780.12)
    end
    
    wait(0.1)
end
end
	end
	end
end)

section10:addButton("Auto Get cannon ball", function()
while task.wait() do
		for i, v in pairs(workspace:GetDescendants()) do
            if v:IsA("ProximityPrompt") and v.Parent:IsA("BasePart") and v.Parent.Parent.Name == "BallGiver" and game.Players.LocalPlayer.PlayerGui.BossFight.Ammo.Text == "0" then
                game:GetService("Players").LocalPlayer.Character.HumanoidRootPart.CFrame = v.Parent.CFrame
                wait(0.3)
                fireproximityprompt(v)
                fireproximityprompt(v)
                fireproximityprompt(v)
                fireproximityprompt(v)
                fireproximityprompt(v)
                task.wait()
            end
end
	end
end)

local section11 = page:addSection("Nagisa Serpent")
section11:addButton("COMMING SOON", function()

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
