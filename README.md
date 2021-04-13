-- Instances:

local FPSMEMORY = Instance.new("ScreenGui")
local TopFrame = Instance.new("ImageLabel")
local UIGradient = Instance.new("UIGradient")
local Frame = Instance.new("ImageLabel")
local FPS = Instance.new("TextLabel")
local FPSNUM = Instance.new("TextLabel")
local MEM = Instance.new("TextLabel")
local MEMNUM = Instance.new("TextLabel")
local UIGradient_2 = Instance.new("UIGradient")
local TIME = Instance.new("TextLabel")
local TIMENUM = Instance.new("TextLabel")
local DATE = Instance.new("TextLabel")
local DATENUM = Instance.new("TextLabel")

--Properties:

FPSMEMORY.Name = "FPS/MEMORY"
FPSMEMORY.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

TopFrame.Name = "TopFrame"
TopFrame.Parent = FPSMEMORY
TopFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TopFrame.BackgroundTransparency = 1.000
TopFrame.Position = UDim2.new(0.00574606657, 0, 0.0476757884, 0)
TopFrame.Size = UDim2.new(0, 242, 0, 137)
TopFrame.Image = "rbxassetid://3570695787"
TopFrame.ScaleType = Enum.ScaleType.Slice
TopFrame.SliceCenter = Rect.new(100, 100, 100, 100)
TopFrame.SliceScale = 0.070

UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 50, 152)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(103, 92, 255))}
UIGradient.Parent = TopFrame

Frame.Name = "Frame"
Frame.Parent = TopFrame
Frame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame.BackgroundTransparency = 1.000
Frame.Position = UDim2.new(0.0370370373, 0, 0.0985915512, 0)
Frame.Size = UDim2.new(0, 199, 0, 57)
Frame.Image = "rbxassetid://3570695787"
Frame.ScaleType = Enum.ScaleType.Slice
Frame.SliceCenter = Rect.new(100, 100, 100, 100)
Frame.SliceScale = 0.050

FPS.Name = "FPS"
FPS.Parent = Frame
FPS.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
FPS.BackgroundTransparency = 1.000
FPS.BorderSizePixel = 0
FPS.Position = UDim2.new(0.0452261306, 0, 0.649122834, 0)
FPS.Size = UDim2.new(0, 199, 0, 20)
FPS.Font = Enum.Font.SourceSansSemibold
FPS.Text = "FPS"
FPS.TextColor3 = Color3.fromRGB(0, 0, 0)
FPS.TextSize = 20.000
FPS.TextXAlignment = Enum.TextXAlignment.Left

FPSNUM.Name = "FPS/NUM"
FPSNUM.Parent = FPS
FPSNUM.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
FPSNUM.BackgroundTransparency = 1.000
FPSNUM.Position = UDim2.new(-0.0856532604, 0, -0.000999987125, 0)
FPSNUM.Size = UDim2.new(0, 199, 0, 20)
FPSNUM.Font = Enum.Font.SourceSansSemibold
FPSNUM.Text = "60"
FPSNUM.TextColor3 = Color3.fromRGB(0, 0, 0)
FPSNUM.TextSize = 20.000
FPSNUM.TextXAlignment = Enum.TextXAlignment.Right

MEM.Name = "MEM"
MEM.Parent = Frame
MEM.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
MEM.BackgroundTransparency = 1.000
MEM.BorderSizePixel = 0
MEM.Position = UDim2.new(0, 0, 0.105263174, 0)
MEM.Size = UDim2.new(0, 199, 0, 20)
MEM.Font = Enum.Font.SourceSansSemibold
MEM.Text = "Memory"
MEM.TextColor3 = Color3.fromRGB(0, 0, 0)
MEM.TextSize = 20.000
MEM.TextXAlignment = Enum.TextXAlignment.Left

MEMNUM.Name = "MEM/NUM"
MEMNUM.Parent = MEM
MEMNUM.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
MEMNUM.BackgroundTransparency = 1.000
MEMNUM.Position = UDim2.new(0, 0, 0.104999997, 0)
MEMNUM.Size = UDim2.new(0, 199, 0, 20)
MEMNUM.Font = Enum.Font.SourceSansSemibold
MEMNUM.Text = "300mb"
MEMNUM.TextColor3 = Color3.fromRGB(0, 0, 0)
MEMNUM.TextSize = 20.000
MEMNUM.TextXAlignment = Enum.TextXAlignment.Right

UIGradient_2.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 50, 152)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(103, 92, 255))}
UIGradient_2.Parent = Frame

TIME.Name = "TIME"
TIME.Parent = Frame
TIME.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TIME.BackgroundTransparency = 1.000
TIME.Position = UDim2.new(0.0452261306, 0, 1.10526311, 0)
TIME.Size = UDim2.new(0, 199, 0, 20)
TIME.Font = Enum.Font.SourceSansSemibold
TIME.Text = "Time"
TIME.TextColor3 = Color3.fromRGB(0, 0, 0)
TIME.TextSize = 20.000
TIME.TextXAlignment = Enum.TextXAlignment.Left

TIMENUM.Name = "TIME/NUM"
TIMENUM.Parent = Frame
TIMENUM.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TIMENUM.BackgroundTransparency = 1.000
TIMENUM.Position = UDim2.new(0.0452261306, 0, 1.09535086, 0)
TIMENUM.Size = UDim2.new(0, 199, 0, 20)
TIMENUM.Font = Enum.Font.SourceSansSemibold
TIMENUM.Text = "10:10:10"
TIMENUM.TextColor3 = Color3.fromRGB(0, 0, 0)
TIMENUM.TextSize = 20.000
TIMENUM.TextXAlignment = Enum.TextXAlignment.Right

DATE.Name = "DATE"
DATE.Parent = Frame
DATE.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
DATE.BackgroundTransparency = 1.000
DATE.Position = UDim2.new(0.0452261306, 0, 1.5964911, 0)
DATE.Size = UDim2.new(0, 199, 0, 20)
DATE.Font = Enum.Font.SourceSansSemibold
DATE.Text = "Date"
DATE.TextColor3 = Color3.fromRGB(0, 0, 0)
DATE.TextSize = 20.000
DATE.TextXAlignment = Enum.TextXAlignment.Left

DATENUM.Name = "DATE/NUM"
DATENUM.Parent = Frame
DATENUM.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
DATENUM.BackgroundTransparency = 1.000
DATENUM.Position = UDim2.new(0.0452261306, 0, 1.58657897, 0)
DATENUM.Size = UDim2.new(0, 199, 0, 20)
DATENUM.Font = Enum.Font.SourceSansSemibold
DATENUM.Text = "Jan/1/2021"
DATENUM.TextColor3 = Color3.fromRGB(0, 0, 0)
DATENUM.TextSize = 20.000
DATENUM.TextXAlignment = Enum.TextXAlignment.Right

-- Scripts:

local function SMOHZ_fake_script() -- FPSNUM.FPS 
	local script = Instance.new('LocalScript', FPSNUM)

	local old_tick = tick();
	
	local a = 0
	local b = game:GetService("RunService").Heartbeat
	local c, d
	local e = {}
	local function f()
		c = tick()
		for g = #e, 1, -1 do
			e[g + 1] = e[g] >= c - 1 and e[g] or nil
		end
		e[1] = c
		local h = tick() - d >= 1 and #e or #e / (tick() - d)
		h = math.floor(h)
		a = a + 1
	
		script.Parent.Text = tostring(h);
	end
	d = tick()
	b:Connect(f)
end
coroutine.wrap(SMOHZ_fake_script)()
local function AEAQ_fake_script() -- MEMNUM.LocalScript 
	local script = Instance.new('LocalScript', MEMNUM)

	while wait() do
		script.Parent.Text = string.format("%dmb", game:GetService("Stats"):GetTotalMemoryUsageMb())
	end
end
coroutine.wrap(AEAQ_fake_script)()
local function AKRC_fake_script() -- Frame.Time/Date 
	local script = Instance.new('LocalScript', Frame)

	while wait() do
		local Data = os.date("*t")
		local Months = {"Jan","Feb","Mar","Apr","May","Jun","Jul","Aug","Sep","Oct","Nov","Dec"}
		local Date = script.Parent:WaitForChild("DATE/NUM")
		local Time = script.Parent:WaitForChild("TIME/NUM")
		for i,v in pairs(Months)do
			if Data.month == i then
				Date.Text = Data.day.."/"..v.."/"..Data.year
			end
		end
		Time.Text = Data.hour..":"..Data.min..":"..Data.sec
	end
end
coroutine.wrap(AKRC_fake_script)()
local function RRAKRR_fake_script() -- Frame.Draggable-UI 
	local script = Instance.new('LocalScript', Frame)

	frame = script.Parent.Parent.Parent.TopFrame
	frame.Draggable = true
	frame.Active = true
	frame.Selectable = true
end
coroutine.wrap(RRAKRR_fake_script)()


function onKeyPress(inputObject, gameProcessedEvent)
	if inputObject.KeyCode == Enum.KeyCode.K then
		if TopFrame.Visible == false then
			TopFrame.Visible = true
		else
			TopFrame.Visible = false
		end
	end
end

game:GetService("UserInputService").InputBegan:connect(onKeyPress)
