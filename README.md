
local ScreenGui = Instance.new("ScreenGui")
local main = Instance.new("ScrollingFrame")
local TextLabel = Instance.new("TextLabel")
local guiyield = Instance.new("TextButton")
local gui2 = Instance.new("TextButton")
local gui4 = Instance.new("TextButton")
local bloppaxd = Instance.new("TextButton")
local TextButton = Instance.new("TextButton")
local requirements = Instance.new("TextButton")
local idkhub = Instance.new("TextButton")
local fewizzard = Instance.new("TextButton")
local ImageLabel = Instance.new("ImageLabel")


ScreenGui.Parent = game.CoreGui

main.Name = "main"
main.Parent = ScreenGui
main.Active = true
main.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
main.Position = UDim2.new(0.245295525, 0, 0.350078434, 0)
main.Size = UDim2.new(0, 384, 0, 234)
main.Active = true
main.Draggable = true

TextLabel.Parent = main
TextLabel.BackgroundColor3 = Color3.fromRGB(77, 77, 77)
TextLabel.Size = UDim2.new(0, 271, 0, 50)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Bloppa FE Hub 5.1"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

guiyield.Name = "guiyield"
guiyield.Parent = main
guiyield.BackgroundColor3 = Color3.fromRGB(55, 111, 166)
guiyield.Position = UDim2.new(0, 0, 0.0368640125, 0)
guiyield.Size = UDim2.new(0, 127, 0, 25)
guiyield.Font = Enum.Font.SourceSans
guiyield.Text = "InfYield"
guiyield.TextColor3 = Color3.fromRGB(0, 0, 0)
guiyield.TextScaled = true
guiyield.TextSize = 14.000
guiyield.TextWrapped = true
guiyield.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'),true))()
end)


gui2.Name = "gui2"
gui2.Parent = main
gui2.BackgroundColor3 = Color3.fromRGB(55, 111, 166)
gui2.Position = UDim2.new(0.330606759, 0, 0.0362987295, 0)
gui2.Size = UDim2.new(0, 118, 0, 25)
gui2.Font = Enum.Font.SourceSans
gui2.Text = "Animal"
gui2.TextColor3 = Color3.fromRGB(0, 0, 0)
gui2.TextScaled = true
gui2.TextSize = 14.000
gui2.TextWrapped = true
gui2.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://cheatersoul.click/animalsimx1"))()
end)


gui4.Name = "gui4"
gui4.Parent = main
gui4.BackgroundColor3 = Color3.fromRGB(55, 111, 166)
gui4.Position = UDim2.new(0, 0, 0.0552511513, 0)
gui4.Size = UDim2.new(0, 127, 0, 25)
gui4.Font = Enum.Font.SourceSans
gui4.Text = "PrisonBreaker"
gui4.TextColor3 = Color3.fromRGB(0, 0, 0)
gui4.TextScaled = true
gui4.TextSize = 14.000
gui4.TextWrapped = true
gui4.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(('https://pastebin.com/QcNge4QY'),true))()
end)

bloppaxd.Name = "bloppaxd"
bloppaxd.Parent = main
bloppaxd.BackgroundColor3 = Color3.fromRGB(55, 111, 166)
bloppaxd.Position = UDim2.new(0, 0, 0.0735325292, 0)
bloppaxd.Size = UDim2.new(0, 127, 0, 25)
bloppaxd.Font = Enum.Font.SourceSans
bloppaxd.Text = "Floppa FE Script"
bloppaxd.TextColor3 = Color3.fromRGB(0, 0, 0)
bloppaxd.TextScaled = true
bloppaxd.TextSize = 14.000
bloppaxd.TextWrapped = true
bloppaxd.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(('https://raw.githubusercontent.com/selecteduseromg343/newfloppa455/main/README.md'),true))()
end)

TextButton.Parent = main
TextButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton.Position = UDim2.new(0.111969113, 0, 3.93100119, 0)
TextButton.Size = UDim2.new(0, 174, 0, 37)
TextButton.Font = Enum.Font.SourceSans
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextSize = 14.000

requirements.Name = "requirements"
requirements.Parent = main
requirements.BackgroundColor3 = Color3.fromRGB(55, 111, 166)
requirements.Position = UDim2.new(0.605514169, 0, 0.11343877, 0)
requirements.Size = UDim2.new(0, 127, 0, 35)
requirements.Font = Enum.Font.SourceSans
requirements.Text = "Click to see hat requirements for FE"
requirements.TextColor3 = Color3.fromRGB(0, 0, 0)
requirements.TextScaled = true
requirements.TextSize = 14.000
requirements.TextWrapped = true

idkhub.Name = "idkhub"
idkhub.Parent = main
idkhub.BackgroundColor3 = Color3.fromRGB(55, 111, 166)
idkhub.Position = UDim2.new(-0.00283414125, 0, 0.11349503, 0)
idkhub.Size = UDim2.new(0, 127, 0, 25)
idkhub.Font = Enum.Font.SourceSans
idkhub.Text = "Demonfall Hub"
idkhub.TextColor3 = Color3.fromRGB(0, 0, 0)
idkhub.TextScaled = true
idkhub.TextSize = 14.000
idkhub.TextWrapped = true
idkhub.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(('https://raw.githubusercontent.com/NOOBHUBX/DemonFall/main/NOOB%20HUB.Lua'),true))()
end)


fewizzard.Name = "fewizzard"
fewizzard.Parent = main
fewizzard.BackgroundColor3 = Color3.fromRGB(55, 111, 166)
fewizzard.Position = UDim2.new(-0.00283414125, 0, 0.0930994824, 0)
fewizzard.Size = UDim2.new(0, 127, 0, 25)
fewizzard.Font = Enum.Font.SourceSans
fewizzard.Text = "FE Wizzard"
fewizzard.TextColor3 = Color3.fromRGB(0, 0, 0)
fewizzard.TextScaled = true
fewizzard.TextSize = 14.000
fewizzard.TextWrapped = true
fewizzard.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(('https://raw.githubusercontent.com/selecteduseromg343/fewizzarder/main/README.md'),true))()
end)

ImageLabel.Parent = main
ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel.Position = UDim2.new(0.704475224, 0, -0.000478891219, 0)
ImageLabel.Size = UDim2.new(0, 99, 0, 70)
ImageLabel.Image = "http://www.roblox.com/asset/?id=10019452562"
