# Bandicoot
C2 Framework in C# to handle reverse shells

![image](https://github.com/user-attachments/assets/f9511d27-f56f-4ee3-bfa9-9ef3bb1f296f)

## Run Bandicoot

1. Backend (C# - Reverse Shell Manager + HTTP API)
Navigate to backend/

Compile using .NET SDK:
```
dotnet new console -o BackendApp
cp *.cs BackendApp/
cd BackendApp
dotnet add package System.Text.Json
dotnet run
```
2. Agent (C# - Reverse Shell Client)
Navigate to agent/

Compile:
```
dotnet new console -o AgentApp
cp Agent.cs AgentApp/
cd AgentApp
dotnet run
```
