local args = {
    [1] = "fire",
    [3] = "Process",
    [4] = "Rock"
}

game:GetService("ReplicatedStorage"):WaitForChild("Modules"):WaitForChild("NetworkFramework"):WaitForChild("NetworkEvent"):FireServer(unpack(args))
