if game.PlaceId == 5602055394 then
	local CoreGui = gameGetService(StarterGui)
	CoreGuiSetCore(SendNotification, {
		-- Customizable
		Title = Supported!,
		Text = Supported games list copied,
		Duration = 2,
	})
	setclipboard(httpspastebin.comrawh52yFdp0)

    local Library = loadstring(gameHttpGet(httpsraw.githubusercontent.comxHeptcKavo-UI-Librarymainsource.lua))()
    local Window = Library.CreateLib(MarsHub  DHM, Midnight)


	-- main tab
    local MTab = WindowNewTab(Welcome)
	local WSection = MTabNewSection(Hello There!)
	local plr = game.Players.LocalPlayer.Name
	WSectionNewLabel(Welcome ..plr)
	WSectionNewLabel(to the best DHM script!)
	WSectionNewLabel(MarsHub!)
	WSectionNewButton(Discord Link, Our discord! Join it for special perks!, function ()
		setclipboard(httpsdiscord.ggu3qrGpwbdJ)
		local CoreGui = gameGetService(StarterGui)
		CoreGuiSetCore(SendNotification, {
		-- Customizable
		Title = Copied!,
		Text = Paste the link in browser or in discord!,
		Duration = 2,
	})
	end)
	WSectionNewKeybind(Toggle Ui, Click to edit keybind, Enum.KeyCode.RightAlt, function()
		LibraryToggleUI()
	end)

	-- player tab
	local pTab = WindowNewTab(plr)
	local PSection = pTabNewSection(Fun)
	
	PSectionNewButton((q) Speed, Fake Macro, function()

mouse = game.Players.LocalPlayerGetMouse() 
down = false
local plr = gameGetService('Players').LocalPlayer

function onButton1Down(mouse)
down = true
while down do
if not down then break end
local char = plr.Character

char.HumanoidRootPart.Velocity = char.HumanoidRootPart.CFrame.lookVector  140 -- don't even need bypass LOL
wait()
end
end

function onButton1Up(mouse)
down = false
end

function onSelected(mouse)
mouse.KeyDownconnect(function(k) if klower()==qthen onButton1Down(mouse)end end) -- literally the key function lmao
mouse.KeyUpconnect(function(k) if klower()==qthen onButton1Up(mouse)end end)
end

onSelected(game.Players.LocalPlayerGetMouse())
		end)

		PSectionNewButton((Fe) Headless, People can see ur headless, function ()
			game.Players.LocalPlayer.Character.Head.Transparency = 1
			for i,v in pairs(game.Players.LocalPlayer.Character.HeadGetChildren()) do
			if (vIsA(Decal)) then
					vDestroy()
				end
			end
		end)

		PSectionNewButton(Inf Jump, Jump as high as you want!, function ()
			local Player = gameGetService'Players'.LocalPlayer;
			local UIS = gameGetService'UserInputService';
 
			_G.JumpHeight = 50;
 
			function Action(Object, Function) if Object ~= nil then Function(Object); end end
 
			UIS.InputBeganconnect(function(UserInput)
    			if UserInput.UserInputType == Enum.UserInputType.Keyboard and UserInput.KeyCode == Enum.KeyCode.Space then
       	 			Action(Player.Character.Humanoid, function(self)
            		if selfGetState() == Enum.HumanoidStateType.Jumping or selfGetState() == Enum.HumanoidStateType.Freefall then
                		Action(self.Parent.HumanoidRootPart, function(self)
                    		self.Velocity = Vector3.new(0, _G.JumpHeight, 0);
                			end)
            			end
        			end)
    			end
			end)
		end)
		
		-- Combat Section --

		local CTab = WindowNewTab(Combat)
		local CSection = CTabNewSection(Aim)
		local Silent = CTabNewSection(Silent)

		SilentNewButton(Silent (300), You dont have to look at the person your shooting, function ()
			local CoreGui = gameGetService(StarterGui) -- Variable of StarterGui

		CoreGuiSetCore(SendNotification, {
			-- Customizable
			Title = Aim,
			Text = C to toggle on and off, red = off green = on,
			Duration = 4,
		})
			loadstring(gameHttpGet('httpspastebin.comrawRUGuhQGH'))()
		end)

		SilentNewButton(Silent (150), You dont have to look at the person your shooting, function ()
			local CoreGui = gameGetService(StarterGui) -- Variable of StarterGui

		CoreGuiSetCore(SendNotification, {
			-- Customizable
			Title = Aim,
			Text = C to toggle on and off, red = off green = on,
			Duration = 4,
		})
			loadstring(gameHttpGet('httpspastebin.comrawFVJ2F3ZN'))()
		end)

		SilentNewButton(Silent (80), You dont have to look at the person your shooting, function ()
			local CoreGui = gameGetService(StarterGui) -- Variable of StarterGui

		CoreGuiSetCore(SendNotification, {
			-- Customizable
			Title = Aim,
			Text = C to toggle on and off, red = off green = on,
			Duration = 4,
		})
			loadstring(gameHttpGet('httpspastebin.comrawWkwhR47v'))()
		end)

		SilentNewButton(Silent (50), You dont have to look at the person your shooting, function ()
			local CoreGui = gameGetService(StarterGui) -- Variable of StarterGui

		CoreGuiSetCore(SendNotification, {
			-- Customizable
			Title = Aim,
			Text = C to toggle on and off, red = off green = on,
			Duration = 4,
		})
			loadstring(gameHttpGet('httpspastebin.comrawc2QxPp3A'))()
		end)

		CSectionNewButton(AimLock, Aims for you, function ()
			loadstring(gameHttpGet('httpspastebin.comraw5GEuaZDM'))()
		end)

		-- Visual Section --

		local ATab = WindowNewTab(Animations)
		local ASection = ATabNewSection(Combos)
		local FSectiion = ATabNewSection(Full Animations)
		local Animate = game.Players.LocalPlayer.Character.Animate

		-- Combos -

		ASectionNewButton(mage and zombie, Combo 1, function ()
			
			Animate.idle.Animation1.AnimationId = httpwww.roblox.comassetid=616158929
			Animate.idle.Animation2.AnimationId = httpwww.roblox.comassetid=616160636
			Animate.walk.WalkAnim.AnimationId = httpwww.roblox.comassetid=616168032
			Animate.run.RunAnim.AnimationId = httpwww.roblox.comassetid=616163682
			Animate.jump.JumpAnim.AnimationId = httpwww.roblox.comassetid=707853694
			Animate.climb.ClimbAnim.AnimationId = httpwww.roblox.comassetid=616156119
			Animate.fall.FallAnim.AnimationId = httpwww.roblox.comassetid=616157476
			game.Players.LocalPlayer.Character.Humanoid.Jump = true
		end)

		ASectionNewButton(pirate and zombie, Combo 2, function ()
			Animate.idle.Animation1.AnimationId = httpwww.roblox.comassetid=616158929
			Animate.idle.Animation2.AnimationId = httpwww.roblox.comassetid=616160636
			Animate.walk.WalkAnim.AnimationId = httpwww.roblox.comassetid=616168032
			Animate.run.RunAnim.AnimationId = httpwww.roblox.comassetid=616163682
			Animate.jump.JumpAnim.AnimationId = httpwww.roblox.comassetid=750782230
			Animate.climb.ClimbAnim.AnimationId = httpwww.roblox.comassetid=616156119
			Animate.fall.FallAnim.AnimationId = httpwww.roblox.comassetid=616157476
			game.Players.LocalPlayer.Character.Humanoid.Jump = true
		end)

		ASectionNewButton(knight and zombie, Combo 3, function ()
			Animate.idle.Animation1.AnimationId = httpwww.roblox.comassetid=616158929
			Animate.idle.Animation2.AnimationId = httpwww.roblox.comassetid=616160636
			Animate.walk.WalkAnim.AnimationId = httpwww.roblox.comassetid=616168032
			Animate.run.RunAnim.AnimationId = httpwww.roblox.comassetid=616163682
			Animate.jump.JumpAnim.AnimationId = httpwww.roblox.comassetid=658409194
			Animate.climb.ClimbAnim.AnimationId = httpwww.roblox.comassetid=616156119
			Animate.fall.FallAnim.AnimationId = httpwww.roblox.comassetid=616157476
			game.Players.LocalPlayer.Character.Humanoid.Jump = true
		end)

		ASectionNewButton(toy and zombie, Combo 4, function ()
			Animate.idle.Animation1.AnimationId = httpwww.roblox.comassetid=782841498
			Animate.idle.Animation2.AnimationId = httpwww.roblox.comassetid=782845736
			Animate.walk.WalkAnim.AnimationId = httpwww.roblox.comassetid=616168032
			Animate.run.RunAnim.AnimationId = httpwww.roblox.comassetid=616163682
			Animate.jump.JumpAnim.AnimationId = httpwww.roblox.comassetid=782847020
			Animate.climb.ClimbAnim.AnimationId = httpwww.roblox.comassetid=616156119
			Animate.fall.FallAnim.AnimationId = httpwww.roblox.comassetid=616157476
			game.Players.LocalPlayer.Character.Humanoid.Jump = true
		end)

		-- Full animations --

		FSectiionNewButton(zombie, gives zombie animation, function ()
			Animate.idle.Animation1.AnimationId = httpwww.roblox.comassetid=616158929
			Animate.idle.Animation2.AnimationId = httpwww.roblox.comassetid=616160636
			Animate.walk.WalkAnim.AnimationId = httpwww.roblox.comassetid=616168032
			Animate.run.RunAnim.AnimationId = httpwww.roblox.comassetid=616163682
			Animate.jump.JumpAnim.AnimationId = httpwww.roblox.comassetid=616161997
			Animate.climb.ClimbAnim.AnimationId = httpwww.roblox.comassetid=616156119
			Animate.fall.FallAnim.AnimationId = httpwww.roblox.comassetid=616157476
			game.Players.LocalPlayer.Character.Humanoid.Jump = true
		end)

		FSectiionNewButton(mage, gives mage animation, function ()
			Animate.idle.Animation1.AnimationId = httpwww.roblox.comassetid=707742142
			Animate.idle.Animation2.AnimationId = httpwww.roblox.comassetid=707855907
			Animate.walk.WalkAnim.AnimationId = httpwww.roblox.comassetid=707897309
			Animate.run.RunAnim.AnimationId = httpwww.roblox.comassetid=707861613
			Animate.jump.JumpAnim.AnimationId = httpwww.roblox.comassetid=707853694
			Animate.climb.ClimbAnim.AnimationId = httpwww.roblox.comassetid=707826056
			Animate.fall.FallAnim.AnimationId = httpwww.roblox.comassetid=707829716
			game.Players.LocalPlayer.Character.Humanoid.Jump = true
		end)

		FSectiionNewButton(ninja, gives ninja animation, function ()
			Animate.idle.Animation1.AnimationId = httpwww.roblox.comassetid=656117400
			Animate.idle.Animation2.AnimationId = httpwww.roblox.comassetid=656118341
			Animate.walk.WalkAnim.AnimationId = httpwww.roblox.comassetid=656121766
			Animate.run.RunAnim.AnimationId = httpwww.roblox.comassetid=656118852
			Animate.jump.JumpAnim.AnimationId = httpwww.roblox.comassetid=656117878
			Animate.climb.ClimbAnim.AnimationId = httpwww.roblox.comassetid=656114359
			Animate.fall.FallAnim.AnimationId = httpwww.roblox.comassetid=656115606
			game.Players.LocalPlayer.Character.Humanoid.Jump = true
		end)

		FSectiionNewButton(toy, gives toy animation, function ()
			Animate.idle.Animation1.AnimationId = httpwww.roblox.comassetid=782841498
			Animate.idle.Animation2.AnimationId = httpwww.roblox.comassetid=782845736
			Animate.walk.WalkAnim.AnimationId = httpwww.roblox.comassetid=782843345
			Animate.run.RunAnim.AnimationId = httpwww.roblox.comassetid=782842708
			Animate.jump.JumpAnim.AnimationId = httpwww.roblox.comassetid=782847020
			Animate.climb.ClimbAnim.AnimationId = httpwww.roblox.comassetid=782843869
			Animate.fall.FallAnim.AnimationId = httpwww.roblox.comassetid=782846423
			game.Players.LocalPlayer.Character.Humanoid.Jump = true
		end)

		--[[

			AHHHHHHHHHHHHHHHHH
		]]
		local VTab = WindowNewTab(Visuals)
		local VSection = VTabNewSection(ESP)

		VSectionNewButton(UntitledESP, Esp, function ()
			loadstring(gameHttpGet('httpsraw.githubusercontent.comic3w0lf22Unnamed-ESPmasterUnnamedESP.lua'))()
			
			CoreGuiSetCore(SendNotification, {
				-- Customizable
				Title = ESP,
				Text = Thanks ic3w0lf22!,
				Duration = 2,
			})
		end)

		-- Skin Section --

		local STab = WindowNewTab(Skins)
		local SSection = STabNewSection(DHM skins)

		SSectionNewButton(RedSparkleTime, DHM gun skin, function ()
			setclipboard(3461309563)
		end)

		SSectionNewButton(Blood, DHM gun skin, function ()
			setclipboard(108941805)
		end)

		SSectionNewButton(Red Grime, DHM gun skin, function ()
			setclipboard(280779721)
		end)

		SSectionNewButton(Gold, DHM gun skin, function ()
			setclipboard(134632723)
		end)

		SSectionNewButton(Monster Assault Camo, DHM gun skin, function ()
			setclipboard(142656364)
		end)

		SSectionNewButton(Chill Traingles, DHM gun skin, function ()
			setclipboard(807738026)
		end)

		SSectionNewButton(Blue Bandana, DHM gun skin, function ()
			setclipboard(5657430676)
		end)

		SSectionNewButton(Red Bandana, DHM gun skin, function ()
			setclipboard(5657568372)
		end)

		SSectionNewButton(Worms, DHM gun skin, function ()
			setclipboard(7545514855)
		end)

		SSectionNewButton(LV, DHM gun skin, function ()
			setclipboard(1156146426)
		end)

		SSectionNewButton(Error, DHM gun skin, function ()
			setclipboard(3155472478)
		end)

		SSectionNewButton(Pewdiepie, DHM gun skin, function ()
			setclipboard(2669398912)
		end)

		SSectionNewButton(Creeper Minecraft, DHM gun skin, function ()
			setclipboard(4944059812)
		end)

		-- Misc Section --
		local MTab = WindowNewTab(Misc)
		local MSection = MTabNewSection(Random)

		MSectionNewButton(BTools, Lets your break parts (Not fe), function ()
			Instance.new(HopperBin, game.Players.LocalPlayer.Backpack).BinType = 4
			Instance.new(HopperBin, game.Players.LocalPlayer.Backpack).BinType = 3
		end)

		MSectionNewButton(Shit-Talk (J), Becomes toxic for u, function ()
			local words = {
				trash,
				dogwater,
				Get Good kid,
				Bad at the game,
				Get Rekt kid,
				Mad,
				Your fr dog,
				Even with lock u would be trash,
				You need to get a script frfr
			}

			local player = game.Players.LocalPlayer
			local keybind = j

			local event = game.ReplicatedStorage.DefaultChatSystemChatEvents.SayMessageRequest

			playerGetMouse().KeyDownConnect(function (key)
				if key == keybind then
					eventFireServer(words[math.random(#words)], All)
				end
			end)
		end)
	else
		local CoreGui = gameGetService(StarterGui) -- Variable of StarterGui

		CoreGuiSetCore(SendNotification, {
			-- Customizable
			Title = Not Supported,
			Text = Supported Games list copied,
			Duration = 4,
		})
	end
