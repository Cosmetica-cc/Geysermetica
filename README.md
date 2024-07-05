<img src="https://Geyser.org/img/Geyser-1760-860.png" alt="Geyser" width="600"/>

[![forthebadge made-with-java](https://forthebadge.com/images/badges/made-with-java.svg)](https://java.com/)

[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Build Status](https://ci.opencollab.dev/job/Geysermetica/job/master/badge/icon)](https://ci.opencollab.dev/job/GeysermeticaMC/job/Geysermetica/job/master/)
[![Discord](https://img.shields.io/discord/613163671870242838.svg?color=%237289da&label=discord)](https://discord.gg/aQh5SJEUBm)
[![Crowdin](https://badges.crowdin.net/Geyser/localized.svg)](https://translate.Geysermc.org/)

Geysermetica is a bridge between Minecraft: Bedrock Edition and Minecraft: Java Edition, closing the gap from those wanting to play true cross-platform with Cosmetica Capes.

Geyser is an open collaboration project by [CubeCraft Games](https://cubecraft.net).

## What is Geysermetica?
Geysermetica, but we removed all the other third-party cape servers and replaced them with [Cosmetica](https://cosmetica.cc)!

### Currently supporting Minecraft Bedrock 1.21 and Minecraft Java 1.21.

## Setting Up
Take a look [here](https://github.com/GeyserMC/Geyser/wiki/Setup) for how to set up Geyser.

[![YouTube Video](https://img.youtube.com/vi/U7dZZ8w7Gi4/0.jpg)](https://www.youtube.com/watch?v=U7dZZ8w7Gi4)

## What's Left to be Added/Fixed
- Near-perfect movement (to the point where anticheat on large servers is unlikely to ban you)
- Resource pack conversion/CustomModelData
- Some Entity Flags
- Structure block UI

## What can't be fixed
There are a few things Geyser is unable to support due to various differences between Minecraft Bedrock and Java. For a list of these limitations, see the [Current Limitations](https://github.com/GeyserMC/Geyser/wiki/Current-Limitations) page.

## Compiling
1. Clone the repo to your computer
2. [Install Maven](https://maven.apache.org/install.html)
3. Navigate to the Geysermetica root directory and run `git submodule update --init --recursive`. This command downloads all the needed submodules for Geysermetica and is a crucial step in this process.
4. Run `mvn clean install` and locate to the `target` folder.

## Contributing
Any contributions are appreciated. Please feel free to reach out to us on [Discord](https://discord.gg/aQh5SJEUBm) if
you're interested in helping out with Geysermetica.

## Libraries Used:
- [Adventure Text Library](https://github.com/KyoriPowered/adventure)
- [NukkitX Bedrock Protocol Library](https://github.com/NukkitX/Protocol)
- [Steveice10's Java Protocol Library](https://github.com/Steveice10/MCProtocolLib)
- [TerminalConsoleAppender](https://github.com/Minecrell/TerminalConsoleAppender)
- [Simple Logging Facade for Java (slf4j)](https://github.com/qos-ch/slf4j)
