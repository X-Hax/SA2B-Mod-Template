# Sonic Adventure 2 Battle Mod Template
### A blank mod template for anyone to clone and begin writing their own mod.

To begin coding your own mod, simply clone the repository with the following command:

```git clone https://github.com/X-Hax/SA2B-Mod-Template```

Or by downloading the repository as a zip and working from there.

## How to Use
This repo contains a 'main.cpp' file where you will be doing a majority of your coding. Also contained in the repo is many optional libraries courtesy of the [SA2ModLoader](https://github.com/X-Hax/sa2-mod-loader) which let you better interface with Sonic Adventure 2, allowing you to manipulate game states, objects, characters, score, etc. 

See the [SA2BModding Wiki](https://github.com/X-Hax/SA2BModdingGuide) for more information on what you can do with mods!

## Notes
Some of the libraries included will not automatically update themselves, so please check every so often for updates. You can find the two main dependency libraries here:
- [Libmodutils](https://github.com/X-Hax/sa2-mod-loader/tree/master/libmodutils)
- Programming Folder (Which can be found in your local Sonic Adventure 2 install, after installing the SA2ModLoader)

Note that Libmodutils originally used the legacy 'stdafx.cpp' and 'stdafx.h' instead of the more recent 'pch.cpp' and 'pch.h.' If you update your libraries, please double check and fix the cpp files to ensure that they do include 'pch.h' instead of 'stdafx.h.'

If you need any help, feel free to ask questions at the official [X-Hax Discord](https://discord.gg/gqJCF47).

Happy programming!
