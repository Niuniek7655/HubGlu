# HubGlu

- How to run backend infrastructure ?

1. Install WSL 2 and docker-engine on your WSL
2. Go to cd /mnt/d/Repos/RafixAndSajmon/src/server/Items (change /mnt/d/Repos/RafixAndSajmon to your project path)
3. Run docker-compose up -d
4. Run command hostname -I to check WSL IP address (we will need it for connect with SQL Server)
5. Connection should look like Server=172.17.64.237;Database=WebGlu;User Id=SA;Password=P@ssw0rd123!;TrustServerCertificate=True; where 172.17.64.237 is one of addresses visible after invoke command hostname -I
