Application
![image](https://user-images.githubusercontent.com/43515480/232025692-c7ed17e4-0fc2-47c9-9898-0994505d603a.png)
![image](https://user-images.githubusercontent.com/43515480/232025765-417a248b-d902-4c2c-ac7f-05c770d3751b.png)
![image](https://user-images.githubusercontent.com/43515480/232025784-49a3f391-2bed-47f9-b344-5502d3e5f5b4.png)
DNS NAME, Public IP

![image](https://user-images.githubusercontent.com/43515480/232025874-253185a7-2743-400e-b4ac-ebbce702814c.png)

inside network : Port 80
![image](https://user-images.githubusercontent.com/43515480/232026016-c3450007-9b34-458d-b642-c9f55127b61e.png)

for IIS Role
Internet explorer -->Tool -> Internet option -->security -> Internet
mark custom all
![image](https://user-images.githubusercontent.com/43515480/232026335-99258173-1cae-4caa-a222-fb83dc779448.png)

inside local server
![image](https://user-images.githubusercontent.com/43515480/232026454-b95374f4-3be2-4c23-a16d-6ecb513277b6.png)
web server IIS

![image](https://user-images.githubusercontent.com/43515480/232026563-bcff0cd6-a3c2-413b-b3d6-596c3397260b.png)
all file inside inetpub-->WWWRoot
![image](https://user-images.githubusercontent.com/43515480/232026762-5e00d1d2-46e8-4570-bc9e-880b2c48816f.png)

web site build on local Server 

Let's Migrate on Azure
![image](https://user-images.githubusercontent.com/43515480/232027093-1ed646d4-2f85-4bff-8b90-a4d42ec45fb9.png)
![image](https://user-images.githubusercontent.com/43515480/232027184-4973faf8-0426-4f42-bde1-68c8ccf9752b.png)
![image](https://user-images.githubusercontent.com/43515480/232027200-dce4dad1-6f54-4e15-bb80-9471d929e4e1.png)
![image](https://user-images.githubusercontent.com/43515480/232027269-881d8fd5-9bb4-4569-b597-838acc9a5fe0.png)
Download app service migration assistant in VM machine..
![image](https://user-images.githubusercontent.com/43515480/232031145-915df4ef-1054-4775-b703-ad2f22f3b442.png)
![image](https://user-images.githubusercontent.com/43515480/232031165-437b7200-4078-4a07-ab0b-6449e90d0ef5.png)
![image](https://user-images.githubusercontent.com/43515480/232031533-1a72ba1d-37ea-444e-bbd4-3f6c29ace32a.png)



![image](https://user-images.githubusercontent.com/43515480/232026129-64f0f095-2835-4784-b6dd-a5e4e672073e.png)


Database


![image](https://user-images.githubusercontent.com/43515480/232009176-a1e77308-1f99-4009-9e23-f224215bc893.png)
![image](https://user-images.githubusercontent.com/43515480/232010762-c1a5328b-48af-4c01-9986-927eb0e9f664.png)
temporary access via firewall
![image](https://user-images.githubusercontent.com/43515480/232010891-a4d388b1-c3e1-4f59-a834-addcd67a34ec.png)
![image](https://user-images.githubusercontent.com/43515480/232010912-daa9e0ca-7d17-40cc-8d27-da7b922c72e8.png)
![image](https://user-images.githubusercontent.com/43515480/232011177-7a9ef540-ad84-4211-9532-b6073bb3d94b.png)
![image](https://user-images.githubusercontent.com/43515480/232016172-09a639b7-cbae-406a-a2fb-0546634091fd.png)
Source & Destination (Need to check for production)
![image](https://user-images.githubusercontent.com/43515480/232016302-4b6b7b15-c01e-4254-b697-044b1abe5e6a.png)
![image](https://user-images.githubusercontent.com/43515480/232016442-8d65df09-44e0-4a6d-8dfe-7f464b862a89.png)
![image](https://user-images.githubusercontent.com/43515480/232019510-25b134e0-9d7f-4d89-9046-6f778359ef15.png)




![image](https://user-images.githubusercontent.com/43515480/232035914-04b60bcb-a70e-405d-95fd-c01805335fc9.png)


Logging for app services: <br/><br/>

**Logging: To enable Azure Diagnostics, navigate to your Azure Web Application and select App Service Logs. <br/>
Turn on Application Logging (Blob) and click on Storage Containers to create a new storage container that will connect the logs.**

https://www.crowdstrike.com/guides/azure-logging/security-concepts-and-best-practices/

![image](https://user-images.githubusercontent.com/43515480/232036422-39419c97-b065-41aa-9ce9-fc7ae0ea2a81.png)
