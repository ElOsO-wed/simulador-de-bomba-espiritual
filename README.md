-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local UICorner_2 = Instance.new("UICorner")
local TextLabel_2 = Instance.new("TextLabel")
local UICorner_3 = Instance.new("UICorner")
local TextButton = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local TextButton_2 = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local TextButton_3 = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local TextLabel_3 = Instance.new("TextLabel")
local TextButton_4 = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local TextButton_5 = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")
local TextButton_6 = Instance.new("TextButton")
local UICorner_9 = Instance.new("UICorner")
local TextButton_7 = Instance.new("TextButton")
local UICorner_10 = Instance.new("UICorner")

--Properties:

ScreenGui.Parent = game.CoreGui
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
ScreenGui.ResetOnSpawn = false

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(11, 11, 11)
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0, 0, 0.0190174319, 0)
Frame.Size = UDim2.new(0, 187, 0, 242)
Frame.Visible = false
Frame.Active = true
Frame.Draggable = true

UICorner.Parent = Frame

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Size = UDim2.new(0, 187, 0, 37)
TextLabel.Font = Enum.Font.LuckiestGuy
TextLabel.Text = "Simulador De Una bomba espiritual!"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextWrapped = true

UICorner_2.Parent = TextLabel

TextLabel_2.Parent = Frame
TextLabel_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Position = UDim2.new(0, 0, 0.84710741, 0)
TextLabel_2.Size = UDim2.new(0, 187, 0, 37)
TextLabel_2.Font = Enum.Font.LuckiestGuy
TextLabel_2.Text = "Owner script: YANSER_ExPLOIT HELPER:      ELOSO"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextScaled = true
TextLabel_2.TextSize = 14.000
TextLabel_2.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextWrapped = true

UICorner_3.Parent = TextLabel_2

TextButton.Parent = Frame
TextButton.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0, 0, 0.154546693, 0)
TextButton.Size = UDim2.new(0, 187, 0, 38)
TextButton.Font = Enum.Font.Antique
TextButton.Text = "Auto power"
TextButton.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton.TextScaled = true
TextButton.TextSize = 14.000
TextButton.TextWrapped = true
TextButton.MouseButton1Click:Connect(function()
	while true do 
		wait(0.1)
		game:GetService("ReplicatedStorage").Remotes.AddWheelSpinValue:FireServer("Power",50000000000)
	end 
end)

UICorner_4.Parent = TextButton

TextButton_2.Parent = Frame
TextButton_2.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.BorderSizePixel = 0
TextButton_2.Position = UDim2.new(0, 0, 0.311571479, 0)
TextButton_2.Size = UDim2.new(0, 187, 0, 38)
TextButton_2.Font = Enum.Font.Antique
TextButton_2.Text = "Dar 50 giros de la ruleta"
TextButton_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_2.TextScaled = true
TextButton_2.TextSize = 14.000
TextButton_2.TextWrapped = true
TextButton_2.MouseButton1Click:Connect(function()
	game:GetService("ReplicatedStorage").Remotes.AddWheelSpinValue:FireServer("Spins",50)
end)

UICorner_5.Parent = TextButton_2

TextButton_3.Parent = Frame
TextButton_3.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_3.BorderSizePixel = 0
TextButton_3.Position = UDim2.new(0, 0, 0.687604547, 0)
TextButton_3.Size = UDim2.new(0, 187, 0, 38)
TextButton_3.Font = Enum.Font.Antique
TextButton_3.Text = "Rejoin"
TextButton_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_3.TextScaled = true
TextButton_3.TextSize = 14.000
TextButton_3.TextWrapped = true
TextButton_3.MouseButton1Click:Connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/Jelly-plays/Rejoin-script/main/obf_L744By559M18BbuseSG6en8r1zL31daK9060LV7WyvmS4bQp92aONWfwRE36FdcZ.lua.txt"))();
end)

UICorner_6.Parent = TextButton_3

TextLabel_3.Parent = Frame
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.BorderSizePixel = 0
TextLabel_3.Position = UDim2.new(0, 0, 0.654546678, 0)
TextLabel_3.Size = UDim2.new(0, 187, 0, 8)
TextLabel_3.Font = Enum.Font.SourceSans
TextLabel_3.Text = ""
TextLabel_3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.TextSize = 14.000

TextButton_4.Parent = Frame
TextButton_4.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_4.BorderSizePixel = 0
TextButton_4.Position = UDim2.new(1, 0, -0.00247810292, 0)
TextButton_4.Size = UDim2.new(0, 53, 0, 22)
TextButton_4.Font = Enum.Font.Antique
TextButton_4.Text = "X"
TextButton_4.TextColor3 = Color3.fromRGB(255, 30, 0)
TextButton_4.TextScaled = true
TextButton_4.TextSize = 14.000
TextButton_4.TextWrapped = true

UICorner_7.Parent = TextButton_4

TextButton_5.Parent = Frame
TextButton_5.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_5.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_5.BorderSizePixel = 0
TextButton_5.Position = UDim2.new(0, 0, 0.46859628, 0)
TextButton_5.Size = UDim2.new(0, 187, 0, 38)
TextButton_5.Font = Enum.Font.Antique
TextButton_5.Text = "tppramdo player"
TextButton_5.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_5.TextScaled = true
TextButton_5.TextSize = 14.000
TextButton_5.TextWrapped = true
TextButton_5.MouseButton1Click:Connect(function()
	-- Servicios y variables
	local Players = game:GetService("Players")
	local UserInputService = game:GetService("UserInputService")
	local VirtualUser = game:GetService("VirtualUser") -- Simula clics
	local attacker = Players.LocalPlayer
	local distanceBehind = 20 -- Distancia detrás del enemigo
	local attacking = false -- Estado del ataque
	local dragging = false -- Control para arrastrar el botón
	local dragOffset = Vector2.new()

	-- Crear GUI
	local screenGui = Instance.new("ScreenGui")
	screenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

	local button = Instance.new("TextButton")
	button.Parent = screenGui
	button.Size = UDim2.new(0, 200, 0, 50)
	button.Position = UDim2.new(0.5, -100, 0.9, 0)
	button.Text = "Activar Auto-Ataque"
	button.BackgroundColor3 = Color3.fromRGB(0, 255, 0)
	button.TextScaled = true
	button.Draggable = false -- Esta propiedad ya no funciona en scripts modernos, lo haremos manualmente

	-- Función para obtener un jugador aleatorio
	local function getRandomPlayer()
		local players = {}
		for _, player in pairs(Players:GetPlayers()) do
			if player ~= attacker then
				table.insert(players, player)
			end
		end
		if #players > 0 then
			return players[math.random(1, #players)]
		end
		return nil
	end

	-- Función para teletransportarse detrás de la cabeza del objetivo
	local function teleportBehind(targetPlayer)
		local targetCharacter = targetPlayer.Character
		if targetCharacter and targetCharacter:FindFirstChild("Head") and attacker.Character then
			local head = targetCharacter.Head.Position
			attacker.Character:SetPrimaryPartCFrame(CFrame.new(head) * CFrame.new(0, 0, -distanceBehind))
		end
	end

	-- Función para seguir la cabeza del jugador objetivo
	local function followPlayer(targetPlayer)
		while attacking and targetPlayer and targetPlayer.Character and targetPlayer.Character:FindFirstChild("Head") do
			local headPosition = targetPlayer.Character.Head.Position
			local behindHead = headPosition - (targetPlayer.Character.Head.CFrame.LookVector * distanceBehind)

			if attacker.Character then
				attacker.Character:SetPrimaryPartCFrame(CFrame.new(behindHead))
			end

			-- Simular clic automático de ataque
			VirtualUser:Button1Down(Vector2.new()) -- Simula presionar clic izquierdo
			wait(0.1) -- Espera un poco antes de moverse de nuevo
		end
	end

	-- Función para esperar hasta que el objetivo sea eliminado
	local function waitUntilTargetIsDead(targetPlayer)
		local targetCharacter = targetPlayer.Character
		if targetCharacter and targetCharacter:FindFirstChild("Humanoid") then
			while targetCharacter.Humanoid.Health > 0 do
				wait(1)
			end
		end
	end

	-- Función principal de ataque
	local function attack()
		while attacking do
			local targetPlayer = getRandomPlayer()
			if targetPlayer then
				teleportBehind(targetPlayer)
				followPlayer(targetPlayer)
				waitUntilTargetIsDead(targetPlayer)
			else
				print("No hay jugadores disponibles para atacar.")
			end
			wait(1)
		end
	end

	-- Evento del botón para activar/desactivar el ataque
	button.MouseButton1Click:Connect(function()
		attacking = not attacking

		if attacking then
			button.Text = "Desactivar Auto-Ataque"
			button.BackgroundColor3 = Color3.fromRGB(255, 0, 0) -- Rojo (desactivar)
			attack()
		else
			button.Text = "Activar Auto-Ataque"
			button.BackgroundColor3 = Color3.fromRGB(0, 255, 0) -- Verde (activar)
		end
	end)

	-- Eventos para mover el botón (arrastrar)
	button.InputBegan:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 then
			dragging = true
			dragOffset = Vector2.new(input.Position.X - button.AbsolutePosition.X, input.Position.Y - button.AbsolutePosition.Y)
		end
	end)

	UserInputService.InputChanged:Connect(function(input)
		if dragging and input.UserInputType == Enum.UserInputType.MouseMovement then
			button.Position = UDim2.new(0, input.Position.X - dragOffset.X, 0, input.Position.Y - dragOffset.Y)
		end
	end)

	UserInputService.InputEnded:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 then
			dragging = false
		end
	end)

end)

UICorner_8.Parent = TextButton_5

TextButton_6.Parent = ScreenGui
TextButton_6.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_6.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_6.BorderSizePixel = 0
TextButton_6.Position = UDim2.new(0.907797337, 0, -0.000950397691, 0)
TextButton_6.Size = UDim2.new(0, 91, 0, 38)
TextButton_6.Font = Enum.Font.Bangers
TextButton_6.Text = "Abrir"
TextButton_6.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_6.TextScaled = true
TextButton_6.TextSize = 14.000
TextButton_6.TextWrapped = true

UICorner_9.Parent = TextButton_6

TextButton_7.Parent = ScreenGui
TextButton_7.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TextButton_7.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_7.BorderSizePixel = 0
TextButton_7.Position = UDim2.new(0.868283689, 0, 0.0117278909, 0)
TextButton_7.Size = UDim2.new(0, 39, 0, 22)
TextButton_7.Font = Enum.Font.Bangers
TextButton_7.Text = "X"
TextButton_7.TextColor3 = Color3.fromRGB(255, 0, 0)
TextButton_7.TextScaled = true
TextButton_7.TextSize = 14.000
TextButton_7.TextWrapped = true

UICorner_10.Parent = TextButton_7

-- Scripts:

local function MDEWVC_fake_script() -- TextButton_4.LocalScript 
	local script = Instance.new('LocalScript', TextButton_4)

	local button = script.Parent
	local frame = button.Parent
	
	button.MouseButton1Click:Connect(function()
		if frame then
			frame:Destroy()
		end
	end)
	
	
end
coroutine.wrap(MDEWVC_fake_script)()
local function NHXEJWZ_fake_script() -- TextButton_6.LocalScript 
	local script = Instance.new('LocalScript', TextButton_6)

	local button = script.Parent -- Botón
	local frame = script.Parent.Parent:FindFirstChild("Frame") -- Frame a mostrar/ocultar
	local dragging = false
	local offset = Vector2.new(0, 0)
	
	if not frame then
		warn("Made BY: YANSER_EXPLOIT")
		return
	end
	
	-- Estado inicial
	button.Text = "Abrir"
	button.Draggable = false -- Esta propiedad no funciona en scripts modernos, haremos el drag manualmente
	
	-- Evento para mostrar/ocultar el frame
	button.MouseButton1Click:Connect(function()
		if frame.Visible then
			frame.Visible = false
			button.Text = "Abrir"
		else
			frame.Visible = true
			button.Text = "Cerrar"
		end
	end)
	
	-- Función para iniciar el arrastre
	button.InputBegan:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 then
			dragging = true
			offset = Vector2.new(input.Position.X - button.AbsolutePosition.X, input.Position.Y - button.AbsolutePosition.Y)
		end
	end)
	
	-- Función para mover el botón mientras se arrastra
	game:GetService("UserInputService").InputChanged:Connect(function(input)
		if dragging and input.UserInputType == Enum.UserInputType.MouseMovement then
			button.Position = UDim2.new(0, input.Position.X - offset.X, 0, input.Position.Y - offset.Y)
		end
	end)
	
	-- Función para soltar el botón
	game:GetService("UserInputService").InputEnded:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 then
			dragging = false
		end
	end)
	
end
coroutine.wrap(NHXEJWZ_fake_script)()
local function MVHLBSY_fake_script() -- TextButton_7.LocalScript 
	local script = Instance.new('LocalScript', TextButton_7)

	local button = script.Parent -- Referencia al botón
	local screenGui = button.Parent -- Asumiendo que el botón está dentro de ScreenGui
	
	button.MouseButton1Click:Connect(function()
		for _, child in pairs(screenGui:GetChildren()) do
			if child:IsA("TextButton") then
				child:Destroy() -- Destruye todos los botones dentro de ScreenGui
			end
		end
	end)
	
end
coroutine.wrap(MVHLBSY_fake_script)()
