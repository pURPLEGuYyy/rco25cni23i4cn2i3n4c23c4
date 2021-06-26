-- Gui to Lua
-- Version: 3.2

-- Instances:

local m = Instance.new("ScreenGui")
local Main = Instance.new("Frame")
local Title = Instance.new("TextLabel")
local SubTitle = Instance.new("TextLabel")
local TextLabel = Instance.new("TextLabel")
local Other = Instance.new("Frame")
local Other_2 = Instance.new("TextButton")
local UICorner = Instance.new("UICorner")
local ScrollingFrame = Instance.new("ScrollingFrame")
local Color = Instance.new("TextLabel")
local UICorner_2 = Instance.new("UICorner")
local TextButton = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local TextButton_2 = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local TextButton_3 = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local TextButton_4 = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local TextButton_5 = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local TextButton_6 = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")
local TextButton_7 = Instance.new("TextButton")
local UICorner_9 = Instance.new("UICorner")
local TextButton_8 = Instance.new("TextButton")
local UICorner_10 = Instance.new("UICorner")
local TextButton_9 = Instance.new("TextButton")
local UICorner_11 = Instance.new("UICorner")
local TextButton_10 = Instance.new("TextButton")
local UICorner_12 = Instance.new("UICorner")
local TextButton_11 = Instance.new("TextButton")
local UICorner_13 = Instance.new("UICorner")
local TextButton_12 = Instance.new("TextButton")
local UICorner_14 = Instance.new("UICorner")
local TextButton_13 = Instance.new("TextButton")
local UICorner_15 = Instance.new("UICorner")
local Other_3 = Instance.new("TextButton")
local UICorner_16 = Instance.new("UICorner")
local Other_4 = Instance.new("TextButton")
local UICorner_17 = Instance.new("UICorner")
local Other_5 = Instance.new("TextButton")
local UICorner_18 = Instance.new("UICorner")
local Other_6 = Instance.new("TextButton")
local UICorner_19 = Instance.new("UICorner")
local Other_7 = Instance.new("TextButton")
local UICorner_20 = Instance.new("UICorner")
local Other_8 = Instance.new("TextButton")
local UICorner_21 = Instance.new("UICorner")
local Other_9 = Instance.new("TextButton")
local UICorner_22 = Instance.new("UICorner")
local Other_10 = Instance.new("TextButton")
local UICorner_23 = Instance.new("UICorner")
local Other_11 = Instance.new("TextButton")
local UICorner_24 = Instance.new("UICorner")
local Other_12 = Instance.new("TextButton")
local UICorner_25 = Instance.new("UICorner")
local Other_13 = Instance.new("TextButton")
local Other_14 = Instance.new("TextButton")
local UICorner_26 = Instance.new("UICorner")
local TextButton_14 = Instance.new("TextButton")
local UICorner_27 = Instance.new("UICorner")
local Background = Instance.new("TextLabel")
local UICorner_28 = Instance.new("UICorner")
local Fun = Instance.new("Frame")
local Fun_2 = Instance.new("TextButton")
local UICorner_29 = Instance.new("UICorner")
local ScrollingFrame_2 = Instance.new("ScrollingFrame")
local FunScripts = Instance.new("TextLabel")
local UICorner_30 = Instance.new("UICorner")
local TextLabel_2 = Instance.new("TextLabel")
local HomeBrew = Instance.new("TextButton")
local BackFlip = Instance.new("TextButton")
local ComingSoon = Instance.new("TextButton")
local BigBoobs = Instance.new("TextButton")
local ImageButton = Instance.new("ImageButton")
local BackHelp = Instance.new("TextLabel")
local UICorner_31 = Instance.new("UICorner")
local MainM = Instance.new("Frame")
local Main_2 = Instance.new("TextButton")
local UICorner_32 = Instance.new("UICorner")
local ScrollingFrame_3 = Instance.new("ScrollingFrame")
local WalkSpeed = Instance.new("TextLabel")
local UICorner_33 = Instance.new("UICorner")
local Health = Instance.new("TextLabel")
local UICorner_34 = Instance.new("UICorner")
local JumpPower = Instance.new("TextLabel")
local UICorner_35 = Instance.new("UICorner")
local WalkValue = Instance.new("TextBox")
local UICorner_36 = Instance.new("UICorner")
local JumpValue = Instance.new("TextBox")
local UICorner_37 = Instance.new("UICorner")
local HValue = Instance.new("TextBox")
local UICorner_38 = Instance.new("UICorner")
local Walk = Instance.new("TextButton")
local UICorner_39 = Instance.new("UICorner")
local Health_2 = Instance.new("TextButton")
local UICorner_40 = Instance.new("UICorner")
local UICorner_41 = Instance.new("UICorner")
local Jump = Instance.new("TextButton")
local UICorner_42 = Instance.new("UICorner")
local AddCurrency = Instance.new("TextButton")
local UICorner_43 = Instance.new("UICorner")
local Amount = Instance.new("TextBox")
local UICorner_44 = Instance.new("UICorner")
local CurrencyName = Instance.new("TextBox")
local UICorner_45 = Instance.new("UICorner")
local Arsenal = Instance.new("TextButton")
local MM2 = Instance.new("TextButton")
local UICorner_46 = Instance.new("UICorner")
local TextLabel_3 = Instance.new("TextLabel")
local TextLabel_4 = Instance.new("TextLabel")
local Jailbreak = Instance.new("TextButton")
local UICorner_47 = Instance.new("UICorner")
local Brookhaven = Instance.new("TextButton")
local UICorner_48 = Instance.new("UICorner")
local RagdollSim = Instance.new("TextButton")
local UICorner_49 = Instance.new("UICorner")
local DaHood = Instance.new("TextButton")
local UICorner_50 = Instance.new("UICorner")
local Username = Instance.new("TextLabel")
local UICorner_51 = Instance.new("UICorner")
local UICorner_52 = Instance.new("UICorner")
local PlayerVictim = Instance.new("TextBox")
local UICorner_53 = Instance.new("UICorner")
local TextButton_15 = Instance.new("TextButton")
local UICorner_54 = Instance.new("UICorner")
local TextLabel_5 = Instance.new("TextLabel")


--Properties:

m.Name = "m"
m.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
m.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Main.Name = "Main"
Main.Parent = m
Main.Active = true
Main.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
Main.BorderColor3 = Color3.fromRGB(27, 42, 53)
Main.Position = UDim2.new(0.449999988, 0, 0.0900000036, 0)
Main.Selectable = true
Main.Size = UDim2.new(0, 500, 0, 600)
Main.Visible = true
Main.Draggable = true

Title.Name = "Title"
Title.Parent = Main
Title.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Title.BackgroundTransparency = 1.000
Title.Position = UDim2.new(0, 0, 0.0150000006, 0)
Title.Size = UDim2.new(0, 500, 0, 36)
Title.Font = Enum.Font.Ubuntu
Title.Text = "HENTAI "
Title.TextColor3 = Color3.fromRGB(255, 255, 255)
Title.TextScaled = true
Title.TextSize = 14.000
Title.TextWrapped = true

SubTitle.Name = "SubTitle"
SubTitle.Parent = Main
SubTitle.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
SubTitle.BackgroundTransparency = 1.000
SubTitle.Position = UDim2.new(0.345999986, 0, 0.075000003, 0)
SubTitle.Size = UDim2.new(0, 146, 0, 15)
SubTitle.Font = Enum.Font.Ubuntu
SubTitle.Text = "HUB"
SubTitle.TextColor3 = Color3.fromRGB(255, 255, 255)
SubTitle.TextScaled = true
SubTitle.TextSize = 14.000
SubTitle.TextWrapped = true

TextLabel.Parent = Main
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.Position = UDim2.new(0, 0, 0.971666694, 0)
TextLabel.Size = UDim2.new(0, 499, 0, 17)
TextLabel.Font = Enum.Font.Ubuntu
TextLabel.Text = "Discord: purple#0666"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

Other.Name = "Other"
Other.Parent = Main
Other.Active = true
Other.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Other.BackgroundTransparency = 1.000
Other.Selectable = true
Other.Size = UDim2.new(0, 500, 0, 600)


Other_2.Name = "Other"
Other_2.Parent = Other
Other_2.BackgroundColor3 = Color3.fromRGB(103, 103, 103)
Other_2.Position = UDim2.new(0, 361, 0, 70)
Other_2.Size = UDim2.new(0, 125, 0, 50)
Other_2.Font = Enum.Font.Ubuntu
Other_2.Text = "Configs"
Other_2.TextColor3 = Color3.fromRGB(0, 0, 0)
Other_2.TextSize = 30.000

UICorner.CornerRadius = UDim.new(0.0599999987, 0)
UICorner.Parent = Other_2

ScrollingFrame.Parent = Other
ScrollingFrame.Active = true
ScrollingFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ScrollingFrame.BackgroundTransparency = 1.000
ScrollingFrame.Position = UDim2.new(0.0299999993, 0, 0.219999999, 0)
ScrollingFrame.Size = UDim2.new(0, 471, 0, 443)
ScrollingFrame.Visible = false

Color.Name = "Color"
Color.Parent = ScrollingFrame
Color.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Color.BackgroundTransparency = 0.900
Color.Position = UDim2.new(0.0299999993, 0, 0, 30)
Color.Size = UDim2.new(0, 75, 0, 200)
Color.Font = Enum.Font.Ubuntu
Color.Text = "Scroll     Color"
Color.TextColor3 = Color3.fromRGB(255, 255, 255)
Color.TextSize = 25.000
Color.TextWrapped = true

UICorner_2.Parent = Color

TextButton.Parent = ScrollingFrame
TextButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton.Position = UDim2.new(0.220806792, 0, 0.0245043598, 0)
TextButton.Size = UDim2.new(0, 72, 0, 50)
TextButton.Font = Enum.Font.SourceSans
TextButton.Text = " "
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextSize = 14.000

UICorner_3.Parent = TextButton

TextButton_2.Parent = ScrollingFrame
TextButton_2.BackgroundColor3 = Color3.fromRGB(112, 13, 0)
TextButton_2.Position = UDim2.new(0.41401273, 0, 0.0245043598, 0)
TextButton_2.Size = UDim2.new(0, 72, 0, 50)
TextButton_2.Font = Enum.Font.SourceSans
TextButton_2.Text = " "
TextButton_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.TextSize = 14.000

UICorner_4.Parent = TextButton_2

TextButton_3.Parent = ScrollingFrame
TextButton_3.BackgroundColor3 = Color3.fromRGB(0, 255, 0)
TextButton_3.Position = UDim2.new(0.605095506, 0, 0.0245043598, 0)
TextButton_3.Size = UDim2.new(0, 72, 0, 50)
TextButton_3.Font = Enum.Font.SourceSans
TextButton_3.Text = " "
TextButton_3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_3.TextSize = 14.000

UICorner_5.Parent = TextButton_3

TextButton_4.Parent = ScrollingFrame
TextButton_4.BackgroundColor3 = Color3.fromRGB(0, 221, 255)
TextButton_4.BorderColor3 = Color3.fromRGB(0, 47, 53)
TextButton_4.Position = UDim2.new(0.789808869, 0, 0.0245043598, 0)
TextButton_4.Size = UDim2.new(0, 72, 0, 50)
TextButton_4.Font = Enum.Font.SourceSans
TextButton_4.Text = " "
TextButton_4.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_4.TextSize = 14.000
UICorner_6.Parent = TextButton_4

TextButton_5.Parent = ScrollingFrame
TextButton_5.BackgroundColor3 = Color3.fromRGB(255, 0, 166)
TextButton_5.Position = UDim2.new(0.220806792, 0, 0.0870043635, 0)
TextButton_5.Size = UDim2.new(0, 72, 0, 50)
TextButton_5.Font = Enum.Font.SourceSans
TextButton_5.Text = " "
TextButton_5.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_5.TextSize = 14.000

UICorner_7.Parent = TextButton_5

TextButton_6.Parent = ScrollingFrame
TextButton_6.BackgroundColor3 = Color3.fromRGB(143, 255, 102)
TextButton_6.Position = UDim2.new(0.41401273, 0, 0.0870043635, 0)
TextButton_6.Size = UDim2.new(0, 72, 0, 50)
TextButton_6.Font = Enum.Font.SourceSans
TextButton_6.Text = " "
TextButton_6.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_6.TextSize = 14.000

UICorner_8.Parent = TextButton_6

TextButton_7.Parent = ScrollingFrame
TextButton_7.BackgroundColor3 = Color3.fromRGB(85, 0, 255)
TextButton_7.Position = UDim2.new(0.605095506, 0, 0.0870043635, 0)
TextButton_7.Size = UDim2.new(0, 72, 0, 50)
TextButton_7.Font = Enum.Font.SourceSans
TextButton_7.Text = " "
TextButton_7.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_7.TextSize = 14.000

UICorner_9.Parent = TextButton_7

TextButton_8.Parent = ScrollingFrame
TextButton_8.BackgroundColor3 = Color3.fromRGB(0, 123, 255)
TextButton_8.Position = UDim2.new(0.789808869, 0, 0.0870043635, 0)
TextButton_8.Size = UDim2.new(0, 72, 0, 50)
TextButton_8.Font = Enum.Font.SourceSans
TextButton_8.Text = " "
TextButton_8.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_8.TextSize = 14.000
UICorner_10.Parent = TextButton_8

TextButton_9.Parent = ScrollingFrame
TextButton_9.BackgroundColor3 = Color3.fromRGB(124, 72, 100)
TextButton_9.Position = UDim2.new(0.220806792, 0, 0.149504364, 0)
TextButton_9.Size = UDim2.new(0, 72, 0, 50)
TextButton_9.Font = Enum.Font.SourceSans
TextButton_9.Text = " "
TextButton_9.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_9.TextSize = 14.000

UICorner_11.Parent = TextButton_9

TextButton_10.Parent = ScrollingFrame
TextButton_10.BackgroundColor3 = Color3.fromRGB(50, 83, 127)
TextButton_10.Position = UDim2.new(0.41401273, 0, 0.149504364, 0)
TextButton_10.Size = UDim2.new(0, 72, 0, 50)
TextButton_10.Font = Enum.Font.SourceSans
TextButton_10.Text = " "
TextButton_10.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_10.TextSize = 14.000

UICorner_12.Parent = TextButton_10

TextButton_11.Parent = ScrollingFrame
TextButton_11.BackgroundColor3 = Color3.fromRGB(129, 71, 139)
TextButton_11.Position = UDim2.new(0.605095506, 0, 0.149504364, 0)
TextButton_11.Size = UDim2.new(0, 72, 0, 50)
TextButton_11.Font = Enum.Font.SourceSans
TextButton_11.Text = " "
TextButton_11.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_11.TextSize = 14.000

UICorner_13.Parent = TextButton_11

TextButton_12.Parent = ScrollingFrame
TextButton_12.BackgroundColor3 = Color3.fromRGB(141, 36, 36)
TextButton_12.Position = UDim2.new(0.789808869, 0, 0.149504364, 0)
TextButton_12.Size = UDim2.new(0, 72, 0, 50)
TextButton_12.Font = Enum.Font.SourceSans
TextButton_12.Text = " "
TextButton_12.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_12.TextSize = 14.000

UICorner_14.Parent = TextButton_12

TextButton_13.Parent = ScrollingFrame
TextButton_13.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
TextButton_13.BorderColor3 = Color3.fromRGB(255, 255, 255)
TextButton_13.BorderSizePixel = 2
TextButton_13.Position = UDim2.new(0.0297239907, 0, 0.200000003, 0)
TextButton_13.Size = UDim2.new(0, 430, 0, 50)
TextButton_13.Font = Enum.Font.Ubuntu
TextButton_13.Text = "Default Color"
TextButton_13.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_13.TextSize = 30.000
TextButton_13.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
TextButton_13.TextWrapped = true

UICorner_15.Parent = TextButton_13

Other_3.Name = "Other"
Other_3.Parent = ScrollingFrame
Other_3.BackgroundColor3 = Color3.fromRGB(56, 124, 52)
Other_3.Position = UDim2.new(0.220806792, 0, 0.256171048, 0)
Other_3.Size = UDim2.new(0, 72, 0, 50)
Other_3.Font = Enum.Font.SourceSans
Other_3.Text = " "
Other_3.TextColor3 = Color3.fromRGB(0, 0, 0)
Other_3.TextSize = 14.000

UICorner_16.Parent = Other_3

Other_4.Name = "Other"
Other_4.Parent = ScrollingFrame
Other_4.BackgroundColor3 = Color3.fromRGB(141, 36, 36)
Other_4.Position = UDim2.new(0.789808869, 0, 0.256171048, 0)
Other_4.Size = UDim2.new(0, 72, 0, 50)
Other_4.Font = Enum.Font.SourceSans
Other_4.Text = " "
Other_4.TextColor3 = Color3.fromRGB(0, 0, 0)
Other_4.TextSize = 14.000

UICorner_17.Parent = Other_4

Other_5.Name = "Other"
Other_5.Parent = ScrollingFrame
Other_5.BackgroundColor3 = Color3.fromRGB(53, 88, 134)
Other_5.Position = UDim2.new(0.41401273, 0, 0.256171048, 0)
Other_5.Size = UDim2.new(0, 72, 0, 50)
Other_5.Font = Enum.Font.SourceSans
Other_5.Text = " "
Other_5.TextColor3 = Color3.fromRGB(0, 0, 0)
Other_5.TextSize = 14.000

UICorner_18.Parent = Other_5

Other_6.Name = "Other"
Other_6.Parent = ScrollingFrame
Other_6.BackgroundColor3 = Color3.fromRGB(129, 71, 139)
Other_6.Position = UDim2.new(0.605095506, 0, 0.256171048, 0)
Other_6.Size = UDim2.new(0, 72, 0, 50)
Other_6.Font = Enum.Font.SourceSans
Other_6.Text = " "
Other_6.TextColor3 = Color3.fromRGB(0, 0, 0)
Other_6.TextSize = 14.000

UICorner_19.Parent = Other_6

Other_7.Name = "Other"
Other_7.Parent = ScrollingFrame
Other_7.BackgroundColor3 = Color3.fromRGB(41, 90, 37)
Other_7.Position = UDim2.new(0.220806792, 0, 0.30950439, 0)
Other_7.Size = UDim2.new(0, 72, 0, 50)
Other_7.Font = Enum.Font.SourceSans
Other_7.Text = " "
Other_7.TextColor3 = Color3.fromRGB(0, 0, 0)
Other_7.TextSize = 14.000

UICorner_20.Parent = Other_7

Other_8.Name = "Other"
Other_8.Parent = ScrollingFrame
Other_8.BackgroundColor3 = Color3.fromRGB(34, 56, 86)
Other_8.Position = UDim2.new(0.41401273, 0, 0.30950439, 0)
Other_8.Size = UDim2.new(0, 72, 0, 50)
Other_8.Font = Enum.Font.SourceSans
Other_8.Text = " "
Other_8.TextColor3 = Color3.fromRGB(0, 0, 0)
Other_8.TextSize = 14.000

UICorner_21.Parent = Other_8

Other_9.Name = "Other"
Other_9.Parent = ScrollingFrame
Other_9.BackgroundColor3 = Color3.fromRGB(97, 24, 24)
Other_9.Position = UDim2.new(0.789808869, 0, 0.30950439, 0)
Other_9.Size = UDim2.new(0, 72, 0, 50)
Other_9.Font = Enum.Font.SourceSans
Other_9.Text = " "
Other_9.TextColor3 = Color3.fromRGB(0, 0, 0)
Other_9.TextSize = 14.000

UICorner_22.Parent = Other_9

Other_10.Name = "Other"
Other_10.Parent = ScrollingFrame
Other_10.BackgroundColor3 = Color3.fromRGB(83, 46, 90)
Other_10.Position = UDim2.new(0.605095506, 0, 0.30950439, 0)
Other_10.Size = UDim2.new(0, 72, 0, 50)
Other_10.Font = Enum.Font.SourceSans
Other_10.Text = " "
Other_10.TextColor3 = Color3.fromRGB(0, 0, 0)
Other_10.TextSize = 14.000

UICorner_23.Parent = Other_10

Other_11.Name = "Other"
Other_11.Parent = ScrollingFrame
Other_11.BackgroundColor3 = Color3.fromRGB(26, 58, 24)
Other_11.Position = UDim2.new(0.220806792, 0, 0.362837732, 0)
Other_11.Size = UDim2.new(0, 72, 0, 50)
Other_11.Font = Enum.Font.SourceSans
Other_11.Text = " "
Other_11.TextColor3 = Color3.fromRGB(0, 0, 0)
Other_11.TextSize = 14.000

UICorner_24.Parent = Other_11

Other_12.Name = "Other"
Other_12.Parent = ScrollingFrame
Other_12.BackgroundColor3 = Color3.fromRGB(27, 44, 68)
Other_12.Position = UDim2.new(0.41401273, 0, 0.362837732, 0)
Other_12.Size = UDim2.new(0, 72, 0, 50)
Other_12.Font = Enum.Font.SourceSans
Other_12.Text = " "
Other_12.TextColor3 = Color3.fromRGB(0, 0, 0)
Other_12.TextSize = 14.000

UICorner_25.Parent = Other_12

Other_13.Name = "Other"
Other_13.Parent = ScrollingFrame
Other_13.BackgroundColor3 = Color3.fromRGB(70, 17, 17)
Other_13.Position = UDim2.new(0.789808869, 0, 0.362837732, 0)
Other_13.Size = UDim2.new(0, 72, 0, 50)
Other_13.Font = Enum.Font.SourceSans
Other_13.Text = " "
Other_13.TextColor3 = Color3.fromRGB(0, 0, 0)
Other_13.TextSize = 14.000

Other_14.Name = "Other"
Other_14.Parent = ScrollingFrame
Other_14.BackgroundColor3 = Color3.fromRGB(53, 29, 58)
Other_14.Position = UDim2.new(0.605095506, 0, 0.362837732, 0)
Other_14.Size = UDim2.new(0, 72, 0, 50)
Other_14.Font = Enum.Font.SourceSans
Other_14.Text = " "
Other_14.TextColor3 = Color3.fromRGB(0, 0, 0)
Other_14.TextSize = 14.000

UICorner_26.Parent = Other_14

TextButton_14.Parent = ScrollingFrame
TextButton_14.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
TextButton_14.BorderColor3 = Color3.fromRGB(255, 255, 255)
TextButton_14.BorderSizePixel = 2
TextButton_14.Position = UDim2.new(0.027600849, 0, 0.415833354, 0)
TextButton_14.Size = UDim2.new(0, 430, 0, 50)
TextButton_14.Font = Enum.Font.Ubuntu
TextButton_14.Text = "Default Color"
TextButton_14.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_14.TextSize = 30.000
TextButton_14.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
TextButton_14.TextWrapped = true

UICorner_27.Parent = TextButton_14

Background.Name = "Background"
Background.Parent = ScrollingFrame
Background.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Background.BackgroundTransparency = 0.900
Background.Position = UDim2.new(0.0257537141, 0, 0.224166662, 30)
Background.Size = UDim2.new(0, 75, 0, 200)
Background.Font = Enum.Font.Ubuntu
Background.Text = "Back   Color"
Background.TextColor3 = Color3.fromRGB(255, 255, 255)
Background.TextSize = 25.000
Background.TextWrapped = true

UICorner_28.Parent = Background

Fun.Name = "Fun"
Fun.Parent = Main
Fun.Active = true
Fun.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Fun.BackgroundTransparency = 1.000
Fun.Selectable = true
Fun.Size = UDim2.new(0, 500, 0, 600)

Fun_2.Name = "Fun"
Fun_2.Parent = Fun
Fun_2.BackgroundColor3 = Color3.fromRGB(103, 103, 103)
Fun_2.Position = UDim2.new(0, 191, 0, 70)
Fun_2.Size = UDim2.new(0, 118, 0, 50)
Fun_2.Font = Enum.Font.Ubuntu
Fun_2.Text = "Fun"
Fun_2.TextColor3 = Color3.fromRGB(0, 0, 0)
Fun_2.TextSize = 30.000
Fun_2.TextWrapped = true

UICorner_29.CornerRadius = UDim.new(0.0599999987, 0)
UICorner_29.Parent = Fun_2

ScrollingFrame_2.Parent = Fun
ScrollingFrame_2.Active = true
ScrollingFrame_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ScrollingFrame_2.BackgroundTransparency = 1.000
ScrollingFrame_2.Position = UDim2.new(0.0299999993, 0, 0.219999999, 0)
ScrollingFrame_2.Size = UDim2.new(0, 471, 0, 443)
ScrollingFrame_2.Visible = false

FunScripts.Name = "FunScripts"
FunScripts.Parent = ScrollingFrame_2
FunScripts.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
FunScripts.BackgroundTransparency = 0.900
FunScripts.Position = UDim2.new(0.280530781, 0, -0.00749999983, 30)
FunScripts.Size = UDim2.new(0, 200, 0, 50)
FunScripts.Font = Enum.Font.Ubuntu
FunScripts.Text = "Fun Scripts"
FunScripts.TextColor3 = Color3.fromRGB(255, 255, 255)
FunScripts.TextSize = 25.000
FunScripts.TextWrapped = true

UICorner_30.Parent = FunScripts

TextLabel_2.Parent = ScrollingFrame_2
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.Position = UDim2.new(0.280254781, 0, 0.0586042181, 0)
TextLabel_2.Size = UDim2.new(0, 200, 0, 31)
TextLabel_2.Font = Enum.Font.Ubuntu
TextLabel_2.Text = "Some Scripts might require paid executers."
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextScaled = true
TextLabel_2.TextSize = 14.000
TextLabel_2.TextWrapped = true

HomeBrew.Name = "HomeBrew"
HomeBrew.Parent = ScrollingFrame_2
HomeBrew.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
HomeBrew.BackgroundTransparency = 0.900
HomeBrew.Position = UDim2.new(0.0191082843, 0, 0.104999989, 0)
HomeBrew.Size = UDim2.new(0, 200, 0, 50)
HomeBrew.Font = Enum.Font.Ubuntu
HomeBrew.Text = "HomeBrew"
HomeBrew.TextColor3 = Color3.fromRGB(255, 255, 255)
HomeBrew.TextSize = 30.000
HomeBrew.TextWrapped = true
HomeBrew.MouseButton1Click:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/AMHdfKcy"))() --loadstring(game:HttpGet("https://pastebin.com/raw/AMHdfKcy"))() --
end)

BackFlip.Name = "BackFlip"
BackFlip.Parent = ScrollingFrame_2
BackFlip.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
BackFlip.BackgroundTransparency = 0.900
BackFlip.Position = UDim2.new(0.507430971, 0, 0.104999989, 0)
BackFlip.Size = UDim2.new(0, 200, 0, 50)
BackFlip.Font = Enum.Font.Ubuntu
BackFlip.Text = "BackFlip+"
BackFlip.TextColor3 = Color3.fromRGB(255, 255, 255)
BackFlip.TextSize = 30.000
BackFlip.MouseButton1Click:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/J4GHjy17"))() --
end)

ComingSoon.Name = "Coming Soon"
ComingSoon.Parent = ScrollingFrame_2
ComingSoon.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ComingSoon.BackgroundTransparency = 0.900
ComingSoon.Position = UDim2.new(0.507430971, 0, 0.164999992, 0)
ComingSoon.Size = UDim2.new(0, 200, 0, 50)
ComingSoon.Font = Enum.Font.Ubuntu
ComingSoon.Text = "Coming Soon.."
ComingSoon.TextColor3 = Color3.fromRGB(255, 255, 255)
ComingSoon.TextSize = 30.000

BigBoobs.Name = "BigBoobs"
BigBoobs.Parent = ScrollingFrame_2
BigBoobs.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
BigBoobs.BackgroundTransparency = 0.900
BigBoobs.Position = UDim2.new(0.0191082843, 0, 0.164999992, 0)
BigBoobs.Size = UDim2.new(0, 200, 0, 50)
BigBoobs.Font = Enum.Font.Ubuntu
BigBoobs.Text = "BigB00BS"
BigBoobs.TextColor3 = Color3.fromRGB(255, 255, 255)
BigBoobs.TextSize = 30.000
BigBoobs.MouseButton1Click:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/bigjohnny1234/Interaxis-hub/main/README.md"))() --
end)


ImageButton.Parent = ScrollingFrame_2
ImageButton.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageButton.BackgroundTransparency = 1.000
ImageButton.Position = UDim2.new(0.88322711, 0, 0.0958333388, 0)
ImageButton.Size = UDim2.new(0, 30, 0, 30)
ImageButton.Image = "rbxassetid://1182449266"

BackHelp.Name = "BackHelp"
BackHelp.Parent = ScrollingFrame_2
BackHelp.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
BackHelp.BackgroundTransparency = 0.650
BackHelp.Position = UDim2.new(0.17197451, 0, 0.288333327, 0)
BackHelp.Size = UDim2.new(0, 300, 0, 50)
BackHelp.Visible = false
BackHelp.Font = Enum.Font.Ubuntu
BackHelp.Text = "Z - Front Flip\\nX - Backflip\\nC - Infinite Jump"
BackHelp.TextColor3 = Color3.fromRGB(255, 255, 255)
BackHelp.TextScaled = true
BackHelp.TextSize = 14.000
BackHelp.TextWrapped = true

UICorner_31.Parent = BackHelp

MainM.Name = "MainM"
MainM.Parent = Main
MainM.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
MainM.BackgroundTransparency = 1.000
MainM.Size = UDim2.new(0, 500, 0, 600)

Main_2.Name = "Main"
Main_2.Parent = MainM
Main_2.BackgroundColor3 = Color3.fromRGB(103, 103, 103)
Main_2.Position = UDim2.new(0, 15, 0, 70)
Main_2.Size = UDim2.new(0, 125, 0, 50)
Main_2.Font = Enum.Font.Ubuntu
Main_2.Text = "Main"
Main_2.TextColor3 = Color3.fromRGB(0, 0, 0)
Main_2.TextSize = 30.000

UICorner_32.CornerRadius = UDim.new(0.0599999987, 0)
UICorner_32.Parent = Main_2

ScrollingFrame_3.Parent = MainM
ScrollingFrame_3.Active = true
ScrollingFrame_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ScrollingFrame_3.BackgroundTransparency = 1.000
ScrollingFrame_3.Position = UDim2.new(0.0299999993, 0, 0.219999999, 0)
ScrollingFrame_3.Size = UDim2.new(0, 471, 0, 443)

WalkSpeed.Name = "WalkSpeed"
WalkSpeed.Parent = ScrollingFrame_3
WalkSpeed.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
WalkSpeed.BackgroundTransparency = 0.900
WalkSpeed.Position = UDim2.new(0.0299999993, 0, 0, 30)
WalkSpeed.Size = UDim2.new(0, 200, 0, 50)
WalkSpeed.Font = Enum.Font.Ubuntu
WalkSpeed.Text = "Walk Speed"
WalkSpeed.TextColor3 = Color3.fromRGB(255, 255, 255)
WalkSpeed.TextSize = 25.000
WalkSpeed.TextWrapped = true

UICorner_33.CornerRadius = UDim.new(0.0799999982, 0)
UICorner_33.Parent = WalkSpeed

Health.Name = "Health"
Health.Parent = ScrollingFrame_3
Health.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Health.BackgroundTransparency = 0.900
Health.Position = UDim2.new(0.0299999993, 0, 0, 100)
Health.Size = UDim2.new(0, 200, 0, 50)
Health.Font = Enum.Font.Ubuntu
Health.Text = "Health"
Health.TextColor3 = Color3.fromRGB(255, 255, 255)
Health.TextSize = 25.000
Health.TextWrapped = true

UICorner_34.CornerRadius = UDim.new(0.0799999982, 0)
UICorner_34.Parent = Health

JumpPower.Name = "JumpPower"
JumpPower.Parent = ScrollingFrame_3
JumpPower.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
JumpPower.BackgroundTransparency = 0.900
JumpPower.Position = UDim2.new(0.0299999993, 0, 0, 170)
JumpPower.Size = UDim2.new(0, 200, 0, 50)
JumpPower.Font = Enum.Font.Ubuntu
JumpPower.Text = "Jump Power"
JumpPower.TextColor3 = Color3.fromRGB(255, 255, 255)
JumpPower.TextSize = 25.000
JumpPower.TextWrapped = true

UICorner_35.CornerRadius = UDim.new(0.0799999982, 0)
UICorner_35.Parent = JumpPower

WalkValue.Name = "WalkValue"
WalkValue.Parent = ScrollingFrame_3
WalkValue.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
WalkValue.BackgroundTransparency = 0.600
WalkValue.Position = UDim2.new(0.513630569, 0, 0.025000006, 0)
WalkValue.Size = UDim2.new(0, 77, 0, 50)
WalkValue.Font = Enum.Font.SourceSans
WalkValue.PlaceholderColor3 = Color3.fromRGB(49, 49, 49)
WalkValue.Text = ""
WalkValue.TextColor3 = Color3.fromRGB(223, 223, 223)
WalkValue.TextScaled = true
WalkValue.TextSize = 26.000
WalkValue.TextWrapped = true

UICorner_36.Parent = WalkValue

JumpValue.Name = "JumpValue"
JumpValue.Parent = ScrollingFrame_3
JumpValue.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
JumpValue.BackgroundTransparency = 0.600
JumpValue.Position = UDim2.new(0.513630569, 0, 0.141666681, 0)
JumpValue.Size = UDim2.new(0, 77, 0, 50)
JumpValue.Font = Enum.Font.SourceSans
JumpValue.PlaceholderColor3 = Color3.fromRGB(49, 49, 49)
JumpValue.Text = ""
JumpValue.TextColor3 = Color3.fromRGB(223, 223, 223)
JumpValue.TextScaled = true
JumpValue.TextSize = 26.000
JumpValue.TextWrapped = true

UICorner_37.Parent = JumpValue

HValue.Name = "HValue"
HValue.Parent = ScrollingFrame_3
HValue.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
HValue.BackgroundTransparency = 0.600
HValue.Position = UDim2.new(0.513630569, 0, 0.0833333433, 0)
HValue.Size = UDim2.new(0, 77, 0, 50)
HValue.Font = Enum.Font.SourceSans
HValue.PlaceholderColor3 = Color3.fromRGB(49, 49, 49)
HValue.Text = ""
HValue.TextColor3 = Color3.fromRGB(223, 223, 223)
HValue.TextScaled = true
HValue.TextSize = 26.000
HValue.TextWrapped = true

UICorner_38.Parent = HValue

Walk.Name = "Walk"
Walk.Parent = ScrollingFrame_3
Walk.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Walk.BackgroundTransparency = 0.900
Walk.Position = UDim2.new(0.717622221, 0, 0.0243867598, 0)
Walk.Size = UDim2.new(0, 97, 0, 50)
Walk.Font = Enum.Font.Ubuntu
Walk.Text = "Change"
Walk.TextColor3 = Color3.fromRGB(255, 255, 255)
Walk.TextSize = 25.000

UICorner_39.Parent = Walk

Health_2.Name = "Health"
Health_2.Parent = ScrollingFrame_3
Health_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Health_2.BackgroundTransparency = 0.900
Health_2.Position = UDim2.new(0.717999995, 0, 0.0579999983, 30)
Health_2.Size = UDim2.new(0, 97, 0, 50)
Health_2.Font = Enum.Font.Ubuntu
Health_2.Text = "Change "
Health_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Health_2.TextSize = 25.000
Health_2.TextWrapped = true

UICorner_40.Parent = Health_2

UICorner_41.Parent = Health_2

Jump.Name = "Jump"
Jump.Parent = ScrollingFrame_3
Jump.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Jump.BackgroundTransparency = 0.900
Jump.Position = UDim2.new(0.717622221, 0, 0.141053423, 0)
Jump.Size = UDim2.new(0, 97, 0, 50)
Jump.Font = Enum.Font.Ubuntu
Jump.Text = "Change"
Jump.TextColor3 = Color3.fromRGB(255, 255, 255)
Jump.TextSize = 25.000
Jump.TextWrapped = true

UICorner_42.CornerRadius = UDim.new(0.0799999982, 0)
UICorner_42.Parent = Jump

AddCurrency.Name = "AddCurrency"
AddCurrency.Parent = ScrollingFrame_3
AddCurrency.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
AddCurrency.BackgroundTransparency = 0.900
AddCurrency.Position = UDim2.new(0.717622221, 0, 0.201053426, 0)
AddCurrency.Size = UDim2.new(0, 97, 0, 50)
AddCurrency.Font = Enum.Font.Ubuntu
AddCurrency.Text = "Add"
AddCurrency.TextColor3 = Color3.fromRGB(255, 255, 255)
AddCurrency.TextSize = 25.000
AddCurrency.TextWrapped = true

UICorner_43.Parent = AddCurrency

Amount.Name = "Amount"
Amount.Parent = ScrollingFrame_3
Amount.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Amount.BackgroundTransparency = 0.600
Amount.Position = UDim2.new(0.513630569, 0, 0.201666683, 0)
Amount.Size = UDim2.new(0, 77, 0, 50)
Amount.Font = Enum.Font.SourceSans
Amount.PlaceholderColor3 = Color3.fromRGB(49, 49, 49)
Amount.Text = ""
Amount.TextColor3 = Color3.fromRGB(223, 223, 223)
Amount.TextScaled = true
Amount.TextSize = 26.000
Amount.TextWrapped = true

UICorner_44.Parent = Amount

CurrencyName.Name = "CurrencyName"
CurrencyName.Parent = ScrollingFrame_3
CurrencyName.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
CurrencyName.BackgroundTransparency = 0.900
CurrencyName.Position = UDim2.new(0.0297239907, 0, 0.200833336, 0)
CurrencyName.Size = UDim2.new(0, 200, 0, 50)
CurrencyName.Font = Enum.Font.Ubuntu
CurrencyName.Text = "Currency Name"
CurrencyName.TextColor3 = Color3.fromRGB(255, 255, 255)
CurrencyName.TextSize = 25.000

print ("everything loaded")

UICorner_45.CornerRadius = UDim.new(0.0799999982, 0)
UICorner_45.Parent = CurrencyName

Arsenal.Name = "Arsenal"
Arsenal.Parent = ScrollingFrame_3
Arsenal.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Arsenal.BackgroundTransparency = 0.900
Arsenal.Position = UDim2.new(0.278131634, 0, 0.349999994, 0)
Arsenal.Size = UDim2.new(0, 200, 0, 50)
Arsenal.Font = Enum.Font.Ubuntu
Arsenal.Text = "Arsenal"
Arsenal.TextColor3 = Color3.fromRGB(255, 255, 255)
Arsenal.TextSize = 30.000
Arsenal.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/RandomAdamYT/DarkHub/master/Init", true))() -- work
end)

print("arsenal worked")

MM2.Name = "MM2"
MM2.Parent = ScrollingFrame_3
MM2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
MM2.BackgroundTransparency = 0.900
MM2.Position = UDim2.new(0.278131634, 0, 0.400000006, 0)
MM2.Size = UDim2.new(0, 200, 0, 50)
MM2.Font = Enum.Font.Ubuntu
MM2.Text = "MM2"
MM2.TextColor3 = Color3.fromRGB(255, 255, 255)
MM2.TextSize = 30.000
MM2.MouseButton1Down:connect(function()
	loadstring(game:GetObjects("rbxassetid://4001118261")[1].Source)()
end)

print("mm2 worked")

UICorner_46.CornerRadius = UDim.new(0.0799999982, 0)
UICorner_46.Parent = MM2

TextLabel_3.Parent = ScrollingFrame_3
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.BackgroundTransparency = 1.000
TextLabel_3.Position = UDim2.new(0.0297239907, 0, 0.25, 0)
TextLabel_3.Size = UDim2.new(0, 420, 0, 40)
TextLabel_3.Font = Enum.Font.Ubuntu
TextLabel_3.Text = "This Option will only work if the Currency is in the leaderstats."
TextLabel_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.TextSize = 20.000
TextLabel_3.TextWrapped = true

TextLabel_4.Parent = ScrollingFrame_3
TextLabel_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.BackgroundTransparency = 1.000
TextLabel_4.Position = UDim2.new(0.0297239907, 0, 0.300000012, 0)
TextLabel_4.Size = UDim2.new(0, 420, 0, 40)
TextLabel_4.Font = Enum.Font.Ubuntu
TextLabel_4.Text = "Game Scripts"
TextLabel_4.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.TextSize = 40.000
TextLabel_4.TextWrapped = true

Jailbreak.Name = "Jailbreak"
Jailbreak.Parent = ScrollingFrame_3
Jailbreak.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Jailbreak.BackgroundTransparency = 0.900
Jailbreak.Position = UDim2.new(0.278131634, 0, 0.450000018, 0)
Jailbreak.Size = UDim2.new(0, 200, 0, 50)
Jailbreak.Font = Enum.Font.Ubuntu
Jailbreak.Text = "Jailbreak"
Jailbreak.TextColor3 = Color3.fromRGB(255, 255, 255)
Jailbreak.TextSize = 30.000
Jailbreak.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://gist.githubus"))()
end)

print("jailbreak worked")

UICorner_47.CornerRadius = UDim.new(0.0799999982, 0)
UICorner_47.Parent = Jailbreak

Brookhaven.Name = "Brookhaven"
Brookhaven.Parent = ScrollingFrame_3
Brookhaven.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Brookhaven.BackgroundTransparency = 0.900
Brookhaven.Position = UDim2.new(0.278131634, 0, 0.500833333, 0)
Brookhaven.Size = UDim2.new(0, 200, 0, 50)
Brookhaven.Font = Enum.Font.Ubuntu
Brookhaven.Text = "Brookhaven"
Brookhaven.TextColor3 = Color3.fromRGB(255, 255, 255)
Brookhaven.TextSize = 30.000
Brookhaven.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://gist.githubusercontent.com/TurkOyuncu99/60832e7d04766a6381194d7502fbb1e8/raw/fbecd900a62e1fa054998f02084475b6c4ed8f18/woah", true))()
end)

print("brookhaven worked")

UICorner_48.CornerRadius = UDim.new(0.0799999982, 0)
UICorner_48.Parent = Brookhaven

RagdollSim.Name = "RagdollSim"
RagdollSim.Parent = ScrollingFrame_3
RagdollSim.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
RagdollSim.BackgroundTransparency = 0.900
RagdollSim.Position = UDim2.new(0.278131634, 0, 0.550833344, 0)
RagdollSim.Size = UDim2.new(0, 200, 0, 50)
RagdollSim.Font = Enum.Font.Ubuntu
RagdollSim.Text = "Ragdoll"
RagdollSim.TextColor3 = Color3.fromRGB(255, 255, 255)
RagdollSim.TextSize = 30.000
RagdollSim.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://bruh.keshhub.com/.lua"))()
end)

print("ragdoll worked")

UICorner_49.CornerRadius = UDim.new(0.0799999982, 0)
UICorner_49.Parent = RagdollSim

DaHood.Name = "DaHood"
DaHood.Parent = ScrollingFrame_3
DaHood.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
DaHood.BackgroundTransparency = 0.900
DaHood.Position = UDim2.new(0.278131634, 0, 0.601666689, 0)
DaHood.Size = UDim2.new(0, 200, 0, 50)
DaHood.Font = Enum.Font.Ubuntu
DaHood.Text = "DaHood"
DaHood.TextColor3 = Color3.fromRGB(255, 255, 255)
DaHood.TextSize = 30.000
DaHood.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/pURPLEGuYyy/2c412c412c412c412c412c4/main/README.md", true))()
end)

print("dahood worked")

UICorner_50.CornerRadius = UDim.new(0.0799999982, 0)
UICorner_50.Parent = DaHood

Username.Name = "Username"
Username.Parent = Main
Username.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Username.BackgroundTransparency = 0.700
Username.Position = UDim2.new(0.0199999996, 0, 0.0169999953, 0)
Username.Size = UDim2.new(0, 163, 0, 35)
Username.Font = Enum.Font.Ubuntu
Username.Text = "Username"
Username.TextColor3 = Color3.fromRGB(255, 255, 255)
Username.TextSize = 25.000
Username.TextWrapped = true

UICorner_51.Parent = Username

UICorner_52.CornerRadius = UDim.new(0.0250000004, 0)
UICorner_52.Parent = Main

PlayerVictim.Name = "PlayerVictim"
PlayerVictim.Parent = Main
PlayerVictim.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
PlayerVictim.BackgroundTransparency = 0.700
PlayerVictim.Position = UDim2.new(0.638000011, 0, 0.0166666675, 0)
PlayerVictim.Size = UDim2.new(0, 168, 0, 35)
PlayerVictim.Font = Enum.Font.Ubuntu
PlayerVictim.Text = "Victim"
PlayerVictim.TextColor3 = Color3.fromRGB(255, 255, 255)
PlayerVictim.TextSize = 25.000

UICorner_53.Parent = PlayerVictim

TextButton_15.Parent = Main
TextButton_15.BackgroundColor3 = Color3.fromRGB(30, 25, 25)
TextButton_15.Position = UDim2.new(0.0299999993, 0, -0.0350000001, 0)
TextButton_15.Size = UDim2.new(0, 465, 0, 21)
TextButton_15.Font = Enum.Font.Ubuntu
TextButton_15.Text = "Close"
TextButton_15.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_15.TextSize = 20.000

UICorner_54.Parent = TextButton_15

TextLabel_5.Parent = Main
TextLabel_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_5.BackgroundTransparency = 1.000
TextLabel_5.Position = UDim2.new(0.74000001, 0, 0.943333328, 0)
TextLabel_5.Size = UDim2.new(0, 200, 0, 50)
TextLabel_5.Font = Enum.Font.Ubuntu
TextLabel_5.Text = "v 1.1"
TextLabel_5.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_5.TextSize = 15.000

-- Scripts:

local function IMSHW_fake_script() -- Main.DragTrue 
	local script = Instance.new('LocalScript', Main)

	script.Parent.Draggable = true
end
coroutine.wrap(IMSHW_fake_script)()
local function XUEIL_fake_script() -- Other_2.LocalScript 
	local script = Instance.new('LocalScript', Other_2)

	script.Parent.MouseButton1Down:connect(function()
		script.Parent.Parent.Parent.MainM.ScrollingFrame.Visible = false
		script.Parent.Parent.Parent.Fun.ScrollingFrame.Visible = false
		script.Parent.Parent.Parent.Other.ScrollingFrame.Visible = true
	end)
end
print("line 1096 check")
coroutine.wrap(XUEIL_fake_script)()
local function NSGDI_fake_script() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript', TextButton)

	script.Parent.MouseButton1Click:Connect(function()
		local Players = game:GetService("Players")
		local player = Players.LocalPlayer
		local playerGui = player:WaitForChild("PlayerGui")
		local color = script.Parent.BackgroundColor3
		local scroll1 = playerGui:WaitForChild("m"):WaitForChild("Main"):WaitForChild("Other"):WaitForChild("ScrollingFrame")
		local scroll2 = playerGui:WaitForChild("m"):WaitForChild("Main"):WaitForChild("Fun"):WaitForChild("ScrollingFrame")
		local scroll3 = playerGui:WaitForChild("m"):WaitForChild("Main"):WaitForChild("MainM"):WaitForChild("ScrollingFrame")
		scroll1.ScrollBarImageColor3 = color
		scroll2.ScrollBarImageColor3 = color
		scroll3.ScrollBarImageColor3 = color
	end)
end
coroutine.wrap(NSGDI_fake_script)()
local function HERXF_fake_script() -- TextButton_2.LocalScript 
	local script = Instance.new('LocalScript', TextButton_2)

	script.Parent.MouseButton1Click:Connect(function()
		local Players = game:GetService("Players")
		local player = Players.LocalPlayer
		local playerGui = player:WaitForChild("PlayerGui")
		local color = script.Parent.BackgroundColor3
		local scroll1 = playerGui:WaitForChild("m"):WaitForChild("Main"):WaitForChild("Other"):WaitForChild("ScrollingFrame")
		local scroll2 = playerGui:WaitForChild("m"):WaitForChild("Main"):WaitForChild("Fun"):WaitForChild("ScrollingFrame")
		local scroll3 = playerGui:WaitForChild("m"):WaitForChild("Main"):WaitForChild("MainM"):WaitForChild("ScrollingFrame")
		scroll1.ScrollBarImageColor3 = color
		scroll2.ScrollBarImageColor3 = color
		scroll3.ScrollBarImageColor3 = color
	end)
end
print("line 1131 check")
coroutine.wrap(HERXF_fake_script)()
local function ZYOEXLU_fake_script() -- TextButton_3.LocalScript 
	local script = Instance.new('LocalScript', TextButton_3)

	script.Parent.MouseButton1Click:Connect(function()
		local Players = game:GetService("Players")
		local player = Players.LocalPlayer
		local playerGui = player:WaitForChild("PlayerGui")
		local color = script.Parent.BackgroundColor3
		local scroll1 = playerGui:WaitForChild("m"):WaitForChild("Main"):WaitForChild("Other"):WaitForChild("ScrollingFrame")
		local scroll2 = playerGui:WaitForChild("m"):WaitForChild("Main"):WaitForChild("Fun"):WaitForChild("ScrollingFrame")
		local scroll3 = playerGui:WaitForChild("m"):WaitForChild("Main"):WaitForChild("MainM"):WaitForChild("ScrollingFrame")
		scroll1.ScrollBarImageColor3 = color
		scroll2.ScrollBarImageColor3 = color
		scroll3.ScrollBarImageColor3 = color
	end)
end
coroutine.wrap(ZYOEXLU_fake_script)()
local function HAJA_fake_script() -- TextButton_4.LocalScript 
	local script = Instance.new('LocalScript', TextButton_4)

	script.Parent.MouseButton1Click:Connect(function()
		local Players = game:GetService("Players")
		local player = Players.LocalPlayer
		local playerGui = player:WaitForChild("PlayerGui")
		local color = script.Parent.BackgroundColor3
		local scroll1 = playerGui:WaitForChild("m"):WaitForChild("Main"):WaitForChild("Other"):WaitForChild("ScrollingFrame")
		local scroll2 = playerGui:WaitForChild("m"):WaitForChild("Main"):WaitForChild("Fun"):WaitForChild("ScrollingFrame")
		local scroll3 = playerGui:WaitForChild("m"):WaitForChild("Main"):WaitForChild("MainM"):WaitForChild("ScrollingFrame")
		scroll1.ScrollBarImageColor3 = color
		scroll2.ScrollBarImageColor3 = color
		scroll3.ScrollBarImageColor3 = color
	end)
end
print("line 1166 check")
coroutine.wrap(HAJA_fake_script)()
local function CWFXK_fake_script() -- TextButton_5.LocalScript 
	local script = Instance.new('LocalScript', TextButton_5)

	script.Parent.MouseButton1Click:Connect(function()
		local Players = game:GetService("Players")
		local player = Players.LocalPlayer
		local playerGui = player:WaitForChild("PlayerGui")
		local color = script.Parent.BackgroundColor3
		local scroll1 = playerGui:WaitForChild("m"):WaitForChild("Main"):WaitForChild("Other"):WaitForChild("ScrollingFrame")
		local scroll2 = playerGui:WaitForChild("m"):WaitForChild("Main"):WaitForChild("Fun"):WaitForChild("ScrollingFrame")
		local scroll3 = playerGui:WaitForChild("m"):WaitForChild("Main"):WaitForChild("MainM"):WaitForChild("ScrollingFrame")
		scroll1.ScrollBarImageColor3 = color
		scroll2.ScrollBarImageColor3 = color
		scroll3.ScrollBarImageColor3 = color
	end)
end
print("line 1184 check")
coroutine.wrap(CWFXK_fake_script)()
local function TIGZX_fake_script() -- TextButton_6.LocalScript 
	local script = Instance.new('LocalScript', TextButton_6)

	script.Parent.MouseButton1Click:Connect(function()
		local Players = game:GetService("Players")
		local player = Players.LocalPlayer
		local playerGui = player:WaitForChild("PlayerGui")
		local color = script.Parent.BackgroundColor3
		local scroll1 = playerGui:WaitForChild("m"):WaitForChild("Main"):WaitForChild("Other"):WaitForChild("ScrollingFrame")
		local scroll2 = playerGui:WaitForChild("m"):WaitForChild("Main"):WaitForChild("Fun"):WaitForChild("ScrollingFrame")
		local scroll3 = playerGui:WaitForChild("m"):WaitForChild("Main"):WaitForChild("MainM"):WaitForChild("ScrollingFrame")
		scroll1.ScrollBarImageColor3 = color
		scroll2.ScrollBarImageColor3 = color
		scroll3.ScrollBarImageColor3 = color
	end)
end
coroutine.wrap(TIGZX_fake_script)()
local function IMUY_fake_script() -- TextButton_7.LocalScript 
	local script = Instance.new('LocalScript', TextButton_7)

	script.Parent.MouseButton1Click:Connect(function()
		local Players = game:GetService("Players")
		local player = Players.LocalPlayer
		local playerGui = player:WaitForChild("PlayerGui")
		local color = script.Parent.BackgroundColor3
		local scroll1 = playerGui:WaitForChild("m"):WaitForChild("Main"):WaitForChild("Other"):WaitForChild("ScrollingFrame")
		local scroll2 = playerGui:WaitForChild("m"):WaitForChild("Main"):WaitForChild("Fun"):WaitForChild("ScrollingFrame")
		local scroll3 = playerGui:WaitForChild("m"):WaitForChild("Main"):WaitForChild("MainM"):WaitForChild("ScrollingFrame")
		scroll1.ScrollBarImageColor3 = color
		scroll2.ScrollBarImageColor3 = color
		scroll3.ScrollBarImageColor3 = color
	end)
end
print("line 1219 check")
coroutine.wrap(IMUY_fake_script)()
local function QTCVWPW_fake_script() -- TextButton_8.LocalScript 
	local script = Instance.new('LocalScript', TextButton_8)

	script.Parent.MouseButton1Click:Connect(function()
		local Players = game:GetService("Players")
		local player = Players.LocalPlayer
		local playerGui = player:WaitForChild("PlayerGui")
		local color = script.Parent.BackgroundColor3
		local scroll1 = playerGui:WaitForChild("m"):WaitForChild("Main"):WaitForChild("Other"):WaitForChild("ScrollingFrame")
		local scroll2 = playerGui:WaitForChild("m"):WaitForChild("Main"):WaitForChild("Fun"):WaitForChild("ScrollingFrame")
		local scroll3 = playerGui:WaitForChild("m"):WaitForChild("Main"):WaitForChild("MainM"):WaitForChild("ScrollingFrame")
		scroll1.ScrollBarImageColor3 = color
		scroll2.ScrollBarImageColor3 = color
		scroll3.ScrollBarImageColor3 = color
	end)
end
coroutine.wrap(QTCVWPW_fake_script)()
local function ARNCK_fake_script() -- TextButton_9.LocalScript 
	local script = Instance.new('LocalScript', TextButton_9)

	script.Parent.MouseButton1Click:Connect(function()
		local Players = game:GetService("Players")
		local player = Players.LocalPlayer
		local playerGui = player:WaitForChild("PlayerGui")
		local color = script.Parent.BackgroundColor3
		local scroll1 = playerGui:WaitForChild("m"):WaitForChild("Main"):WaitForChild("Other"):WaitForChild("ScrollingFrame")
		local scroll2 = playerGui:WaitForChild("m"):WaitForChild("Main"):WaitForChild("Fun"):WaitForChild("ScrollingFrame")
		local scroll3 = playerGui:WaitForChild("m"):WaitForChild("Main"):WaitForChild("MainM"):WaitForChild("ScrollingFrame")
		scroll1.ScrollBarImageColor3 = color
		scroll2.ScrollBarImageColor3 = color
		scroll3.ScrollBarImageColor3 = color
	end)
end
coroutine.wrap(ARNCK_fake_script)()
local function VOQJPFF_fake_script() -- TextButton_10.LocalScript 
	local script = Instance.new('LocalScript', TextButton_10)

	script.Parent.MouseButton1Click:Connect(function()
		local Players = game:GetService("Players")
		local player = Players.LocalPlayer
		local playerGui = player:WaitForChild("PlayerGui")
		local color = script.Parent.BackgroundColor3
		local scroll1 = playerGui:WaitForChild("m"):WaitForChild("Main"):WaitForChild("Other"):WaitForChild("ScrollingFrame")
		local scroll2 = playerGui:WaitForChild("m"):WaitForChild("Main"):WaitForChild("Fun"):WaitForChild("ScrollingFrame")
		local scroll3 = playerGui:WaitForChild("m"):WaitForChild("Main"):WaitForChild("MainM"):WaitForChild("ScrollingFrame")
		scroll1.ScrollBarImageColor3 = color
		scroll2.ScrollBarImageColor3 = color
		scroll3.ScrollBarImageColor3 = color
	end)
end
coroutine.wrap(VOQJPFF_fake_script)()
local function LHVFCR_fake_script() -- TextButton_11.LocalScript 
	local script = Instance.new('LocalScript', TextButton_11)

	script.Parent.MouseButton1Click:Connect(function()
		local Players = game:GetService("Players")
		local player = Players.LocalPlayer
		local playerGui = player:WaitForChild("PlayerGui")
		local color = script.Parent.BackgroundColor3
		local scroll1 = playerGui:WaitForChild("m"):WaitForChild("Main"):WaitForChild("Other"):WaitForChild("ScrollingFrame")
		local scroll2 = playerGui:WaitForChild("m"):WaitForChild("Main"):WaitForChild("Fun"):WaitForChild("ScrollingFrame")
		local scroll3 = playerGui:WaitForChild("m"):WaitForChild("Main"):WaitForChild("MainM"):WaitForChild("ScrollingFrame")
		scroll1.ScrollBarImageColor3 = color
		scroll2.ScrollBarImageColor3 = color
		scroll3.ScrollBarImageColor3 = color
	end)
end
coroutine.wrap(LHVFCR_fake_script)()
local function XBDGP_fake_script() -- TextButton_12.LocalScript 
	local script = Instance.new('LocalScript', TextButton_12)

	script.Parent.MouseButton1Click:Connect(function()
		local Players = game:GetService("Players")
		local player = Players.LocalPlayer
		local playerGui = player:WaitForChild("PlayerGui")
		local color = script.Parent.BackgroundColor3
		local scroll1 = playerGui:WaitForChild("m"):WaitForChild("Main"):WaitForChild("Other"):WaitForChild("ScrollingFrame")
		local scroll2 = playerGui:WaitForChild("m"):WaitForChild("Main"):WaitForChild("Fun"):WaitForChild("ScrollingFrame")
		local scroll3 = playerGui:WaitForChild("m"):WaitForChild("Main"):WaitForChild("MainM"):WaitForChild("ScrollingFrame")
		scroll1.ScrollBarImageColor3 = color
		scroll2.ScrollBarImageColor3 = color
		scroll3.ScrollBarImageColor3 = color
	end)
end
coroutine.wrap(XBDGP_fake_script)()
local function YJII_fake_script() -- TextButton_13.LocalScript 
	local script = Instance.new('LocalScript', TextButton_13)

	script.Parent.MouseButton1Click:Connect(function()
		local Players = game:GetService("Players")
		local player = Players.LocalPlayer
		local playerGui = player:WaitForChild("PlayerGui")
		local color = script.Parent.BackgroundColor3
		local scroll1 = playerGui:WaitForChild("m"):WaitForChild("Main"):WaitForChild("Other"):WaitForChild("ScrollingFrame")
		local scroll2 = playerGui:WaitForChild("m"):WaitForChild("Main"):WaitForChild("Fun"):WaitForChild("ScrollingFrame")
		local scroll3 = playerGui:WaitForChild("m"):WaitForChild("Main"):WaitForChild("MainM"):WaitForChild("ScrollingFrame")
		scroll1.ScrollBarImageColor3 = color
		scroll2.ScrollBarImageColor3 = color
		scroll3.ScrollBarImageColor3 = color
	end)
end
coroutine.wrap(YJII_fake_script)()
local function ZXEOFJZ_fake_script() -- Other_3.LocalScript 
	local script = Instance.new('LocalScript', Other_3)

	script.Parent.MouseButton1Click:Connect(function()
		local Players = game:GetService("Players")
		local player = Players.LocalPlayer
		local playerGui = player:WaitForChild("PlayerGui")
		local color = script.Parent.BackgroundColor3
		local back = playerGui:WaitForChild("m"):WaitForChild("Main")
		back.BackgroundColor3 = color
	end)
end
coroutine.wrap(ZXEOFJZ_fake_script)()
local function BEOZAJ_fake_script() -- Other_4.LocalScript 
	local script = Instance.new('LocalScript', Other_4)

	script.Parent.MouseButton1Click:Connect(function()
		local Players = game:GetService("Players")
		local player = Players.LocalPlayer
		local playerGui = player:WaitForChild("PlayerGui")
		local color = script.Parent.BackgroundColor3
		local back = playerGui:WaitForChild("m"):WaitForChild("Main")
		back.BackgroundColor3 = color
	end)
end
print("line 1348 check")
coroutine.wrap(BEOZAJ_fake_script)()
local function SRBWNDY_fake_script() -- Other_5.LocalScript 
	local script = Instance.new('LocalScript', Other_5)

	script.Parent.MouseButton1Click:Connect(function()
		local Players = game:GetService("Players")
		local player = Players.LocalPlayer
		local playerGui = player:WaitForChild("PlayerGui")
		local color = script.Parent.BackgroundColor3
		local back = playerGui:WaitForChild("m"):WaitForChild("Main")
		back.BackgroundColor3 = color
	end)
end
coroutine.wrap(SRBWNDY_fake_script)()
local function TMQEW_fake_script() -- Other_6.LocalScript 
	local script = Instance.new('LocalScript', Other_6)

	script.Parent.MouseButton1Click:Connect(function()
		local Players = game:GetService("Players")
		local player = Players.LocalPlayer
		local playerGui = player:WaitForChild("PlayerGui")
		local color = script.Parent.BackgroundColor3
		local back = playerGui:WaitForChild("m"):WaitForChild("Main")
		back.BackgroundColor3 = color
	end)
end
coroutine.wrap(TMQEW_fake_script)()
local function BBHB_fake_script() -- Other_6.LocalScript 
	local script = Instance.new('LocalScript', Other_6)

	script.Parent.MouseButton1Click:Connect(function()
		local Players = game:GetService("Players")
		local player = Players.LocalPlayer
		local playerGui = player:WaitForChild("PlayerGui")
		local color = script.Parent.BackgroundColor3
		local back = playerGui:WaitForChild("m"):WaitForChild("Main")
		back.BackgroundColor3 = color
	end)
end
coroutine.wrap(BBHB_fake_script)()
local function BSUPBF_fake_script() -- Other_7.LocalScript 
	local script = Instance.new('LocalScript', Other_7)

	script.Parent.MouseButton1Click:Connect(function()
		local Players = game:GetService("Players")
		local player = Players.LocalPlayer
		local playerGui = player:WaitForChild("PlayerGui")
		local color = script.Parent.BackgroundColor3
		local back = playerGui:WaitForChild("m"):WaitForChild("Main")
		back.BackgroundColor3 = color
	end)
end
coroutine.wrap(BSUPBF_fake_script)()
local function NBSCCLF_fake_script() -- Other_8.LocalScript 
	local script = Instance.new('LocalScript', Other_8)

	script.Parent.MouseButton1Click:Connect(function()
		local Players = game:GetService("Players")
		local player = Players.LocalPlayer
		local playerGui = player:WaitForChild("PlayerGui")
		local color = script.Parent.BackgroundColor3
		local back = playerGui:WaitForChild("m"):WaitForChild("Main")
		back.BackgroundColor3 = color
	end)
end
coroutine.wrap(NBSCCLF_fake_script)()
local function CZGNFWZ_fake_script() -- Other_9.LocalScript 
	local script = Instance.new('LocalScript', Other_9)

	script.Parent.MouseButton1Click:Connect(function()
		local Players = game:GetService("Players")
		local player = Players.LocalPlayer
		local playerGui = player:WaitForChild("PlayerGui")
		local color = script.Parent.BackgroundColor3
		local back = playerGui:WaitForChild("m"):WaitForChild("Main")
		back.BackgroundColor3 = color
	end)
end
coroutine.wrap(CZGNFWZ_fake_script)()
local function GDWD_fake_script() -- Other_10.LocalScript 
	local script = Instance.new('LocalScript', Other_10)

	script.Parent.MouseButton1Click:Connect(function()
		local Players = game:GetService("Players")
		local player = Players.LocalPlayer
		local playerGui = player:WaitForChild("PlayerGui")
		local color = script.Parent.BackgroundColor3
		local back = playerGui:WaitForChild("m"):WaitForChild("Main")
		back.BackgroundColor3 = color
	end)
end
coroutine.wrap(GDWD_fake_script)()
local function DXSGZOU_fake_script() -- Other_11.LocalScript 
	local script = Instance.new('LocalScript', Other_11)

	script.Parent.MouseButton1Click:Connect(function()
		local Players = game:GetService("Players")
		local player = Players.LocalPlayer
		local playerGui = player:WaitForChild("PlayerGui")
		local color = script.Parent.BackgroundColor3
		local back = playerGui:WaitForChild("m"):WaitForChild("Main")
		back.BackgroundColor3 = color
	end)
end
print("line 1353 checl")
coroutine.wrap(DXSGZOU_fake_script)()
local function KFEGTX_fake_script() -- Other_12.LocalScript 
	local script = Instance.new('LocalScript', Other_12)

	script.Parent.MouseButton1Click:Connect(function()
		local Players = game:GetService("Players")
		local player = Players.LocalPlayer
		local playerGui = player:WaitForChild("PlayerGui")
		local color = script.Parent.BackgroundColor3
		local back = playerGui:WaitForChild("m"):WaitForChild("Main")
		back.BackgroundColor3 = color
	end)
end
coroutine.wrap(KFEGTX_fake_script)()
local function IPBFZSD_fake_script() -- Other_13.LocalScript 
	local script = Instance.new('LocalScript', Other_13)

	script.Parent.MouseButton1Click:Connect(function()
		local Players = game:GetService("Players")
		local player = Players.LocalPlayer
		local playerGui = player:WaitForChild("PlayerGui")
		local color = script.Parent.BackgroundColor3
		local back = playerGui:WaitForChild("m"):WaitForChild("Main")
		back.BackgroundColor3 = color
	end)
end
coroutine.wrap(IPBFZSD_fake_script)()
local function NVEILFK_fake_script() -- Other_14.LocalScript 
	local script = Instance.new('LocalScript', Other_14)

	script.Parent.MouseButton1Click:Connect(function()
		local Players = game:GetService("Players")
		local player = Players.LocalPlayer
		local playerGui = player:WaitForChild("PlayerGui")
		local color = script.Parent.BackgroundColor3
		local back = playerGui:WaitForChild("m"):WaitForChild("Main")
		back.BackgroundColor3 = color
	end)
end
coroutine.wrap(NVEILFK_fake_script)()
local function ZPTNQ_fake_script() -- TextButton_14.LocalScript 
	local script = Instance.new('LocalScript', TextButton_14)

	script.Parent.MouseButton1Click:Connect(function()
		local Players = game:GetService("Players")
		local player = Players.LocalPlayer
		local playerGui = player:WaitForChild("PlayerGui")
		local color = script.Parent.BackgroundColor3
		local back = playerGui:WaitForChild("m"):WaitForChild("Main")
		back.BackgroundColor3 = color
	end)
end
coroutine.wrap(ZPTNQ_fake_script)()
local function VHZWXK_fake_script() -- Fun_2.LocalScript 
	local script = Instance.new('LocalScript', Fun_2)

	script.Parent.MouseButton1Down:connect(function()
		script.Parent.Parent.Parent.MainM.ScrollingFrame.Visible = false
		script.Parent.Parent.Parent.Fun.ScrollingFrame.Visible = true
		script.Parent.Parent.Parent.Other.ScrollingFrame.Visible = false
	end)
end
coroutine.wrap(VHZWXK_fake_script)()
local function CTBFKPZ_fake_script() -- ImageButton.LocalScript 
	local script = Instance.new('LocalScript', ImageButton)

	script.Parent.MouseButton1Click:Connect(function()
		if script.Parent.Parent.BackHelp.Visible == false then
			script.Parent.Parent.BackHelp.Visible = true 
		else
			script.Parent.Parent.BackHelp.Visible = false
		end
	end)
end
print("line 1528 check")
coroutine.wrap(CTBFKPZ_fake_script)()
local function TUGADYJ_fake_script() -- Main_2.LocalScript 
	local script = Instance.new('LocalScript', Main_2)

	script.Parent.MouseButton1Down:connect(function()
		script.Parent.Parent.ScrollingFrame.Visible = true
		script.Parent.Parent.Parent.Fun.ScrollingFrame.Visible = false
		script.Parent.Parent.Parent.Other.ScrollingFrame.Visible = false
	end)
end
coroutine.wrap(TUGADYJ_fake_script)()
local function PKMWOWJ_fake_script() -- Walk.LocalScript 
	local script = Instance.new('LocalScript', Walk)

	local walk_speed;
	
	script.Parent.Parent.WalkValue.Changed:Connect(function() 
		local Players = game:GetService("Players")
		local Player = Players.LocalPlayer
		local Character = Player.Character or Player.CharacterAdded:Wait()
		local humanoid = Character:WaitForChild "Humanoid"
		walk_speed = script.Parent.Parent.WalkValue.Text
		game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = tonumber(walk_speed) or 16
	end)
end
coroutine.wrap(PKMWOWJ_fake_script)()
local function IQLKSLE_fake_script() -- Health_2.LocalScript 
	local script = Instance.new('LocalScript', Health_2)

	
	local hvalue;
	
	script.Parent.Parent.HValue.Changed:Connect(function() 
		local Players = game:GetService("Players")
		local Player = Players.LocalPlayer
		local Character = Player.Character or Player.CharacterAdded:Wait()
		local humanoid = Character:WaitForChild "Humanoid"
		hvalue = script.Parent.Parent.HValue.Text
		humanoid.Health = tonumber(hvalue) or 100
	end)
	
	
	local hvalue;
	
	script.Parent.Parent.HValue.Changed:Connect(function() 
		local Players = game:GetService("Players")
		local Player = Players.LocalPlayer
		local Character = Player.Character or Player.CharacterAdded:Wait()
		local humanoid = Character:WaitForChild "Humanoid"
		hvalue = script.Parent.Parent.HValue.Text
		humanoid.MaxHealth = tonumber(hvalue) or 100
	end)
end
print("line 1582 check")
coroutine.wrap(IQLKSLE_fake_script)()
local function WZWJP_fake_script() -- Jump.LocalScript 
	local script = Instance.new('LocalScript', Jump)

	
	local jump_power;
	
	script.Parent.Parent.JumpValue.Changed:Connect(function() 
		local Players = game:GetService("Players")
		local Player = Players.LocalPlayer
		local Character = Player.Character or Player.CharacterAdded:Wait()
		local humanoid = Character:WaitForChild "Humanoid"
		jump_power = script.Parent.Parent.JumpValue.Text
		humanoid.JumpPower = tonumber(jump_power) or 26
	end)
end
coroutine.wrap(WZWJP_fake_script)()
local function RDFEX_fake_script() -- AddCurrency.LocalScript 
	local script = Instance.new('LocalScript', AddCurrency)

	script.Parent.MouseButton1Click:Connect(function()
			local Players = game:GetService("Players")
		local Player = Players.LocalPlayer
		local Currency = script.Parent.Parent.CurrencyName.Text
		local amount = script.Parent.Parent.Amount
		Player.leaderstats.Currency = Player.leaderstats.Currency + amount
	end)
	
end
coroutine.wrap(RDFEX_fake_script)()
local function ONJANPW_fake_script() -- MainM.DragTrue 
	local script = Instance.new('LocalScript', MainM)

	script.Parent.Draggable = true
end
coroutine.wrap(ONJANPW_fake_script)()
local function YKGLFT_fake_script() -- Username.LocalScript 
	local script = Instance.new('LocalScript', Username)

	script.Parent.Text = game.Players.LocalPlayer.Name
end
coroutine.wrap(YKGLFT_fake_script)()
local function JMFJ_fake_script() -- TextButton_15.LocalScript 
	local script = Instance.new('LocalScript', TextButton_15)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Visible = false
	end)
end
coroutine.wrap(JMFJ_fake_script)()
