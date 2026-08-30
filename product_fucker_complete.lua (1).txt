-- Product Purchase Faker
-- Made by esore 2026

local ScreenGui = Instance.new("ScreenGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
ScreenGui.Parent = game:GetService("CoreGui")
ScreenGui.Name = "GH78UERSGWVSTSGV"

local mainbg = Instance.new("Frame")
mainbg.AnchorPoint = Vector2.new(0.5, 0.5)
mainbg.Name = "mainbg"
mainbg.Position = UDim2.new(0.5, 0, 0.5, 0)
mainbg.BorderColor3 = Color3.fromRGB(0, 0, 0)
mainbg.Size = UDim2.new(0, 411, 0, 288)
mainbg.BorderSizePixel = 0
mainbg.BackgroundColor3 = Color3.fromRGB(26, 27, 36)
mainbg.Parent = ScreenGui

local UICorner = Instance.new("UICorner")
UICorner.CornerRadius = UDim.new(0, 6)
UICorner.Parent = mainbg

local UIStroke = Instance.new("UIStroke")
UIStroke.Color = Color3.fromRGB(154, 154, 154)
UIStroke.Parent = mainbg

local Header = Instance.new("TextLabel")
Header.TextWrapped = true
Header.TextColor3 = Color3.fromRGB(255, 255, 255)
Header.BorderColor3 = Color3.fromRGB(0, 0, 0)
Header.Text = "Product Fucker"
Header.Name = "Header"
Header.Size = UDim2.new(0, 157, 0, 15)
Header.Position = UDim2.new(0.03, 0, 0.04, 0)
Header.BorderSizePixel = 0
Header.BackgroundTransparency = 1
Header.TextXAlignment = Enum.TextXAlignment.Left
Header.TextSize = 14
Header.FontFace = Font.new("rbxasset://fonts/families/SourceSansPro.json", Enum.FontWeight.Bold, Enum.FontStyle.Normal)
Header.TextScaled = true
Header.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Header.Parent = mainbg

local dfgsgdsf = Instance.new("Frame")
dfgsgdsf.BorderColor3 = Color3.fromRGB(0, 0, 0)
dfgsgdsf.AnchorPoint = Vector2.new(0.5, 0.5)
dfgsgdsf.BackgroundTransparency = 1
dfgsgdsf.Position = UDim2.new(0.5, 0, 0.14300000667572021, 0)
dfgsgdsf.Name = "dfgsgdsf"
dfgsgdsf.Size = UDim2.new(0, 389, 0, 18)
dfgsgdsf.BorderSizePixel = 0
dfgsgdsf.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
dfgsgdsf.Parent = mainbg

local ScanTab = Instance.new("ImageButton")
ScanTab.Name = "ScanTab"
ScanTab.ImageTransparency = 1
ScanTab.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScanTab.Size = UDim2.new(0, 79, 0, 18)
ScanTab.BorderSizePixel = 0
ScanTab.BackgroundColor3 = Color3.fromRGB(104, 123, 165)
ScanTab.Parent = dfgsgdsf

local UICorner = Instance.new("UICorner")
UICorner.CornerRadius = UDim.new(0, 6)
UICorner.Parent = ScanTab

local UIStroke = Instance.new("UIStroke")
UIStroke.Color = Color3.fromRGB(154, 154, 154)
UIStroke.Parent = ScanTab

local TextLabel = Instance.new("TextLabel")
TextLabel.TextWrapped = true
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.Text = "Scanner"
TextLabel.Size = UDim2.new(0, 67, 0, 11)
TextLabel.AnchorPoint = Vector2.new(0.5, 0.5)
TextLabel.BorderSizePixel = 0
TextLabel.BackgroundTransparency = 1
TextLabel.Position = UDim2.new(0.5, 0, 0.5, 0)
TextLabel.FontFace = Font.new("rbxasset://fonts/families/SourceSansPro.json", Enum.FontWeight.Bold, Enum.FontStyle.Normal)
TextLabel.TextSize = 14
TextLabel.TextScaled = true
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.Parent = ScanTab

local UIGradient = Instance.new("UIGradient")
UIGradient.Rotation = -90
UIGradient.Color = ColorSequence.new{
	ColorSequenceKeypoint.new(0, Color3.fromRGB(163, 163, 163)),
	ColorSequenceKeypoint.new(1, Color3.fromRGB(255, 255, 255))
}
UIGradient.Parent = ScanTab

local UIListLayout = Instance.new("UIListLayout")
UIListLayout.Padding = UDim.new(0.009999999776482582, 0)
UIListLayout.SortOrder = Enum.SortOrder.LayoutOrder
UIListLayout.FillDirection = Enum.FillDirection.Horizontal
UIListLayout.Parent = dfgsgdsf

local ListenerTab = Instance.new("ImageButton")
ListenerTab.Name = "ListenerTab"
ListenerTab.ImageTransparency = 1
ListenerTab.BorderColor3 = Color3.fromRGB(0, 0, 0)
ListenerTab.Size = UDim2.new(0, 79, 0, 18)
ListenerTab.BorderSizePixel = 0
ListenerTab.BackgroundColor3 = Color3.fromRGB(90, 99, 109)
ListenerTab.Parent = dfgsgdsf

local UICorner = Instance.new("UICorner")
UICorner.CornerRadius = UDim.new(0, 6)
UICorner.Parent = ListenerTab

local UIStroke = Instance.new("UIStroke")
UIStroke.Color = Color3.fromRGB(154, 154, 154)
UIStroke.Parent = ListenerTab

local TextLabel = Instance.new("TextLabel")
TextLabel.TextWrapped = true
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.Text = "Listener"
TextLabel.Size = UDim2.new(0, 67, 0, 11)
TextLabel.AnchorPoint = Vector2.new(0.5, 0.5)
TextLabel.BorderSizePixel = 0
TextLabel.BackgroundTransparency = 1
TextLabel.Position = UDim2.new(0.5, 0, 0.5, 0)
TextLabel.FontFace = Font.new("rbxasset://fonts/families/SourceSansPro.json", Enum.FontWeight.Bold, Enum.FontStyle.Normal)
TextLabel.TextSize = 14
TextLabel.TextScaled = true
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.Parent = ListenerTab

local UIGradient = Instance.new("UIGradient")
UIGradient.Rotation = -90
UIGradient.Color = ColorSequence.new{
	ColorSequenceKeypoint.new(0, Color3.fromRGB(163, 163, 163)),
	ColorSequenceKeypoint.new(1, Color3.fromRGB(255, 255, 255))
}
UIGradient.Parent = ListenerTab

local ActionTab = Instance.new("ImageButton")
ActionTab.Name = "ActionTab"
ActionTab.ImageTransparency = 1
ActionTab.BorderColor3 = Color3.fromRGB(0, 0, 0)
ActionTab.Size = UDim2.new(0, 79, 0, 18)
ActionTab.BorderSizePixel = 0
ActionTab.BackgroundColor3 = Color3.fromRGB(90, 99, 109)
ActionTab.Parent = dfgsgdsf

local UICorner = Instance.new("UICorner")
UICorner.CornerRadius = UDim.new(0, 6)
UICorner.Parent = ActionTab

local UIStroke = Instance.new("UIStroke")
UIStroke.Color = Color3.fromRGB(154, 154, 154)
UIStroke.Parent = ActionTab

local TextLabel = Instance.new("TextLabel")
TextLabel.TextWrapped = true
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.Text = "Action"
TextLabel.Size = UDim2.new(0, 67, 0, 11)
TextLabel.AnchorPoint = Vector2.new(0.5, 0.5)
TextLabel.BorderSizePixel = 0
TextLabel.BackgroundTransparency = 1
TextLabel.Position = UDim2.new(0.5, 0, 0.5, 0)
TextLabel.FontFace = Font.new("rbxasset://fonts/families/SourceSansPro.json", Enum.FontWeight.Bold, Enum.FontStyle.Normal)
TextLabel.TextSize = 14
TextLabel.TextScaled = true
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.Parent = ActionTab

local UIGradient = Instance.new("UIGradient")
UIGradient.Rotation = -90
UIGradient.Color = ColorSequence.new{
	ColorSequenceKeypoint.new(0, Color3.fromRGB(163, 163, 163)),
	ColorSequenceKeypoint.new(1, Color3.fromRGB(255, 255, 255))
}
UIGradient.Parent = ActionTab

-- ==================== SCANNER TAB FRAME ====================
local scannerTabFrame = Instance.new("ScrollingFrame")
scannerTabFrame.Visible = false
scannerTabFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
scannerTabFrame.Name = "scannerTabFrame"
scannerTabFrame.Size = UDim2.new(0, 389, 0, 218)
scannerTabFrame.AnchorPoint = Vector2.new(0.5, 0.5)
scannerTabFrame.Selectable = false
scannerTabFrame.BackgroundTransparency = 1
scannerTabFrame.Position = UDim2.new(0.5, 0, 0.5859708786010742, 0)
scannerTabFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
scannerTabFrame.AutomaticCanvasSize = Enum.AutomaticSize.Y
scannerTabFrame.BorderSizePixel = 0
scannerTabFrame.CanvasSize = UDim2.new(0, 0, 0, 0)
scannerTabFrame.Parent = mainbg

local UIListLayout_scanner = Instance.new("UIListLayout")
UIListLayout_scanner.Padding = UDim.new(0.009999999776482582, 0)
UIListLayout_scanner.SortOrder = Enum.SortOrder.LayoutOrder
UIListLayout_scanner.Parent = scannerTabFrame

-- Scan Button
local ScanBtn = Instance.new("ImageButton")
ScanBtn.Size = UDim2.new(0, 96, 0, 22)
ScanBtn.Name = "ScanBtn"
ScanBtn.ImageTransparency = 1
ScanBtn.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScanBtn.Position = UDim2.new(0, 0, 0, 0)
ScanBtn.BorderSizePixel = 0
ScanBtn.BackgroundColor3 = Color3.fromRGB(90, 99, 109)
ScanBtn.Parent = scannerTabFrame

local UICorner_ScanBtn = Instance.new("UICorner")
UICorner_ScanBtn.CornerRadius = UDim.new(0, 6)
UICorner_ScanBtn.Parent = ScanBtn

local UIStroke_ScanBtn = Instance.new("UIStroke")
UIStroke_ScanBtn.Color = Color3.fromRGB(154, 154, 154)
UIStroke_ScanBtn.BorderStrokePosition = Enum.BorderStrokePosition.Inner
UIStroke_ScanBtn.Parent = ScanBtn

local TextLabel_ScanBtn = Instance.new("TextLabel")
TextLabel_ScanBtn.TextWrapped = true
TextLabel_ScanBtn.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_ScanBtn.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_ScanBtn.Text = "Scan"
TextLabel_ScanBtn.Size = UDim2.new(0, 67, 0, 11)
TextLabel_ScanBtn.AnchorPoint = Vector2.new(0.5, 0.5)
TextLabel_ScanBtn.BorderSizePixel = 0
TextLabel_ScanBtn.BackgroundTransparency = 1
TextLabel_ScanBtn.Position = UDim2.new(0.5, 0, 0.5, 0)
TextLabel_ScanBtn.FontFace = Font.new("rbxasset://fonts/families/SourceSansPro.json", Enum.FontWeight.Bold, Enum.FontStyle.Normal)
TextLabel_ScanBtn.TextSize = 14
TextLabel_ScanBtn.TextScaled = true
TextLabel_ScanBtn.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_ScanBtn.Parent = ScanBtn

local UIGradient_ScanBtn = Instance.new("UIGradient")
UIGradient_ScanBtn.Rotation = -90
UIGradient_ScanBtn.Color = ColorSequence.new{
	ColorSequenceKeypoint.new(0, Color3.fromRGB(163, 163, 163)),
	ColorSequenceKeypoint.new(1, Color3.fromRGB(255, 255, 255))
}
UIGradient_ScanBtn.Parent = ScanBtn

-- ReScan Button (top right)
local ReScanBtn = Instance.new("ImageButton")
ReScanBtn.Size = UDim2.new(0, 96, 0, 22)
ReScanBtn.Name = "ReScanBtn"
ReScanBtn.ImageTransparency = 1
ReScanBtn.BorderColor3 = Color3.fromRGB(0, 0, 0)
ReScanBtn.Position = UDim2.new(0.74, 0, 0, 0)
ReScanBtn.BorderSizePixel = 0
ReScanBtn.BackgroundColor3 = Color3.fromRGB(90, 99, 109)
ReScanBtn.Parent = scannerTabFrame

local UICorner_ReScan = Instance.new("UICorner")
UICorner_ReScan.CornerRadius = UDim.new(0, 6)
UICorner_ReScan.Parent = ReScanBtn

local UIStroke_ReScan = Instance.new("UIStroke")
UIStroke_ReScan.Color = Color3.fromRGB(154, 154, 154)
UIStroke_ReScan.BorderStrokePosition = Enum.BorderStrokePosition.Inner
UIStroke_ReScan.Parent = ReScanBtn

local TextLabel_ReScan = Instance.new("TextLabel")
TextLabel_ReScan.TextWrapped = true
TextLabel_ReScan.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_ReScan.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_ReScan.Text = "ReScan"
TextLabel_ReScan.Size = UDim2.new(0, 67, 0, 11)
TextLabel_ReScan.AnchorPoint = Vector2.new(0.5, 0.5)
TextLabel_ReScan.BorderSizePixel = 0
TextLabel_ReScan.BackgroundTransparency = 1
TextLabel_ReScan.Position = UDim2.new(0.5, 0, 0.5, 0)
TextLabel_ReScan.FontFace = Font.new("rbxasset://fonts/families/SourceSansPro.json", Enum.FontWeight.Bold, Enum.FontStyle.Normal)
TextLabel_ReScan.TextSize = 14
TextLabel_ReScan.TextScaled = true
TextLabel_ReScan.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_ReScan.Parent = ReScanBtn

local UIGradient_ReScan = Instance.new("UIGradient")
UIGradient_ReScan.Rotation = -90
UIGradient_ReScan.Color = ColorSequence.new{
	ColorSequenceKeypoint.new(0, Color3.fromRGB(163, 163, 163)),
	ColorSequenceKeypoint.new(1, Color3.fromRGB(255, 255, 255))
}
UIGradient_ReScan.Parent = ReScanBtn

-- Scanner Results ScrollFrame
local ScannerResults = Instance.new("ScrollingFrame")
ScannerResults.Name = "ScannerResults"
ScannerResults.Size = UDim2.new(0, 389, 0, 170)
ScannerResults.BackgroundTransparency = 1
ScannerResults.BorderSizePixel = 0
ScannerResults.AutomaticCanvasSize = Enum.AutomaticSize.Y
ScannerResults.CanvasSize = UDim2.new(0, 0, 0, 0)
ScannerResults.ScrollBarThickness = 3
ScannerResults.Parent = scannerTabFrame

local UIListLayout_Results = Instance.new("UIListLayout")
UIListLayout_Results.Padding = UDim.new(0.009999999776482582, 0)
UIListLayout_Results.SortOrder = Enum.SortOrder.LayoutOrder
UIListLayout_Results.Parent = ScannerResults

-- ==================== LISTENER TAB FRAME ====================
local listenerTabFrame = Instance.new("ScrollingFrame")
listenerTabFrame.Visible = false
listenerTabFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
listenerTabFrame.Name = "listenerTabFrame"
listenerTabFrame.Size = UDim2.new(0, 389, 0, 218)
listenerTabFrame.AnchorPoint = Vector2.new(0.5, 0.5)
listenerTabFrame.Selectable = false
listenerTabFrame.BackgroundTransparency = 1
listenerTabFrame.Position = UDim2.new(0.5, 0, 0.5859708786010742, 0)
listenerTabFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
listenerTabFrame.AutomaticCanvasSize = Enum.AutomaticSize.Y
listenerTabFrame.BorderSizePixel = 0
listenerTabFrame.CanvasSize = UDim2.new(0, 0, 0, 0)
listenerTabFrame.Parent = mainbg

local UIListLayout_listener = Instance.new("UIListLayout")
UIListLayout_listener.Padding = UDim.new(0.009999999776482582, 0)
UIListLayout_listener.SortOrder = Enum.SortOrder.LayoutOrder
UIListLayout_listener.Parent = listenerTabFrame

-- ==================== ACTION TAB FRAME ====================
local actionTabFrame = Instance.new("Frame")
actionTabFrame.ClipsDescendants = true
actionTabFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
actionTabFrame.AnchorPoint = Vector2.new(0.5, 0.5)
actionTabFrame.Name = "actionTabFrame"
actionTabFrame.BackgroundTransparency = 1
actionTabFrame.Position = UDim2.new(0.5, 0, 0.5859708786010742, 0)
actionTabFrame.SelectionGroup = true
actionTabFrame.Size = UDim2.new(0, 389, 0, 218)
actionTabFrame.BorderSizePixel = 0
actionTabFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
actionTabFrame.Parent = mainbg

local UIListLayout_action = Instance.new("UIListLayout")
UIListLayout_action.Padding = UDim.new(0.009999999776482582, 0)
UIListLayout_action.SortOrder = Enum.SortOrder.LayoutOrder
UIListLayout_action.Parent = actionTabFrame

local grferge = Instance.new("Frame")
grferge.Active = true
grferge.Selectable = true
grferge.BackgroundTransparency = 0.75
grferge.Name = "grferge"
grferge.Size = UDim2.new(0, 369, 0, 25)
grferge.BorderColor3 = Color3.fromRGB(0, 0, 0)
grferge.BorderSizePixel = 0
grferge.BackgroundColor3 = Color3.fromRGB(90, 99, 109)
grferge.Parent = actionTabFrame

local UICorner_grf = Instance.new("UICorner")
UICorner_grf.CornerRadius = UDim.new(0, 6)
UICorner_grf.Parent = grferge

local UIStroke_grf = Instance.new("UIStroke")
UIStroke_grf.Color = Color3.fromRGB(154, 154, 154)
UIStroke_grf.BorderStrokePosition = Enum.BorderStrokePosition.Inner
UIStroke_grf.Parent = grferge

local UIGradient_grf = Instance.new("UIGradient")
UIGradient_grf.Rotation = -90
UIGradient_grf.Color = ColorSequence.new{
	ColorSequenceKeypoint.new(0, Color3.fromRGB(163, 163, 163)),
	ColorSequenceKeypoint.new(1, Color3.fromRGB(255, 255, 255))
}
UIGradient_grf.Parent = grferge

local ProductIDInput = Instance.new("TextBox")
ProductIDInput.PlaceholderText = "Product ID"
ProductIDInput.TextSize = 14
ProductIDInput.Size = UDim2.new(0, 334, 0, 19)
ProductIDInput.TextColor3 = Color3.fromRGB(255, 201, 37)
ProductIDInput.BorderColor3 = Color3.fromRGB(0, 0, 0)
ProductIDInput.Text = ""
ProductIDInput.Name = "ProductIDInput"
ProductIDInput.Position = UDim2.new(0.514008641242981, 0, 0.5, 0)
ProductIDInput.AnchorPoint = Vector2.new(0.5, 0.5)
ProductIDInput.BorderSizePixel = 0
ProductIDInput.FontFace = Font.new("rbxasset://fonts/families/Inconsolata.json", Enum.FontWeight.Bold, Enum.FontStyle.Normal)
ProductIDInput.BackgroundTransparency = 1
ProductIDInput.TextXAlignment = Enum.TextXAlignment.Left
ProductIDInput.TextWrapped = true
ProductIDInput.ClearTextOnFocus = false
ProductIDInput.TextScaled = true
ProductIDInput.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ProductIDInput.Parent = grferge

local Ico = Instance.new("ImageLabel")
Ico.BorderColor3 = Color3.fromRGB(0, 0, 0)
Ico.Name = "Ico"
Ico.Size = UDim2.new(0, 12, 0, 12)
Ico.Position = UDim2.new(0.033943966031074524, 0, 0.5, 0)
Ico.AnchorPoint = Vector2.new(0.5, 0.5)
Ico.Image = "rbxassetid://16167590360"
Ico.BackgroundTransparency = 1
Ico.ImageRectSize = Vector2.new(16, 16)
Ico.ImageRectOffset = Vector2.new(253, 492)
Ico.BorderSizePixel = 0
Ico.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Ico.Parent = grferge

local Warn = Instance.new("TextLabel")
Warn.TextWrapped = true
Warn.Name = "Warn"
Warn.TextColor3 = Color3.fromRGB(255, 53, 53)
Warn.BorderColor3 = Color3.fromRGB(0, 0, 0)
Warn.Text = "! This won't actually purchase the product, This just fakes it."
Warn.Size = UDim2.new(0, 356, 0, 12)
Warn.Position = UDim2.new(0.45807769894599915, 0, 0.13062931597232819, 0)
Warn.AnchorPoint = Vector2.new(0.5, 0.5)
Warn.BorderSizePixel = 0
Warn.BackgroundTransparency = 1
Warn.TextXAlignment = Enum.TextXAlignment.Left
Warn.TextScaled = true
Warn.FontFace = Font.new("rbxasset://fonts/families/SourceSansPro.json", Enum.FontWeight.Bold, Enum.FontStyle.Normal)
Warn.TextSize = 14
Warn.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Warn.Parent = actionTabFrame

local HookBtn = Instance.new("ImageButton")
HookBtn.Size = UDim2.new(0, 96, 0, 22)
HookBtn.Name = "HookBtn"
HookBtn.ImageTransparency = 1
HookBtn.BorderColor3 = Color3.fromRGB(0, 0, 0)
HookBtn.Position = UDim2.new(0, 0, 0.10440554469823837, 0)
HookBtn.BorderSizePixel = 0
HookBtn.BackgroundColor3 = Color3.fromRGB(90, 99, 109)
HookBtn.Parent = actionTabFrame

local UICorner_Hook = Instance.new("UICorner")
UICorner_Hook.CornerRadius = UDim.new(0, 6)
UICorner_Hook.Parent = HookBtn

local UIStroke_Hook = Instance.new("UIStroke")
UIStroke_Hook.Color = Color3.fromRGB(154, 154, 154)
UIStroke_Hook.BorderStrokePosition = Enum.BorderStrokePosition.Inner
UIStroke_Hook.Parent = HookBtn

local TextLabel_Hook = Instance.new("TextLabel")
TextLabel_Hook.TextWrapped = true
TextLabel_Hook.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_Hook.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_Hook.Text = "Signal Product"
TextLabel_Hook.Size = UDim2.new(0, 67, 0, 11)
TextLabel_Hook.AnchorPoint = Vector2.new(0.5, 0.5)
TextLabel_Hook.BorderSizePixel = 0
TextLabel_Hook.BackgroundTransparency = 1
TextLabel_Hook.Position = UDim2.new(0.5, 0, 0.5, 0)
TextLabel_Hook.FontFace = Font.new("rbxasset://fonts/families/SourceSansPro.json", Enum.FontWeight.Bold, Enum.FontStyle.Normal)
TextLabel_Hook.TextSize = 14
TextLabel_Hook.TextScaled = true
TextLabel_Hook.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_Hook.Parent = HookBtn

local UIGradient_Hook = Instance.new("UIGradient")
UIGradient_Hook.Rotation = -90
UIGradient_Hook.Color = ColorSequence.new{
	ColorSequenceKeypoint.new(0, Color3.fromRGB(163, 163, 163)),
	ColorSequenceKeypoint.new(1, Color3.fromRGB(255, 255, 255))
}
UIGradient_Hook.Parent = HookBtn

local GamepassBtn = Instance.new("ImageButton")
GamepassBtn.Size = UDim2.new(0, 96, 0, 22)
GamepassBtn.Name = "GamepassBtn"
GamepassBtn.ImageTransparency = 1
GamepassBtn.BorderColor3 = Color3.fromRGB(0, 0, 0)
GamepassBtn.Position = UDim2.new(0, 0, 0.10440554469823837, 0)
GamepassBtn.BorderSizePixel = 0
GamepassBtn.BackgroundColor3 = Color3.fromRGB(90, 99, 109)
GamepassBtn.Parent = actionTabFrame

local UICorner_GP = Instance.new("UICorner")
UICorner_GP.CornerRadius = UDim.new(0, 6)
UICorner_GP.Parent = GamepassBtn

local UIStroke_GP = Instance.new("UIStroke")
UIStroke_GP.Color = Color3.fromRGB(154, 154, 154)
UIStroke_GP.BorderStrokePosition = Enum.BorderStrokePosition.Inner
UIStroke_GP.Parent = GamepassBtn

local TextLabel_GP = Instance.new("TextLabel")
TextLabel_GP.TextWrapped = true
TextLabel_GP.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_GP.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_GP.Text = "Signal Gamepass"
TextLabel_GP.Size = UDim2.new(0, 67, 0, 11)
TextLabel_GP.AnchorPoint = Vector2.new(0.5, 0.5)
TextLabel_GP.BorderSizePixel = 0
TextLabel_GP.BackgroundTransparency = 1
TextLabel_GP.Position = UDim2.new(0.5, 0, 0.5, 0)
TextLabel_GP.FontFace = Font.new("rbxasset://fonts/families/SourceSansPro.json", Enum.FontWeight.Bold, Enum.FontStyle.Normal)
TextLabel_GP.TextSize = 14
TextLabel_GP.TextScaled = true
TextLabel_GP.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_GP.Parent = GamepassBtn

local UIGradient_GP = Instance.new("UIGradient")
UIGradient_GP.Rotation = -90
UIGradient_GP.Color = ColorSequence.new{
	ColorSequenceKeypoint.new(0, Color3.fromRGB(163, 163, 163)),
	ColorSequenceKeypoint.new(1, Color3.fromRGB(255, 255, 255))
}
UIGradient_GP.Parent = GamepassBtn

local BulkBtn = Instance.new("ImageButton")
BulkBtn.Size = UDim2.new(0, 96, 0, 22)
BulkBtn.Name = "BulkBtn"
BulkBtn.ImageTransparency = 1
BulkBtn.BorderColor3 = Color3.fromRGB(0, 0, 0)
BulkBtn.Position = UDim2.new(0, 0, 0.10440554469823837, 0)
BulkBtn.BorderSizePixel = 0
BulkBtn.BackgroundColor3 = Color3.fromRGB(90, 99, 109)
BulkBtn.Parent = actionTabFrame

local UICorner_Bulk = Instance.new("UICorner")
UICorner_Bulk.CornerRadius = UDim.new(0, 6)
UICorner_Bulk.Parent = BulkBtn

local UIStroke_Bulk = Instance.new("UIStroke")
UIStroke_Bulk.Color = Color3.fromRGB(154, 154, 154)
UIStroke_Bulk.BorderStrokePosition = Enum.BorderStrokePosition.Inner
UIStroke_Bulk.Parent = BulkBtn

local TextLabel_Bulk = Instance.new("TextLabel")
TextLabel_Bulk.TextWrapped = true
TextLabel_Bulk.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_Bulk.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_Bulk.Text = "Signal Bulk"
TextLabel_Bulk.Size = UDim2.new(0, 67, 0, 11)
TextLabel_Bulk.AnchorPoint = Vector2.new(0.5, 0.5)
TextLabel_Bulk.BorderSizePixel = 0
TextLabel_Bulk.BackgroundTransparency = 1
TextLabel_Bulk.Position = UDim2.new(0.5, 0, 0.5, 0)
TextLabel_Bulk.FontFace = Font.new("rbxasset://fonts/families/SourceSansPro.json", Enum.FontWeight.Bold, Enum.FontStyle.Normal)
TextLabel_Bulk.TextSize = 14
TextLabel_Bulk.TextScaled = true
TextLabel_Bulk.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_Bulk.Parent = BulkBtn

local UIGradient_Bulk = Instance.new("UIGradient")
UIGradient_Bulk.Rotation = -90
UIGradient_Bulk.Color = ColorSequence.new{
	ColorSequenceKeypoint.new(0, Color3.fromRGB(163, 163, 163)),
	ColorSequenceKeypoint.new(1, Color3.fromRGB(255, 255, 255))
}
UIGradient_Bulk.Parent = BulkBtn

local PurchaseBtn = Instance.new("ImageButton")
PurchaseBtn.Size = UDim2.new(0, 96, 0, 22)
PurchaseBtn.Name = "PurchaseBtn"
PurchaseBtn.ImageTransparency = 1
PurchaseBtn.BorderColor3 = Color3.fromRGB(0, 0, 0)
PurchaseBtn.Position = UDim2.new(0, 0, 0.10440554469823837, 0)
PurchaseBtn.BorderSizePixel = 0
PurchaseBtn.BackgroundColor3 = Color3.fromRGB(90, 99, 109)
PurchaseBtn.Parent = actionTabFrame

local UICorner_Pur = Instance.new("UICorner")
UICorner_Pur.CornerRadius = UDim.new(0, 6)
UICorner_Pur.Parent = PurchaseBtn

local UIStroke_Pur = Instance.new("UIStroke")
UIStroke_Pur.Color = Color3.fromRGB(154, 154, 154)
UIStroke_Pur.BorderStrokePosition = Enum.BorderStrokePosition.Inner
UIStroke_Pur.Parent = PurchaseBtn

local TextLabel_Pur = Instance.new("TextLabel")
TextLabel_Pur.TextWrapped = true
TextLabel_Pur.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_Pur.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_Pur.Text = "Signal Purchase"
TextLabel_Pur.Size = UDim2.new(0, 67, 0, 11)
TextLabel_Pur.AnchorPoint = Vector2.new(0.5, 0.5)
TextLabel_Pur.BorderSizePixel = 0
TextLabel_Pur.BackgroundTransparency = 1
TextLabel_Pur.Position = UDim2.new(0.5, 0, 0.5, 0)
TextLabel_Pur.FontFace = Font.new("rbxasset://fonts/families/SourceSansPro.json", Enum.FontWeight.Bold, Enum.FontStyle.Normal)
TextLabel_Pur.TextSize = 14
TextLabel_Pur.TextScaled = true
TextLabel_Pur.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_Pur.Parent = PurchaseBtn

local UIGradient_Pur = Instance.new("UIGradient")
UIGradient_Pur.Rotation = -90
UIGradient_Pur.Color = ColorSequence.new{
	ColorSequenceKeypoint.new(0, Color3.fromRGB(163, 163, 163)),
	ColorSequenceKeypoint.new(1, Color3.fromRGB(255, 255, 255))
}
UIGradient_Pur.Parent = PurchaseBtn



local TweenService = game:GetService("TweenService")
local dragging = false
local dragInput, dragStart, startPos

local tweenSpeed = 0.15 -- smoothing speed

mainbg.Active = true
mainbg.Selectable = true

local function update(input)
    if not dragging then return end
    local delta = input.Position - dragStart
    local newPos = UDim2.new(
        startPos.X.Scale,
        startPos.X.Offset + delta.X,
        startPos.Y.Scale,
        startPos.Y.Offset + delta.Y
    )

    -- Tween soft in position
    TweenService:Create(mainbg, TweenInfo.new(tweenSpeed, Enum.EasingStyle.Quad, Enum.EasingDirection.Out), {
        Position = newPos
    }):Play()
end

mainbg.InputBegan:Connect(function(input)
    if input.UserInputType == Enum.UserInputType.MouseButton1 or 
       input.UserInputType == Enum.UserInputType.Touch then
        dragging = true
        dragStart = input.Position
        startPos = mainbg.Position

        input.Changed:Connect(function()
            if input.UserInputState == Enum.UserInputState.End then
                dragging = false
            end
        end)
    end
end)

mainbg.InputChanged:Connect(function(input)
    if input.UserInputType == Enum.UserInputType.MouseMovement or 
       input.UserInputType == Enum.UserInputType.Touch then
        dragInput = input
    end
end)

game:GetService("UserInputService").InputChanged:Connect(function(input)
    if input == dragInput and dragging then
        update(input)
    end
end)


-- Tabs Handler
ScanTab.MouseButton1Click:Connect(function()
    ScanTab.BackgroundColor3 = Color3.fromRGB(104, 123, 165)
    ListenerTab.BackgroundColor3 = Color3.fromRGB(90, 99, 109)
    ActionTab.BackgroundColor3 = Color3.fromRGB(90, 99, 109)

    scannerTabFrame.Visible = true
    listenerTabFrame.Visible = false
    actionTabFrame.Visible = false
end)
ListenerTab.MouseButton1Click:Connect(function()
    ScanTab.BackgroundColor3 = Color3.fromRGB(90, 99, 109)
    ListenerTab.BackgroundColor3 = Color3.fromRGB(104, 123, 165)
    ActionTab.BackgroundColor3 = Color3.fromRGB(90, 99, 109)

    scannerTabFrame.Visible = false
    listenerTabFrame.Visible = true
    actionTabFrame.Visible = false
end)
ActionTab.MouseButton1Click:Connect(function()
    ScanTab.BackgroundColor3 = Color3.fromRGB(90, 99, 109)
    ListenerTab.BackgroundColor3 = Color3.fromRGB(90, 99, 109)
    ActionTab.BackgroundColor3 = Color3.fromRGB(104, 123, 165)

    scannerTabFrame.Visible = false
    listenerTabFrame.Visible = false
    actionTabFrame.Visible = true
end)

local MarketplaceService = game:GetService("MarketplaceService")

HookBtn.MouseButton1Click:Connect(function()
    local productID = tonumber(ProductIDInput.Text)
    if not productID then
        warn("Invalid Product ID")
        return
    end

    print("Falsely Bought product:", productID)

    MarketplaceService:SignalPromptProductPurchaseFinished(
        game:GetService("Players").LocalPlayer.UserId,
        productID,
        true
    )
end)

GamepassBtn.MouseButton1Click:Connect(function()
    local productID = tonumber(ProductIDInput.Text)
    if not productID then
        warn("Invalid Product ID")
        return
    end

    print("Falsely Bought product:", productID)

    MarketplaceService:SignalPromptGamePassPurchaseFinished(
        game:GetService("Players").LocalPlayer,
        productID,
        true
    )
end)

BulkBtn.MouseButton1Click:Connect(function()
    local productID = tonumber(ProductIDInput.Text)
    if not productID then
        warn("Invalid Product ID")
        return
    end

    print("Falsely Bought product:", productID)

    MarketplaceService:SignalPromptBulkPurchaseFinished(
        game:GetService("Players").LocalPlayer.UserId,
        productID,
        true
    )
end)

PurchaseBtn.MouseButton1Click:Connect(function()
    local productID = tonumber(ProductIDInput.Text)
    if not productID then
        warn("Invalid Product ID")
        return
    end

    print("Falsely Bought product:", productID)

    MarketplaceService:SignalPromptPurchaseFinished(
        game:GetService("Players").LocalPlayer.UserId,
        productID,
        true
    )
end)

-- ==================== ADD RESPONSE FUNCTION (Shared) ====================
function addLog(pName, purchasedId, wasPurchased, parentFrame)
    parentFrame = parentFrame or listenerTabFrame

    local Response = Instance.new("Frame")
    Response.Active = true
    Response.Selectable = true
    Response.BackgroundTransparency = 0.75
    Response.Name = "Response"
    Response.Size = UDim2.new(0, 369, 0, 37)
    Response.BorderColor3 = Color3.fromRGB(0, 0, 0)
    Response.BorderSizePixel = 0
    Response.BackgroundColor3 = Color3.fromRGB(90, 99, 109)
    Response.Parent = parentFrame

    local UICorner = Instance.new("UICorner")
    UICorner.CornerRadius = UDim.new(0, 6)
    UICorner.Parent = Response

    local UIStroke = Instance.new("UIStroke")
    UIStroke.Color = Color3.fromRGB(154, 154, 154)
    UIStroke.BorderStrokePosition = Enum.BorderStrokePosition.Inner
    UIStroke.Parent = Response

    local ProductName = Instance.new("TextLabel")
    ProductName.TextWrapped = true
    ProductName.Name = "ProductName"
    ProductName.TextColor3 = Color3.fromRGB(255, 255, 255)
    ProductName.BorderColor3 = Color3.fromRGB(0, 0, 0)
    ProductName.Text = pName
    ProductName.Size = UDim2.new(0, 200, 0, 12)
    ProductName.Position = UDim2.new(0.32, 0, 0.375, 0)
    ProductName.AnchorPoint = Vector2.new(0.5, 0.5)
    ProductName.BorderSizePixel = 0
    ProductName.BackgroundTransparency = 1
    ProductName.TextXAlignment = Enum.TextXAlignment.Left
    ProductName.TextScaled = true
    ProductName.FontFace = Font.new("rbxasset://fonts/families/Inconsolata.json", Enum.FontWeight.Bold, Enum.FontStyle.Normal)
    ProductName.TextSize = 14
    ProductName.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
    ProductName.Parent = Response

    local UIGradient = Instance.new("UIGradient")
    UIGradient.Rotation = -90
    UIGradient.Color = ColorSequence.new{
        ColorSequenceKeypoint.new(0, Color3.fromRGB(163, 163, 163)),
        ColorSequenceKeypoint.new(1, Color3.fromRGB(255, 255, 255))
    }
    UIGradient.Parent = Response

    local ProductID = Instance.new("TextLabel")
    ProductID.TextWrapped = true
    ProductID.Name = "ProductID"
    ProductID.TextColor3 = Color3.fromRGB(255, 201, 37)
    ProductID.BorderColor3 = Color3.fromRGB(0, 0, 0)
    ProductID.Text = tostring(purchasedId)
    ProductID.Size = UDim2.new(0, 200, 0, 12)
    ProductID.Position = UDim2.new(0.32, 0, 0.6875, 0)
    ProductID.AnchorPoint = Vector2.new(0.5, 0.5)
    ProductID.BorderSizePixel = 0
    ProductID.BackgroundTransparency = 1
    ProductID.TextXAlignment = Enum.TextXAlignment.Left
    ProductID.TextScaled = true
    ProductID.FontFace = Font.new("rbxasset://fonts/families/Inconsolata.json", Enum.FontWeight.Bold, Enum.FontStyle.Normal)
    ProductID.TextSize = 14
    ProductID.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
    ProductID.Parent = Response

    -- Delete Button (behind OpenProduct)
    local DeleteBtn = Instance.new("ImageButton")
    DeleteBtn.ImageTransparency = 1
    DeleteBtn.BorderColor3 = Color3.fromRGB(0, 0, 0)
    DeleteBtn.AnchorPoint = Vector2.new(0.5, 0.5)
    DeleteBtn.Name = "DeleteBtn"
    DeleteBtn.Position = UDim2.new(0.87, 0, 0.5, 0)
    DeleteBtn.Size = UDim2.new(0, 24, 0, 23)
    DeleteBtn.BorderSizePixel = 0
    DeleteBtn.BackgroundColor3 = Color3.fromRGB(90, 99, 109)
    DeleteBtn.Parent = Response

    local UICorner_Del = Instance.new("UICorner")
    UICorner_Del.CornerRadius = UDim.new(0, 6)
    UICorner_Del.Parent = DeleteBtn

    local UIStroke_Del = Instance.new("UIStroke")
    UIStroke_Del.Color = Color3.fromRGB(154, 154, 154)
    UIStroke_Del.Parent = DeleteBtn

    local UIGradient_Del = Instance.new("UIGradient")
    UIGradient_Del.Rotation = -90
    UIGradient_Del.Color = ColorSequence.new{
        ColorSequenceKeypoint.new(0, Color3.fromRGB(163, 163, 163)),
        ColorSequenceKeypoint.new(1, Color3.fromRGB(255, 255, 255))
    }
    UIGradient_Del.Parent = DeleteBtn

    local Ico_Del = Instance.new("ImageLabel")
    Ico_Del.ImageColor3 = Color3.fromRGB(197, 197, 197)
    Ico_Del.BorderColor3 = Color3.fromRGB(0, 0, 0)
    Ico_Del.Name = "Ico"
    Ico_Del.Size = UDim2.new(0, 16, 0, 16)
    Ico_Del.Position = UDim2.new(0.5, 0, 0.5, 0)
    Ico_Del.AnchorPoint = Vector2.new(0.5, 0.5)
    Ico_Del.Image = "rbxassetid://7733768142"
    Ico_Del.BackgroundTransparency = 1
    Ico_Del.BorderSizePixel = 0
    Ico_Del.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
    Ico_Del.Parent = DeleteBtn

    DeleteBtn.MouseButton1Click:Connect(function()
        Response:Destroy()
    end)

    -- CopyID Button
    local CopyID = Instance.new("ImageButton")
    CopyID.ImageTransparency = 1
    CopyID.BorderColor3 = Color3.fromRGB(0, 0, 0)
    CopyID.AnchorPoint = Vector2.new(0.5, 0.5)
    CopyID.Name = "CopyID"
    CopyID.Position = UDim2.new(0.79, 0, 0.5, 0)
    CopyID.Size = UDim2.new(0, 24, 0, 23)
    CopyID.BorderSizePixel = 0
    CopyID.BackgroundColor3 = Color3.fromRGB(90, 99, 109)
    CopyID.Parent = Response

    local UICorner_Copy = Instance.new("UICorner")
    UICorner_Copy.CornerRadius = UDim.new(0, 6)
    UICorner_Copy.Parent = CopyID

    local UIStroke_Copy = Instance.new("UIStroke")
    UIStroke_Copy.Color = Color3.fromRGB(154, 154, 154)
    UIStroke_Copy.Parent = CopyID

    local UIGradient_Copy = Instance.new("UIGradient")
    UIGradient_Copy.Rotation = -90
    UIGradient_Copy.Color = ColorSequence.new{
        ColorSequenceKeypoint.new(0, Color3.fromRGB(163, 163, 163)),
        ColorSequenceKeypoint.new(1, Color3.fromRGB(255, 255, 255))
    }
    UIGradient_Copy.Parent = CopyID

    local Ico_Copy = Instance.new("ImageLabel")
    Ico_Copy.ImageColor3 = Color3.fromRGB(197, 197, 197)
    Ico_Copy.BorderColor3 = Color3.fromRGB(0, 0, 0)
    Ico_Copy.Name = "Ico"
    Ico_Copy.Size = UDim2.new(0, 21, 0, 20)
    Ico_Copy.AnchorPoint = Vector2.new(0.5, 0.5)
    Ico_Copy.Image = "rbxassetid://16884178261"
    Ico_Copy.BackgroundTransparency = 1
    Ico_Copy.ImageRectSize = Vector2.new(36, 36)
    Ico_Copy.Position = UDim2.new(0.5, 0, 0.5, 0)
    Ico_Copy.BorderSizePixel = 0
    Ico_Copy.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
    Ico_Copy.Parent = CopyID

    CopyID.MouseButton1Click:Connect(function()
        print("Copied!")
        setclipboard(tostring(purchasedId))
    end)

    -- OpenProduct Button
    local OpenProduct = Instance.new("ImageButton")
    OpenProduct.ImageTransparency = 1
    OpenProduct.BorderColor3 = Color3.fromRGB(0, 0, 0)
    OpenProduct.AnchorPoint = Vector2.new(0.5, 0.5)
    OpenProduct.Name = "OpenProduct"
    OpenProduct.Position = UDim2.new(0.95, 0, 0.5, 0)
    OpenProduct.Size = UDim2.new(0, 24, 0, 23)
    OpenProduct.BorderSizePixel = 0
    OpenProduct.BackgroundColor3 = Color3.fromRGB(90, 99, 109)
    OpenProduct.Parent = Response

    local UICorner_Open = Instance.new("UICorner")
    UICorner_Open.CornerRadius = UDim.new(0, 6)
    UICorner_Open.Parent = OpenProduct

    local UIStroke_Open = Instance.new("UIStroke")
    UIStroke_Open.Color = Color3.fromRGB(154, 154, 154)
    UIStroke_Open.Parent = OpenProduct

    local UIGradient_Open = Instance.new("UIGradient")
    UIGradient_Open.Rotation = -90
    UIGradient_Open.Color = ColorSequence.new{
        ColorSequenceKeypoint.new(0, Color3.fromRGB(163, 163, 163)),
        ColorSequenceKeypoint.new(1, Color3.fromRGB(255, 255, 255))
    }
    UIGradient_Open.Parent = OpenProduct

    local Ico_Open = Instance.new("ImageLabel")
    Ico_Open.ImageColor3 = Color3.fromRGB(197, 197, 197)
    Ico_Open.BorderColor3 = Color3.fromRGB(0, 0, 0)
    Ico_Open.Name = "Ico"
    Ico_Open.Size = UDim2.new(0, 14, 0, 14)
    Ico_Open.Position = UDim2.new(0.5, 0, 0.5, 0)
    Ico_Open.AnchorPoint = Vector2.new(0.5, 0.5)
    Ico_Open.Image = "rbxassetid://16884179279"
    Ico_Open.BackgroundTransparency = 1
    Ico_Open.ImageRectSize = Vector2.new(48, 48)
    Ico_Open.ImageRectOffset = Vector2.new(690, 702)
    Ico_Open.BorderSizePixel = 0
    Ico_Open.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
    Ico_Open.Parent = OpenProduct

    OpenProduct.MouseButton1Click:Connect(function()
        ProductIDInput.Text = tostring(purchasedId)
        -- Switch to Action tab
        ScanTab.BackgroundColor3 = Color3.fromRGB(90, 99, 109)
        ListenerTab.BackgroundColor3 = Color3.fromRGB(90, 99, 109)
        ActionTab.BackgroundColor3 = Color3.fromRGB(104, 123, 165)
        scannerTabFrame.Visible = false
        listenerTabFrame.Visible = false
        actionTabFrame.Visible = true
    end)
end

-- ==================== SCANNER FUNCTIONALITY ====================
local function clearScanner()
    for _, child in ipairs(ScannerResults:GetChildren()) do
        if child:IsA("Frame") then child:Destroy() end
    end
end

local function scanGame()
    clearScanner()

    local foundProducts = {}
    local success, err = pcall(function()
        for _, obj in ipairs(game:GetDescendants()) do
            if obj:IsA("TextLabel") or obj:IsA("TextButton") or obj:IsA("TextBox") then
                local text = obj.Text or ""
                -- Look for product IDs in text (numbers that could be product IDs)
                for id in string.gmatch(text, "%d+") do
                    local numId = tonumber(id)
                    if numId and numId > 1000000 and numId < 999999999 then
                        table.insert(foundProducts, {Name = obj.Name, ID = numId, ParentName = obj.Parent and obj.Parent.Name or "Unknown"})
                    end
                end
            end
            -- Check for IntValues that might be product IDs
            if obj:IsA("IntValue") or obj:IsA("NumberValue") then
                local val = obj.Value
                if val and val > 1000000 and val < 999999999 then
                    table.insert(foundProducts, {Name = obj.Name, ID = val, ParentName = obj.Parent and obj.Parent.Name or "Unknown"})
                end
            end
            -- Check attributes
            for attrName, attrVal in pairs(obj:GetAttributes()) do
                if type(attrVal) == "number" and attrVal > 1000000 and attrVal < 999999999 then
                    table.insert(foundProducts, {Name = attrName, ID = attrVal, ParentName = obj.Name})
                end
            end
        end
    end)

    if not success then
        warn("Scan error: " .. tostring(err))
    end

    local total = #foundProducts
    if total == 0 then
        addLog("No products found", 0, false, ScannerResults)
        return
    end

    for _, product in ipairs(foundProducts) do
        addLog(product.Name .. " (" .. product.ParentName .. ")", product.ID, true, ScannerResults)
    end

    print("Scan complete! Found " .. total .. " products.")
end

ScanBtn.MouseButton1Click:Connect(function()
    scanGame()
end)

ReScanBtn.MouseButton1Click:Connect(function()
    scanGame()
end)

-- ==================== LISTENER EVENTS ====================
MarketplaceService.PromptProductPurchaseFinished:Connect(function(player, purchasedId, wasPurchased)
    print("Hook triggered for product:", purchasedId)
    print("Player:", player)
    print("WasPurchased:", wasPurchased)
    addLog(game:GetService("Players").LocalPlayer.Name, purchasedId, wasPurchased, listenerTabFrame)
end)
