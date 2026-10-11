# OTHMANE-HUB
... 
local code = [[
local enumValues, whiteColor, indigoAccentColor, fullCornerRadius, blackColor, cornerRadius6, slateButtonColor, collapsedSize, mutedRedSurfaceColor, cornerRadius7, zeroSize, oliveDisabledColor, fillSize, lightTextColor, navyColor, darkBackgroundColor, cornerRadius5, purpleAccentColor, darkSurfaceColor, redColor, grayColor, sliderFillSize, defaultButtonSize, verticalFillSize, cornerRadius8, centerAnchor, deepNavyColor, goldColor, standardRowSize, cornerRadius10, alertRedColor, lightRedColor, greenColor, cornerRadius4, orangeColor, panelBackgroundColor, violetColor, mediumGrayColor, _cachedStealPrompt, _cachedStealTarget, uiBuildYield
local button1, button2, button3, createEspBillboard, addInlineScaleSlider, selectedPet, segmentCrossesPortal, buildDetourRoute, getMutationRank
local newInstance = Instance.new
local function setProperties(instance, properties)
  local parent = properties.Parent
  properties.Parent = nil
  for propertyName, value in pairs(properties) do
    instance[propertyName] = value
  end
  if parent then
    instance.Parent = parent
  end
  return instance
end
local spawnLineEnabled = false
local registerCleanupConnection, PlayersService, localPlayer, TeleportService, InputService, RunService, HttpService, ContentProviderService, StarterGuiService
local TweenService, LightingService, TextService, sharedPriorityItems, isAutoPurchaseAllowed, WorkspaceRoot, fileSystemAvailable, earlyUISettings, isMobile, resetCharacterSafely
local espEnabled, espHighlights, espBillboards, trackedESPItems, instantClonerEnabled, selectTargetKey, baseHubVisible, uiVisible, transparentPlotsEnabled, rainbowBeamEnabled
local plotBeam, plotBeamAttachPlayer, createPlotBeam, plotsFolder, toggleClearBase, placeId, jobId
do
  do
    local routeRunService, equipRoutingTools, computeOptimizedRoute, traverseRouteVelocity, applySmoothVelocityRamp, upperFloorThreshold, lowerBasePositions, upperBasePositions, lowerFloorY, findClosestBaseIndex
    local getTargetAnimalPosition, teleportToTarget
    do
      local equipTeleportTool, computeFallbackRoute, suppressCharacterAnimations, moveAlongRoute, stopRootMotion, localPlayer2, lowerFloorRoutes, upperFloorRoutes
      do
        local isPathClear, routePlayersService, localPlayer3, routeIgnoredInstances
        local moveThroughRoute
        do
          local isStrictObstacle, pathClearance, isLooseObstacle, PathfindingService, movementPlayersService, maxVerticalSpeed, waypointArrivalRadius, cardinalDirections
          do
            local netFolder, remoteHashSecret, decodeRemotePath, computeSha256Binary
            do
              do
                local getSynchronizer
                do
                  if not game:IsLoaded() then
                    game.Loaded:Wait()
                  end
                  enumValues = {
                    gothamBoldFont = Enum.Font.GothamBold,
                    gothamBlackFont = Enum.Font.GothamBlack,
                    gothamSemiboldFont = Enum.Font.GothamSemibold,
                    touchInput = Enum.UserInputType.Touch,
                    primaryMouseButton = Enum.UserInputType.MouseButton1,
                    keyboardInput = Enum.UserInputType.Keyboard,
                    mouseMovementInput = Enum.UserInputType.MouseMovement,
                    textAlignLeft = Enum.TextXAlignment.Left,
                    textAlignCenter = Enum.TextXAlignment.Center,
                    textAlignRight = Enum.TextXAlignment.Right,
                    verticalAlignCenter = Enum.TextYAlignment.Center,
                    easingOut = Enum.EasingDirection.Out,
                    easingIn = Enum.EasingDirection.In,
                    quadEasing = Enum.EasingStyle.Quad,
                    backEasing = Enum.EasingStyle.Back,
                    quintEasing = Enum.EasingStyle.Quint,
                    truncateAtEnd = Enum.TextTruncate.AtEnd,
                    layoutOrderSort = Enum.SortOrder.LayoutOrder,
                    excludeRaycastFilter = Enum.RaycastFilterType.Exclude,
                    siblingZIndex = Enum.ZIndexBehavior.Sibling,
                    deadHumanoidState = Enum.HumanoidStateType.Dead,
                    Players = game:GetService("Players"),
                    ReplicatedStorage = game:GetService("ReplicatedStorage"),
                    RunService = game:GetService("RunService"),
                    Workspace = game:GetService("Workspace"),
                    HttpService = game:GetService("HttpService"),
                    TweenService = game:GetService("TweenService"),
                    UserInputService = game:GetService("UserInputService"),
                    TeleportService = game:GetService("TeleportService"),
                    CoreGui = game:GetService("CoreGui"),
                    Lighting = game:GetService("Lighting"),
                    Debris = game:GetService("Debris"),
                    SoundService = game:GetService("SoundService"),
                    PathfindingService = game:GetService("PathfindingService"),
                    TextService = game:GetService("TextService"),
                  }
                  whiteColor = Color3.fromRGB(255, 255, 255)
                  indigoAccentColor = Color3.fromRGB(99, 102, 241)
                  fullCornerRadius = UDim.new(1, 0)
                  blackColor = Color3.fromRGB(0, 0, 0)
                  cornerRadius6 = UDim.new(0, 6)
                  slateButtonColor = Color3.fromRGB(74, 86, 128)
                  collapsedSize = UDim2.new(1, 0, 0, 0)
                  mutedRedSurfaceColor = Color3.fromRGB(60, 40, 50)
                  cornerRadius7 = UDim.new(0, 7)
                  zeroSize = UDim2.new(0, 0, 0, 0)
                  oliveDisabledColor = Color3.fromRGB(80, 80, 60)
                  fillSize = UDim2.new(1, 0, 1, 0)
                  lightTextColor = Color3.fromRGB(220, 220, 230)
                  navyColor = Color3.fromRGB(50, 50, 100)
                  darkBackgroundColor = Color3.fromRGB(12, 12, 18)
                  cornerRadius5 = UDim.new(0, 5)
                  purpleAccentColor = Color3.fromRGB(160, 100, 170)
                  darkSurfaceColor = Color3.fromRGB(30, 30, 35)
                  redColor = Color3.fromRGB(255, 0, 0)
                  grayColor = Color3.fromRGB(150, 150, 150)
                  sliderFillSize = UDim2.new(0.85, 0, 0, 1)
                  defaultButtonSize = UDim2.new(0, 100, 0, 30)
                  verticalFillSize = UDim2.new(0, 0, 1, 0)
                  cornerRadius8 = UDim.new(0, 8)
                  centerAnchor = Vector2.new(0.5, 0.5)
                  deepNavyColor = Color3.fromRGB(8, 8, 16)
                  goldColor = Color3.fromRGB(255, 215, 0)
                  standardRowSize = UDim2.new(1, 0, 0, 34)
                  cornerRadius10 = UDim.new(0, 10)
                  alertRedColor = Color3.fromRGB(255, 50, 50)
                  lightRedColor = Color3.fromRGB(255, 100, 100)
                  greenColor = Color3.fromRGB(100, 255, 100)
                  cornerRadius4 = UDim.new(0, 4)
                  orangeColor = Color3.fromRGB(255, 140, 0)
                  panelBackgroundColor = Color3.fromRGB(25, 25, 35)
                  violetColor = Color3.fromRGB(140, 80, 255)
                  mediumGrayColor = Color3.fromRGB(120, 120, 120)
                  _G._othmaneHUI = _G._othmaneHUI
                    or function()
                      local success, callResult = pcall(function()
                        local isConditionMet = gethui or get_hidden_gui or gethiddenui
                        return isConditionMet and isConditionMet()
                      end)
                      if success then
                        success = typeof(callResult) == "Instance"
                      end
                      if success then
                        return callResult
                      end
                      local success2, callResult2 = pcall(function()
                        return cloneref(enumValues.CoreGui)
                      end)
                      if success2 and typeof(callResult2) == "Instance" then
                        return callResult2
                      end
                      return enumValues.CoreGui
                    end
                  do
                    local snapshot = _G
                    local othmaneN = _G._othmaneN
                    if not othmaneN then
                      local function getValue()
                        local randomGenerator = Random.new()
                        local function getValue()
                          local items = {}
                          for i = 1, 16 do
                            items[i] = string.char(randomGenerator:NextInteger(97, 122))
                          end
                          return table.concat(items)
                        end
                        return {
                          tpp = getValue(),
                          tcp = getValue(),
                          mf = getValue(),
                          la = getValue(),
                          is = getValue(),
                          pt = getValue(),
                          tf = getValue(),
                          tla = getValue(),
                        }
                      end
                      othmaneN = getValue()
                    end
                    snapshot._othmaneN = othmaneN
                  end
                end
                task.spawn(function()
                  if not enumValues.Players.LocalPlayer then
                    return
                  end
                  local function onCharacterAdded(character)
                    if
                      not (
                        character:FindFirstChild("HumanoidRootPart") or character:WaitForChild("HumanoidRootPart", 10)
                      )
                    then
                      return
                    end
                    local function onDescendantAdded(descendant)
                      if descendant:IsA("BasePart") and descendant.Name ~= "__HITBOX" then
                        pcall(function()
                          descendant.CollisionGroup = "Default"
                        end)
                      end
                    end
                    for _, descendant in ipairs(character:GetDescendants()) do
                      onDescendantAdded(descendant)
                    end
                    character.DescendantAdded:Connect(onDescendantAdded)
                  end
                  if enumValues.Players.LocalPlayer.Character then
                    task.spawn(onCharacterAdded, enumValues.Players.LocalPlayer.Character)
                  end
                  enumValues.Players.LocalPlayer.CharacterAdded:Connect(onCharacterAdded)
                end)
                do
                  local packages = enumValues.ReplicatedStorage:WaitForChild("Packages")
                  packages:WaitForChild("Synchronizer")
                  packages:WaitForChild("Net")
                end
                do
                  local state = nil
                  getSynchronizer = function()
                    if state then
                      return state
                    end
                    local success, callResult = pcall(function()
                      return require(enumValues.ReplicatedStorage:WaitForChild("Packages"):WaitForChild("Synchronizer"))
                    end)
                    if success and type(callResult) == "table" then
                      state = callResult
                    end
                    return state
                  end
                end
                local knownSynchronizerChannels, getValue11, getValue2, handleState, findTarget2
                do
                  local items = {}
                  knownSynchronizerChannels = {}
                  local isEnabled = false
                  getValue11 = function(data)
                    if data == nil then
                      return nil
                    end
                    if items[data] then
                      return items[data]
                    end
                    local state13 = getSynchronizer()
                    if not state13 then
                      return nil
                    end
                    local state2 = nil
                    pcall(function()
                      state13:WaitAndCall(data, function(data)
                        state2 = data
                      end)
                    end)
                    if state2 then
                      items[data] = state2
                      knownSynchronizerChannels[data] = true
                    end
                    return state2
                  end
                  getValue2 = function(data)
                    local state = getValue11(data)
                    if not state then
                      return nil
                    end
                    local state2 = rawget(state, "CacheTable")
                    return type(state2) == "table" and state2 or nil
                  end
                  handleState = function()
                    local plots_2 = enumValues.Workspace:FindFirstChild("Plots")
                    if plots_2 then
                      for _, child in ipairs(plots_2:GetChildren()) do
                        knownSynchronizerChannels[child.Name] = true
                      end
                    end
                    if enumValues.Players.LocalPlayer then
                      knownSynchronizerChannels[enumValues.Players.LocalPlayer.Name] = true
                    end
                    for _, item in ipairs({
                      "Cycle",
                      "Events",
                      "ServerLuck",
                    }) do
                      knownSynchronizerChannels[item] = true
                    end
                  end
                  findTarget2 = function()
                    if isEnabled then
                      return
                    end
                    isEnabled = true
                    local state14 = getSynchronizer()
                    if not state14 then
                      return
                    end
                    pcall(function()
                      state14.OnChannelCreated:Connect(function(data)
                        local state15 = rawget(data, "Index")
                        if state15 ~= nil then
                          items[state15] = data
                          knownSynchronizerChannels[state15] = true
                        end
                      end)
                      state14.OnChannelDestroyed:Connect(function(data)
                        local state16 = rawget(data, "Index")
                        if state16 ~= nil then
                          items[state16] = nil
                          knownSynchronizerChannels[state16] = nil
                        end
                      end)
                    end)
                    pcall(function()
                      local plots = enumValues.Workspace:FindFirstChild("Plots")
                      if plots then
                        plots.ChildAdded:Connect(function(child)
                          knownSynchronizerChannels[child.Name] = true
                        end)
                        plots.ChildRemoved:Connect(function(child)
                          knownSynchronizerChannels[child.Name] = nil
                          items[child.Name] = nil
                        end)
                      end
                    end)
                  end
                end
                do
                  local function getValue12()
                    findTarget2()
                    handleState()
                    return knownSynchronizerChannels
                  end
                  _G._othmaneRawCT = function(data)
                    return getValue2(data)
                  end
                  _G.OthmaneSyncGet = function(data)
                    return getValue11(data)
                  end
                  _G.OthmaneSyncBind = function()
                    return getValue12()
                  end
                  _G.OthmaneSyncAll = function()
                    local items = {}
                    for k in pairs(getValue12()) do
                      local state = getValue11(k)
                      if state then
                        items[k] = state
                      end
                    end
                    return items
                  end
                  local othmaneSync = {
                    Read = function(data)
                      return getValue2(data)
                    end,
                    Channel = function(data)
                      return getValue11(data)
                    end,
                    Indices = function()
                      local items = {}
                      for k in pairs(getValue12()) do
                        items[#items + 1] = k
                      end
                      return items
                    end,
                    AnimalList = function(data)
                      local animalList = getValue2(data)
                      animalList = animalList and animalList.AnimalList
                      return type(animalList) == "table" and animalList or nil
                    end,
                    Owner = function(data)
                      local owner = getValue2(data)
                      owner = owner and owner.Owner
                      if owner == nil then
                        return nil
                      end
                      local isActive = typeof(owner) == "Instance"
                      local isActive2
                      if isActive then
                        isActive2 = isActive
                      else
                        isActive2 = type(owner) == "table"
                      end
                      if isActive2 then
                        return owner.Name
                      end
                      return tostring(owner)
                    end,
                    Generation = function(data, data2, data3)
                      return _G._othmaneGen and _G._othmaneGen(data, data2, data3) or 0
                    end,
                    ChGet = function(data, data2)
                      if not data then
                        return nil
                      end
                      local state = rawget(data, "CacheTable")
                      if type(state) == "table" then
                        return state[data2]
                      end
                      return nil
                    end,
                  }
                  _G.OthmaneChGet = othmaneSync.ChGet
                  othmaneSync.ScanAll = function(data)
                    local isConditionMet = data or 0
                    local items = {}
                    for _, item in ipairs(othmaneSync.Indices()) do
                      local state = getValue2(item)
                      if type(state) == "table" and type(state.AnimalList) == "table" then
                        local owner = state.Owner
                        local name = owner ~= nil
                            and ((typeof(owner) == "Instance" or type(owner) == "table") and owner.Name or tostring(owner))
                          or nil
                        for k, itemLocal448 in pairs(state.AnimalList) do
                          local index = type(itemLocal448) == "table" and itemLocal448.Index
                          if index then
                            index = not (itemLocal448.Machine and itemLocal448.Machine.Type == "Fuse" and itemLocal448.Machine.Active)
                          end
                          if index then
                            local othmaneGen = _G._othmaneGen and _G._othmaneGen(itemLocal448.Index, itemLocal448.Mutation, itemLocal448.Traits) or 0
                            if isConditionMet <= othmaneGen then
                              local mutation = itemLocal448.Mutation
                              if mutation == "None" or mutation == "" then
                                mutation = nil
                              end
                              items[#items + 1] = {
                                name = itemLocal448.Index,
                                rawIndex = itemLocal448.Index,
                                value = othmaneGen,
                                mutation = mutation,
                                traits = itemLocal448.Traits,
                                owner = name,
                                plot = item,
                                slot = tostring(k),
                                uid = tostring(item) .. "_" .. tostring(k),
                              }
                            end
                          end
                        end
                      end
                    end
                    table.sort(items, function(data, data2)
                      return data.value > data2.value
                    end)
                    return items
                  end
                  _G.OthmaneSync = othmaneSync
                  task.spawn(function()
                    pcall(getValue12)
                  end)
                end
              end
            end
          end
        end
      end
    end
  end
end
]]

local fn = assert(loadstring(code))
fn()
