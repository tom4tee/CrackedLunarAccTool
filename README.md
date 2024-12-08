![Image](/media/logo.png)
# CrackedLunarAccTool
A tool which modifies the accounts.json file in Lunar Client to add cracked accounts. But ported to Python 
# Original Creator
This tool was not made 100% by me, the original creator is Whatlify. I only ported the C# code to Python. (You can find the original Repository [here](https://github.com/Whatlify/CrackedLunarAccountTool))
## How does it work? (Explained by Whatlify)

Lunar Client doesn't check whether or not your Microsoft Account is valid or even owns a copy of Minecraft. Therefore, you can add accounts via the accounts.json located in your user folder (C:\Users\YourWindowsUsernameHere\\.lunarclient\settings\game) as an example. There's other json values such as localId which also accept any placeholder value so I've set them to whatever UUID you entered as that works fine. You can also does this entire process manually if you have some basic computer knowledge as I mentioned above.

## Getting Started

### Dependencies
* Colorama
* Windows 10-11 or any windows version compatible with .NET Framework 4.7.2
* .NET Framework 4.7.2 (it's installed by default)
* A brain

### Building it (For Dumbs)
* Just run "python main.py" on some terminal 

### Using It

* Open the executable file.
* Depending on the option you choose it'll either add, remove or view current accounts.
* If you want to add an account choose your username and make sure it's 3-16 characters long and doesn't contain special characters or multiplayer won't work (click [here](https://www.minecraftforum.net/forums/minecraft-java-edition/suggestions/3007464-minecraft-username-rules) for further info).
* Then choose a UUID of a player that has the skin you want by going to [NameMC](https://namemc.com/) and picking your preferred one.
* That's basically it.

## Help

If it doesn't work make sure you have Lunar Client installed and ran any version of Lunar Client or make sure to run the program as administrator.

## Version History

* 1.0
    * Initial Release

## License

This project is licensed under the MIT License - see the LICENSE.md file for details

## Acknowledgments

Inspiration, code snippets, etc.
* Games2day - Originally released his own version of this in python and allowed me to make a rewrite.
* Whatlify - Originally Creator of This Tool.
