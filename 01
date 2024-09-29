local coreGui = game:GetService("CoreGui")
local screenGui = Instance.new("ScreenGui", coreGui)
local button = Instance.new("TextButton", screenGui)

-- Cấu hình nút
button.Size = UDim2.new(0, 50, 0, 50)
button.Position = UDim2.new(1, -60, 0.5, -25) -- Đặt ở giữa bên phải
button.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
button.BackgroundTransparency = 0.5 -- Đặt độ trong suốt
button.BorderSizePixel = 0
button.Text = "INVIS"
button.TextColor3 = Color3.fromRGB(255, 255, 255)
button.TextSize = 20
button.Font = Enum.Font.SourceSansBold

-- Kết nối sự kiện nhấn phím G
button.MouseButton1Down:Connect(function()
    keypress(Enum.KeyCode.G)
end)

button.MouseButton1Up:Connect(function()
    keyrelease(Enum.KeyCode.G)
end)
