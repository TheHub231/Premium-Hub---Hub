-- Premium Hub:

local ScreenGui = Instance.new("ScreenGui")
local main = Instance.new("ImageLabel")
local ImageLabel = Instance.new("ImageLabel")
local TextLabel = Instance.new("TextLabel")
local Close = Instance.new("TextButton")
local Frame = Instance.new("ImageLabel")
local open_Roundify_12px = Instance.new("ImageLabel")
local IF = Instance.new("TextButton")
local TextLabel_2 = Instance.new("TextLabel")
local TextLabel_3 = Instance.new("TextLabel")
local open_Roundify_12px_2 = Instance.new("ImageLabel")
local GHH = Instance.new("TextButton")
local WL = Instance.new("TextButton")
local PBX = Instance.new("TextButton")
local open_Roundify_12px_3 = Instance.new("ImageLabel")
local open_Roundify_12px_4 = Instance.new("ImageLabel")
local TextLabel_4 = Instance.new("TextLabel")
local TextLabel_5 = Instance.new("TextLabel")
local SB = Instance.new("TextButton")
local Clear = Instance.new("TextButton")
local open_Roundify_12px_5 = Instance.new("ImageLabel")
local open_Roundify_12px_6 = Instance.new("ImageLabel")
local TextLabel_6 = Instance.new("TextLabel")
local TextLabel_7 = Instance.new("TextLabel")
local open_Roundify_12px_7 = Instance.new("ImageLabel")
local CB = Instance.new("TextButton")
local Code = Instance.new("TextBox")
local TextLabel_8 = Instance.new("TextLabel")
local TextLabel_9 = Instance.new("TextLabel")
local TextLabel_10 = Instance.new("TextLabel")
local TextLabel_11 = Instance.new("TextLabel")
local TextLabel_12 = Instance.new("TextLabel")
local TextLabel_13 = Instance.new("TextLabel")
local TextLabel_14 = Instance.new("TextLabel")
local openmain = Instance.new("ImageLabel")
local open_Roundify_12px_8 = Instance.new("ImageLabel")
local TextLabel_15 = Instance.new("TextLabel")
local Close_2 = Instance.new("TextButton")
local open = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.CoreGui

main.Name = "main"
main.Parent = ScreenGui
main.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
main.BackgroundTransparency = 1.000
main.Position = UDim2.new(0.132435858, 0, 0.207357854, 0)
main.Size = UDim2.new(0, 711, 0, 445)
main.Visible = false
main.Image = "rbxassetid://3570695787"
main.ImageColor3 = Color3.fromRGB(45, 45, 45)
main.ScaleType = Enum.ScaleType.Slice
main.SliceCenter = Rect.new(100, 100, 100, 100)
main.SliceScale = 0.120
main.Active = true
main.Draggable = true

ImageLabel.Parent = main
ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel.Position = UDim2.new(0.0108505227, 0, 0.120980255, 0)
ImageLabel.Size = UDim2.new(0, 696, 0, 379)
ImageLabel.Image = "rbxassetid://5622147406"

TextLabel.Parent = main
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.Position = UDim2.new(-0.000401228666, 0, 0.0153622627, 0)
TextLabel.Size = UDim2.new(0, 204, 0, 40)
TextLabel.Font = Enum.Font.ArialBold
TextLabel.Text = "Premium Hub"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 25.000
TextLabel.TextWrapped = true

Close.Name = "Close"
Close.Parent = main
Close.BackgroundColor3 = Color3.fromRGB(236, 236, 236)
Close.BackgroundTransparency = 1.000
Close.BorderSizePixel = 0
Close.Position = UDim2.new(0.936746895, 0, 0.0215013828, 0)
Close.Size = UDim2.new(0, 37, 0, 33)
Close.Font = Enum.Font.Arial
Close.Text = "X"
Close.TextColor3 = Color3.fromRGB(255, 255, 255)
Close.TextScaled = true
Close.TextSize = 14.000
Close.TextWrapped = true
Close.MouseButton1Down:connect(function()
main.Visible = false
end)

Frame.Name = "Frame"
Frame.Parent = main
Frame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame.BackgroundTransparency = 1.000
Frame.Position = UDim2.new(0.0717299581, 0, 0.146067411, 0)
Frame.Size = UDim2.new(0, 609, 0, 356)
Frame.Image = "rbxassetid://3570695787"
Frame.ImageColor3 = Color3.fromRGB(45, 45, 45)
Frame.ScaleType = Enum.ScaleType.Slice
Frame.SliceCenter = Rect.new(100, 100, 100, 100)
Frame.SliceScale = 0.120

open_Roundify_12px.Name = "open_Roundify_12px"
open_Roundify_12px.Parent = main
open_Roundify_12px.Active = true
open_Roundify_12px.AnchorPoint = Vector2.new(0.5, 0.5)
open_Roundify_12px.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
open_Roundify_12px.BackgroundTransparency = 1.000
open_Roundify_12px.Position = UDim2.new(0.3682096, 0, 0.218314111, 0)
open_Roundify_12px.Selectable = true
open_Roundify_12px.Size = UDim2.new(0.0416235663, 0, 0.0645757318, 0)
open_Roundify_12px.Image = "rbxassetid://3570695787"
open_Roundify_12px.ImageColor3 = Color3.fromRGB(255, 0, 0)
open_Roundify_12px.ScaleType = Enum.ScaleType.Slice
open_Roundify_12px.SliceCenter = Rect.new(100, 100, 100, 100)
open_Roundify_12px.SliceScale = 0.120

IF.Name = "IF"
IF.Parent = main
IF.BackgroundColor3 = Color3.fromRGB(236, 236, 236)
IF.BackgroundTransparency = 1.000
IF.BorderSizePixel = 0
IF.Position = UDim2.new(0.347397923, 0, 0.185433447, 0)
IF.Size = UDim2.new(0, 28, 0, 29)
IF.Font = Enum.Font.Arial
IF.Text = ""
IF.TextColor3 = Color3.fromRGB(255, 255, 255)
IF.TextScaled = true
IF.TextSize = 14.000
IF.TextWrapped = true
IF.MouseButton1Down:connect(function()
loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
end)

TextLabel_2.Parent = main
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.Position = UDim2.new(0.0910193026, 0, 0.179468617, 0)
TextLabel_2.Size = UDim2.new(0, 183, 0, 36)
TextLabel_2.Font = Enum.Font.ArialBold
TextLabel_2.Text = "Infinite Yield"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextSize = 25.000
TextLabel_2.TextWrapped = true

TextLabel_3.Parent = main
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.BackgroundTransparency = 1.000
TextLabel_3.Position = UDim2.new(0.424352646, 0, 0.179468617, 0)
TextLabel_3.Size = UDim2.new(0, 183, 0, 36)
TextLabel_3.Font = Enum.Font.ArialBold
TextLabel_3.Text = "GrubHub"
TextLabel_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.TextSize = 25.000
TextLabel_3.TextWrapped = true

open_Roundify_12px_2.Name = "open_Roundify_12px"
open_Roundify_12px_2.Parent = main
open_Roundify_12px_2.Active = true
open_Roundify_12px_2.AnchorPoint = Vector2.new(0.5, 0.5)
open_Roundify_12px_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
open_Roundify_12px_2.BackgroundTransparency = 1.000
open_Roundify_12px_2.Position = UDim2.new(0.701542974, 0, 0.218314111, 0)
open_Roundify_12px_2.Selectable = true
open_Roundify_12px_2.Size = UDim2.new(0.0416235663, 0, 0.0645757318, 0)
open_Roundify_12px_2.Image = "rbxassetid://3570695787"
open_Roundify_12px_2.ImageColor3 = Color3.fromRGB(255, 0, 0)
open_Roundify_12px_2.ScaleType = Enum.ScaleType.Slice
open_Roundify_12px_2.SliceCenter = Rect.new(100, 100, 100, 100)
open_Roundify_12px_2.SliceScale = 0.120

GHH.Name = "GHH"
GHH.Parent = main
GHH.BackgroundColor3 = Color3.fromRGB(236, 236, 236)
GHH.BackgroundTransparency = 1.000
GHH.BorderSizePixel = 0
GHH.Position = UDim2.new(0.680731297, 0, 0.185433447, 0)
GHH.Size = UDim2.new(0, 28, 0, 29)
GHH.Font = Enum.Font.Arial
GHH.Text = ""
GHH.TextColor3 = Color3.fromRGB(255, 255, 255)
GHH.TextScaled = true
GHH.TextSize = 14.000
GHH.TextWrapped = true
GHH.MouseButton1Down:connect(function()
loadstring(game:HttpGet("https://pastebin.com/raw/BvcmWpvn", true))()
end)

WL.Name = "WL"
WL.Parent = main
WL.BackgroundColor3 = Color3.fromRGB(236, 236, 236)
WL.BackgroundTransparency = 1.000
WL.BorderSizePixel = 0
WL.Position = UDim2.new(0.680731297, 0, 0.295545816, 0)
WL.Size = UDim2.new(0, 28, 0, 29)
WL.Font = Enum.Font.Arial
WL.Text = ""
WL.TextColor3 = Color3.fromRGB(255, 255, 255)
WL.TextScaled = true
WL.TextSize = 14.000
WL.TextWrapped = true
WL.MouseButton1Down:connect(function()
loadstring(game:HttpGet("https://pastebin.com/raw/r4pLKeK8"))()
end)

PBX.Name = "PBX"
PBX.Parent = main
PBX.BackgroundColor3 = Color3.fromRGB(236, 236, 236)
PBX.BackgroundTransparency = 1.000
PBX.BorderSizePixel = 0
PBX.Position = UDim2.new(0.347397923, 0, 0.295545816, 0)
PBX.Size = UDim2.new(0, 28, 0, 29)
PBX.Font = Enum.Font.Arial
PBX.Text = ""
PBX.TextColor3 = Color3.fromRGB(255, 255, 255)
PBX.TextScaled = true
PBX.TextSize = 14.000
PBX.TextWrapped = true
PBX.MouseButton1Down:connect(function()
loadstring(game:HttpGet(("https://raw.githubusercontent.com/i1nfinity/Project-X/master/Prison%20Breaker%20X"), true))()
end)

open_Roundify_12px_3.Name = "open_Roundify_12px"
open_Roundify_12px_3.Parent = main
open_Roundify_12px_3.Active = true
open_Roundify_12px_3.AnchorPoint = Vector2.new(0.5, 0.5)
open_Roundify_12px_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
open_Roundify_12px_3.BackgroundTransparency = 1.000
open_Roundify_12px_3.Position = UDim2.new(0.3682096, 0, 0.32842648, 0)
open_Roundify_12px_3.Selectable = true
open_Roundify_12px_3.Size = UDim2.new(0.0416235663, 0, 0.0645757318, 0)
open_Roundify_12px_3.Image = "rbxassetid://3570695787"
open_Roundify_12px_3.ImageColor3 = Color3.fromRGB(255, 0, 0)
open_Roundify_12px_3.ScaleType = Enum.ScaleType.Slice
open_Roundify_12px_3.SliceCenter = Rect.new(100, 100, 100, 100)
open_Roundify_12px_3.SliceScale = 0.120

open_Roundify_12px_4.Name = "open_Roundify_12px"
open_Roundify_12px_4.Parent = main
open_Roundify_12px_4.Active = true
open_Roundify_12px_4.AnchorPoint = Vector2.new(0.5, 0.5)
open_Roundify_12px_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
open_Roundify_12px_4.BackgroundTransparency = 1.000
open_Roundify_12px_4.Position = UDim2.new(0.701542974, 0, 0.32842648, 0)
open_Roundify_12px_4.Selectable = true
open_Roundify_12px_4.Size = UDim2.new(0.0416235663, 0, 0.0645757318, 0)
open_Roundify_12px_4.Image = "rbxassetid://3570695787"
open_Roundify_12px_4.ImageColor3 = Color3.fromRGB(255, 0, 0)
open_Roundify_12px_4.ScaleType = Enum.ScaleType.Slice
open_Roundify_12px_4.SliceCenter = Rect.new(100, 100, 100, 100)
open_Roundify_12px_4.SliceScale = 0.120

TextLabel_4.Parent = main
TextLabel_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.BackgroundTransparency = 1.000
TextLabel_4.Position = UDim2.new(0.424352646, 0, 0.289580971, 0)
TextLabel_4.Size = UDim2.new(0, 183, 0, 36)
TextLabel_4.Font = Enum.Font.ArialBold
TextLabel_4.Text = "WeightLifting"
TextLabel_4.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.TextSize = 25.000
TextLabel_4.TextWrapped = true

TextLabel_5.Parent = main
TextLabel_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_5.BackgroundTransparency = 1.000
TextLabel_5.Position = UDim2.new(0.0910193026, 0, 0.289580971, 0)
TextLabel_5.Size = UDim2.new(0, 183, 0, 36)
TextLabel_5.Font = Enum.Font.ArialBold
TextLabel_5.Text = "PrisonBreakerX"
TextLabel_5.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_5.TextSize = 25.000
TextLabel_5.TextWrapped = true

SB.Name = "SB"
SB.Parent = main
SB.BackgroundColor3 = Color3.fromRGB(236, 236, 236)
SB.BackgroundTransparency = 1.000
SB.BorderSizePixel = 0
SB.Position = UDim2.new(0.680731297, 0, 0.414646924, 0)
SB.Size = UDim2.new(0, 28, 0, 29)
SB.Font = Enum.Font.Arial
SB.Text = ""
SB.TextColor3 = Color3.fromRGB(255, 255, 255)
SB.TextScaled = true
SB.TextSize = 14.000
SB.TextWrapped = true
SB.MouseButton1Down:connect(function()
loadstring(game:GetObjects("rbxassetid://3623753581")[1].Source)()
end)

Clear.Name = "Clear"
Clear.Parent = main
Clear.BackgroundColor3 = Color3.fromRGB(236, 236, 236)
Clear.BackgroundTransparency = 1.000
Clear.BorderSizePixel = 0
Clear.Position = UDim2.new(0.347397923, 0, 0.414646924, 0)
Clear.Size = UDim2.new(0, 28, 0, 29)
Clear.Font = Enum.Font.Arial
Clear.Text = ""
Clear.TextColor3 = Color3.fromRGB(255, 255, 255)
Clear.TextScaled = true
Clear.TextSize = 14.000
Clear.TextWrapped = true
Clear.MouseButton1Down:connect(function()
pcall(function()loadstring(game:HttpGet('https://raw.githubusercontent.com/bedra45/chetbypasser/main/chetbypass'))()end)
end)

open_Roundify_12px_5.Name = "open_Roundify_12px"
open_Roundify_12px_5.Parent = main
open_Roundify_12px_5.Active = true
open_Roundify_12px_5.AnchorPoint = Vector2.new(0.5, 0.5)
open_Roundify_12px_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
open_Roundify_12px_5.BackgroundTransparency = 1.000
open_Roundify_12px_5.Position = UDim2.new(0.3682096, 0, 0.447527587, 0)
open_Roundify_12px_5.Selectable = true
open_Roundify_12px_5.Size = UDim2.new(0.0416235663, 0, 0.0645757318, 0)
open_Roundify_12px_5.Image = "rbxassetid://3570695787"
open_Roundify_12px_5.ImageColor3 = Color3.fromRGB(255, 0, 0)
open_Roundify_12px_5.ScaleType = Enum.ScaleType.Slice
open_Roundify_12px_5.SliceCenter = Rect.new(100, 100, 100, 100)
open_Roundify_12px_5.SliceScale = 0.120

open_Roundify_12px_6.Name = "open_Roundify_12px"
open_Roundify_12px_6.Parent = main
open_Roundify_12px_6.Active = true
open_Roundify_12px_6.AnchorPoint = Vector2.new(0.5, 0.5)
open_Roundify_12px_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
open_Roundify_12px_6.BackgroundTransparency = 1.000
open_Roundify_12px_6.Position = UDim2.new(0.701542974, 0, 0.447527587, 0)
open_Roundify_12px_6.Selectable = true
open_Roundify_12px_6.Size = UDim2.new(0.0416235663, 0, 0.0645757318, 0)
open_Roundify_12px_6.Image = "rbxassetid://3570695787"
open_Roundify_12px_6.ImageColor3 = Color3.fromRGB(255, 0, 0)
open_Roundify_12px_6.ScaleType = Enum.ScaleType.Slice
open_Roundify_12px_6.SliceCenter = Rect.new(100, 100, 100, 100)
open_Roundify_12px_6.SliceScale = 0.120

TextLabel_6.Parent = main
TextLabel_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_6.BackgroundTransparency = 1.000
TextLabel_6.Position = UDim2.new(0.424352646, 0, 0.408682108, 0)
TextLabel_6.Size = UDim2.new(0, 183, 0, 36)
TextLabel_6.Font = Enum.Font.ArialBold
TextLabel_6.Text = "SharkBite"
TextLabel_6.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_6.TextSize = 25.000
TextLabel_6.TextWrapped = true

TextLabel_7.Parent = main
TextLabel_7.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_7.BackgroundTransparency = 1.000
TextLabel_7.Position = UDim2.new(0.0910193026, 0, 0.408682108, 0)
TextLabel_7.Size = UDim2.new(0, 183, 0, 36)
TextLabel_7.Font = Enum.Font.ArialBold
TextLabel_7.Text = "Chat Bypass"
TextLabel_7.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_7.TextSize = 25.000
TextLabel_7.TextWrapped = true

open_Roundify_12px_7.Name = "open_Roundify_12px"
open_Roundify_12px_7.Parent = main
open_Roundify_12px_7.Active = true
open_Roundify_12px_7.AnchorPoint = Vector2.new(0.5, 0.5)
open_Roundify_12px_7.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
open_Roundify_12px_7.BackgroundTransparency = 1.000
open_Roundify_12px_7.Position = UDim2.new(0.406184286, 0, 0.871123075, 0)
open_Roundify_12px_7.Selectable = true
open_Roundify_12px_7.Size = UDim2.new(0.632340968, 0, 0.102777973, 0)
open_Roundify_12px_7.Image = "rbxassetid://3570695787"
open_Roundify_12px_7.ImageColor3 = Color3.fromRGB(103, 103, 103)
open_Roundify_12px_7.ScaleType = Enum.ScaleType.Slice
open_Roundify_12px_7.SliceCenter = Rect.new(100, 100, 100, 100)
open_Roundify_12px_7.SliceScale = 0.120

CB.Name = "CB"
CB.Parent = main
CB.BackgroundColor3 = Color3.fromRGB(236, 236, 236)
CB.BackgroundTransparency = 1.000
CB.BorderSizePixel = 0
CB.Position = UDim2.new(0.0910193026, 0, 0.819734097, 0)
CB.Size = UDim2.new(0, 447, 0, 45)
CB.Font = Enum.Font.Arial
CB.Text = "Clear"
CB.TextColor3 = Color3.fromRGB(255, 255, 255)
CB.TextScaled = true
CB.TextSize = 14.000
CB.TextWrapped = true
CB.MouseButton1Down:connect(function()
Code.Text = ("")
end)

Code.Name = "Code"
Code.Parent = main
Code.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
Code.BorderColor3 = Color3.fromRGB(255, 255, 255)
Code.BorderSizePixel = 4
Code.Position = UDim2.new(0.0910193026, 0, 0.521348298, 0)
Code.Size = UDim2.new(0, 446, 0, 120)
Code.Font = Enum.Font.Code
Code.PlaceholderColor3 = Color3.fromRGB(255, 255, 255)
Code.PlaceholderText = "-- Codes Stored Here"
Code.Text = ""
Code.TextColor3 = Color3.fromRGB(255, 255, 255)
Code.TextSize = 18.000
Code.TextXAlignment = Enum.TextXAlignment.Left
Code.TextYAlignment = Enum.TextYAlignment.Top

TextLabel_8.Parent = main
TextLabel_8.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_8.BackgroundTransparency = 1.000
TextLabel_8.Position = UDim2.new(0.750653625, 0, 0.172665641, 0)
TextLabel_8.Size = UDim2.new(0, 119, 0, 40)
TextLabel_8.Font = Enum.Font.ArialBold
TextLabel_8.Text = "Premium Hub"
TextLabel_8.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_8.TextSize = 25.000
TextLabel_8.TextWrapped = true

TextLabel_9.Parent = main
TextLabel_9.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_9.BackgroundTransparency = 1.000
TextLabel_9.Position = UDim2.new(0.750653625, 0, 0.269294858, 0)
TextLabel_9.Size = UDim2.new(0, 119, 0, 40)
TextLabel_9.Font = Enum.Font.ArialBold
TextLabel_9.Text = "Premium Hub"
TextLabel_9.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_9.TextSize = 25.000
TextLabel_9.TextWrapped = true

TextLabel_10.Parent = main
TextLabel_10.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_10.BackgroundTransparency = 1.000
TextLabel_10.Position = UDim2.new(0.750653625, 0, 0.370418459, 0)
TextLabel_10.Size = UDim2.new(0, 119, 0, 40)
TextLabel_10.Font = Enum.Font.ArialBold
TextLabel_10.Text = "Premium Hub"
TextLabel_10.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_10.TextSize = 25.000
TextLabel_10.TextWrapped = true

TextLabel_11.Parent = main
TextLabel_11.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_11.BackgroundTransparency = 1.000
TextLabel_11.Position = UDim2.new(0.750653625, 0, 0.478283644, 0)
TextLabel_11.Size = UDim2.new(0, 119, 0, 40)
TextLabel_11.Font = Enum.Font.ArialBold
TextLabel_11.Text = "Premium Hub"
TextLabel_11.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_11.TextSize = 25.000
TextLabel_11.TextWrapped = true

TextLabel_12.Parent = main
TextLabel_12.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_12.BackgroundTransparency = 1.000
TextLabel_12.Position = UDim2.new(0.750653625, 0, 0.583901644, 0)
TextLabel_12.Size = UDim2.new(0, 119, 0, 40)
TextLabel_12.Font = Enum.Font.ArialBold
TextLabel_12.Text = "Premium Hub"
TextLabel_12.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_12.TextSize = 25.000
TextLabel_12.TextWrapped = true

TextLabel_13.Parent = main
TextLabel_13.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_13.BackgroundTransparency = 1.000
TextLabel_13.Position = UDim2.new(0.750653625, 0, 0.673789263, 0)
TextLabel_13.Size = UDim2.new(0, 119, 0, 40)
TextLabel_13.Font = Enum.Font.ArialBold
TextLabel_13.Text = "Premium Hub"
TextLabel_13.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_13.TextSize = 25.000
TextLabel_13.TextWrapped = true

TextLabel_14.Parent = main
TextLabel_14.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_14.BackgroundTransparency = 1.000
TextLabel_14.Position = UDim2.new(0.778782964, 0, 0.765924096, 0)
TextLabel_14.Size = UDim2.new(0, 78, 0, 69)
TextLabel_14.Font = Enum.Font.ArialBold
TextLabel_14.Text = "👑"
TextLabel_14.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_14.TextScaled = true
TextLabel_14.TextSize = 25.000
TextLabel_14.TextWrapped = true

openmain.Name = "openmain"
openmain.Parent = ScreenGui
openmain.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
openmain.BackgroundTransparency = 1.000
openmain.Position = UDim2.new(0.273340821, 0, 0.311036795, 0)
openmain.Size = UDim2.new(0, 403, 0, 239)
openmain.Image = "rbxassetid://3570695787"
openmain.ImageColor3 = Color3.fromRGB(39, 39, 39)
openmain.ScaleType = Enum.ScaleType.Slice
openmain.SliceCenter = Rect.new(100, 100, 100, 100)
openmain.SliceScale = 0.120
openmain.Active = true
openmain.Draggable = true

open_Roundify_12px_8.Name = "open_Roundify_12px"
open_Roundify_12px_8.Parent = openmain
open_Roundify_12px_8.Active = true
open_Roundify_12px_8.AnchorPoint = Vector2.new(0.5, 0.5)
open_Roundify_12px_8.BackgroundColor3 = Color3.fromRGB(76, 76, 76)
open_Roundify_12px_8.BackgroundTransparency = 1.000
open_Roundify_12px_8.Position = UDim2.new(0.498196989, 0, 0.709953785, 0)
open_Roundify_12px_8.Selectable = true
open_Roundify_12px_8.Size = UDim2.new(0.835835695, 0, 0.451743007, 0)
open_Roundify_12px_8.Image = "rbxassetid://3570695787"
open_Roundify_12px_8.ImageColor3 = Color3.fromRGB(84, 84, 84)
open_Roundify_12px_8.ScaleType = Enum.ScaleType.Slice
open_Roundify_12px_8.SliceCenter = Rect.new(100, 100, 100, 100)
open_Roundify_12px_8.SliceScale = 0.120

TextLabel_15.Parent = openmain
TextLabel_15.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_15.BackgroundTransparency = 1.000
TextLabel_15.Position = UDim2.new(0.351076484, 0, 0.104855016, 0)
TextLabel_15.Size = UDim2.new(0, 119, 0, 83)
TextLabel_15.Font = Enum.Font.ArialBold
TextLabel_15.Text = "👑"
TextLabel_15.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_15.TextScaled = true
TextLabel_15.TextSize = 14.000
TextLabel_15.TextWrapped = true

Close_2.Name = "Close"
Close_2.Parent = openmain
Close_2.BackgroundColor3 = Color3.fromRGB(236, 236, 236)
Close_2.BackgroundTransparency = 1.000
Close_2.BorderSizePixel = 0
Close_2.Position = UDim2.new(0.915649891, 0, 0.0394788943, 0)
Close_2.Size = UDim2.new(0, 25, 0, 25)
Close_2.Font = Enum.Font.Arial
Close_2.Text = "X"
Close_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Close_2.TextScaled = true
Close_2.TextSize = 14.000
Close_2.TextWrapped = true
Close_2.MouseButton1Down:connect(function()
openmain.Visible = false
end)

open.Name = "open"
open.Parent = openmain
open.BackgroundColor3 = Color3.fromRGB(236, 236, 236)
open.BackgroundTransparency = 1.000
open.BorderSizePixel = 0
open.Position = UDim2.new(0.0802791044, 0, 0.495545834, 0)
open.Size = UDim2.new(0, 336, 0, 102)
open.Font = Enum.Font.Arial
open.Text = "Premium Hub"
open.TextColor3 = Color3.fromRGB(255, 255, 255)
open.TextScaled = true
open.TextSize = 14.000
open.TextWrapped = true
open.MouseButton1Down:connect(function()
main.Visible = true
openmain.Visible = false
end)

-- Scripts:

local function XBUPAWK_fake_script() -- open.Rainbower 
	local script = Instance.new('LocalScript', open)

	while wait() do
		script.Parent.TextColor3 = Color3.new(1,0,0)
		for i=1,15 do
			game:GetService("RunService").RenderStepped:wait()
			script.Parent.TextColor3 = Color3.new(script.Parent.TextColor3.r,script.Parent.TextColor3.g+(17/255),script.Parent.TextColor3.b)
		end
		for i=1,15 do
			game:GetService("RunService").RenderStepped:wait()
			script.Parent.TextColor3 = Color3.new(script.Parent.TextColor3.r-(17/255),script.Parent.TextColor3.g,script.Parent.TextColor3.b)
		end
		for i=1,15 do
			game:GetService("RunService").RenderStepped:wait()
			script.Parent.TextColor3 = Color3.new(script.Parent.TextColor3.r,script.Parent.TextColor3.g,script.Parent.TextColor3.b+(17/255))
		end
		for i=1,15 do
			game:GetService("RunService").RenderStepped:wait()
			script.Parent.TextColor3 = Color3.new(script.Parent.TextColor3.r,script.Parent.TextColor3.g-(17/255),script.Parent.TextColor3.b)
		end
		for i=1,15 do
			game:GetService("RunService").RenderStepped:wait()
			script.Parent.TextColor3 = Color3.new(script.Parent.TextColor3.r+(17/255),script.Parent.TextColor3.g,script.Parent.TextColor3.b)
		end
		for i=1,15 do
			game:GetService("RunService").RenderStepped:wait()
			script.Parent.TextColor3 = Color3.new(script.Parent.TextColor3.r,script.Parent.TextColor3.g,script.Parent.TextColor3.b-(17/255))
		end
	end
end
coroutine.wrap(XBUPAWK_fake_script)()
