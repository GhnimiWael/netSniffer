
# About | Network Sniffer
 A network packet sniffer program which uses the **Swing** GUI widget toolkit to display packet data.
 It's name, is a combination of **sniff** and **network**. *Java smells good*.

<p align="center" width="60%">
    <img width="60%"src="https://i.imgur.com/vVYviMT.png"> 
</p>

# Usage
- Install [Java](https://www.java.com/en/download) (JRE) and [Npcap](https://npcap.com) (Windows) | [libpcap](https://www.tcpdump.org) (Linux).
- Download the jar release from the build folder
- Run the jar.

    ```
    java -jar netSniffer.jar
    ```

# Build

## Dependencies

- OpenJDK 17
- Gradle
- git

> Dependencies can be installed via [scoop](https://scoop.sh). (Windows only)
```
scoop bucket add java
scoop install openjdk17 gradle git
```

## Procedure

- Clone the repo.

    ```
    git clone https://github.com/GhnimiWael/netSniffer
    ```

- Navigate to the repo's folder.

    ```
    cd netSniffer
    ```
- Build.

    ```
    gradle build
    ```
    >**Note**: The Jar is created under the *build/libs* folder.
