    local success = exports['sgoc_camera']:StartSgocCamera()
    if success then
        ESX.ShowNotification('Udane')
    elseif not success then
        ESX.ShowNotification('Nie Udane')
    end