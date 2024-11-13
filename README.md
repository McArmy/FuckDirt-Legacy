# FuckDirt
v1.4.3 - [Changelog](CHANGELOG.md) | [Contributing](CONTRIBUTING.md) | [License](LICENSE)

### Requirements
-   =   Java JDK 8 ([Adoptium OpenJDK](https://adoptium.net/temurin/releases/?package=jdk&version=8) recommended)
- \>=   [RetroMCP-Java 1.0](https://github.com/MCPHackers/RetroMCP-Java/releases)

### Installation
- Clone the repository [`git clone https://github.com/McArmy/FuckDirt-Legacy.git`]
- Enter the directory [`cd ./FuckDirt-Legacy`]
- Download [RetroMCP-Java](https://github.com/MCPHackers/RetroMCP-Java/releases) [`curl -L -O https://github.com/MCPHackers/RetroMCP-Java/releases/latest/download/RetroMCP-Java-CLI.jar`]
- Setup Minecraft b1.1_02 [`java -jar RetroMCP-Java-CLI.jar setup b1.1_02`]
- Decompile Minecraft [`java -jar RetroMCP-Java-CLI.jar decompile`]
- Apply source code patches [`java -jar RetroMCP-Java-CLI.jar applypatch`]
- Recompile Minecraft [`java -jar RetroMCP-Java-CLI.jar recompile`]
- Apply resource patches to `minecraft/jars/deobfuscated.jar` with a file archiver like [7-Zip](https://www.7-zip.org/), [WinRAR](https://www.win-rar.com/), [FileRoller](https://fileroller.sourceforge.net/), or [xarchiver](https://xarchiver.sourceforge.net/)
- Start Minecraft client [`java -jar RetroMCP-Java-CLI.jar start client`] OR server [`java -jar RetroMCP-Java-CLI.jar start server`]

### Contribution
- Edit source code files at `minecraft/src` or `minecraft_server/src` with a source code editor like [Eclipse IDE](https://eclipseide.org/), [IntelliJ IDEA](https://www.jetbrains.com/idea/), or [Visual Studio Code](https://code.visualstudio.com/)
- Recompile Minecraft [`java -jar RetroMCP-Java-CLI.jar recompile`]
- Start Minecraft client [`java -jar RetroMCP-Java-CLI.jar start client`] OR server [`java -jar RetroMCP-Java-CLI.jar start server`]
- Change configuration files at `minecraft_any/game` or `minecraft_server/game`
- Apply resource patches to `minecraft/jars/deobfuscated.jar` with a file archiver like [7-Zip](https://www.7-zip.org/), [WinRAR](https://www.win-rar.com/), [FileRoller](https://fileroller.sourceforge.net/), or [xarchiver](https://xarchiver.sourceforge.net/)
- Create source code patches [`java -jar RetroMCP-Java-CLI.jar createpatch`]
- Create Minecraft mod builds [`java -jar RetroMCP-Java-CLI.jar build`]

See [contributing](CONTRIBUTING.md) for more information.

### Prerequisites
- Download and install Java JDK 8 ([Adoptium OpenJDK](https://adoptium.net/temurin/releases/?package=jdk&version=8) recommended)
- Ensure your PATH environment variable contains the ``bin`` directory for your Java JDK 8 installation before any other Java JDK or Java JRE installations
- Ensure your JAVA_HOME environment variable is set to the root directory for your Java JDK 8 installation
- Ensure your default Java version is your Java JDK 8 installation