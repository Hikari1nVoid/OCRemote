# OCRemote

OCRemote is a Blazor-powered web application which allows remote management for your AE2 Network with the help of OpenComputers mod.

## Currently Work In Progress

- Fix documentation.
- Enhance component detection and remove all hard-coded file paths and Component addresses.
- Add more weeb content for my personal preference.

## Deployment

Here are the steps to deploy OCRemote:

1. Install Rider or Visual Studio with .NET 7 SDK.
2. Export the item panel 128*128png from NEI, and change the path in `Controller\AEController.cs`.
3. Configure your in-game OC machine.Magic memories are required as T3.5 only provides 1024kb per stick and they are insufficient in most cases!
4. Modify the HTTP address in `OCServer/server2.lua` and deploy it to your in-game Machine.
5. Get a blazorize token. You can create a `blazorise.txt` in the root directory for the token, or you could ask Cyl18 for it.
6. Make your web server available for your OC machine.A public IPv4 Address may be required for deployment in MP.

## Showcase

Here are some screenshots of our project:

![Screenshot 1](docs/1.png)
![Screenshot 2](docs/2.png)
![Screenshot 3](docs/3.5.jpg)
![Screenshot 4](docs/3.png)
