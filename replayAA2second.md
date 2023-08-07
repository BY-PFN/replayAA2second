spawn(function()
    while wait() do
        pcall(function() 
           

local args = {
    [1] = "replay"
}

game:GetService("ReplicatedStorage").endpoints.client_to_server.set_game_finished_vote:InvokeServer(unpack(args))

            wait(2)
        end)
    end
end)
