-- Gui to Lua
-- Version: 3.2

-- Instances:

local CoreGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local fortnitexd = Instance.new("TextLabel")

--Properties:

CoreGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
CoreGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Frame.Parent = CoreGui
Frame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame.BackgroundTransparency = 1.000
Frame.Size = UDim2.new(0, 100, 0, 100)

fortnitexd.Name = "fortnitexd"
fortnitexd.Parent = Frame
fortnitexd.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
fortnitexd.BackgroundTransparency = 1.000
fortnitexd.BorderSizePixel = 0
fortnitexd.Position = UDim2.new(15.1500006, 0, 9, 0)
fortnitexd.Size = UDim2.new(0, 404, 0, 93)
fortnitexd.Font = Enum.Font.RobotoMono
fortnitexd.Text = "bella is my mommy"
fortnitexd.TextColor3 = Color3.fromRGB(0, 0, 0)
fortnitexd.TextScaled = true
fortnitexd.TextSize = 71.000
fortnitexd.TextTransparency = 0.7
fortnitexd.TextWrapped = true

-- Scripts:

local function JBRNLZW_fake_script() -- fortnitexd.LocalScript 
	local script = Instance.new('LocalScript', fortnitexd)

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
coroutine.wrap(JBRNLZW_fake_script)()
