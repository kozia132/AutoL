# AutoL
AutoL is a modification of Sk1ers AutoGG (https://github.com/Sk1erLLC/AutoGG) mod for Minecraft that automatically says a selected phrase after a game has ended (on supported servers).

Unlike a lot of other Sk1er mods, this one uses the old ModCore instead of Essential.

## Support
there is none.

## Developing
**Requirements:**
- JDK (Java Development Kit) 8
    * [AdoptOpenJDK](https://adoptopenjdk.net/)
    * [Other OpenJDK distributions](https://en.wikipedia.org/wiki/OpenJDK#OpenJDK_builds)
    * [Oracle JDK (proprietary)](https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html)
    
- A Java IDE, we recommend using [IntelliJ IDEA](https://jetbrains.com/idea/)
 
## Building
**Unix-based systems (GNU/Linux, OSX, etc):**
```bash
$ ./gradlew build
```

**Microsoft Windows:**
```batch
> gradlew.bat build
```

Artifacts will be placed under `build/libs` directory. 

## License
AutoGG and AutoL is licensed under **GNU GPLv3** see: [LICENSE](LICENSE)
