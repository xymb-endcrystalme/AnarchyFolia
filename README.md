## AnarchyFolia
AnarchyFolia is a fork of Folia that includes optimizations needed for anarchy servers 6b6t.org and Endcrystal.me.
All gameplay-breaking/backwards-incompatible optimizations are turned off by default, you need to enable them in a config file.

### Progress
- [x] Compile as a fork
- [ ] Config file
- [ ] Disable shulker drop contents when destroyed
- [ ] [Linear region file](https://github.com/xymb-endcrystalme/LinearRegionFileFormatTools) format
- [ ] Huge (10k+ dubs) stash optimization
- [ ] Limits on entity ticking
- [ ] Hopper & shulker handling optimizations
- [ ] Automatic update upstream

### Configuration
TODO

### Compiling/running
Just refer to original [Folia's README file](https://github.com/PaperMC/Folia), the usage is pretty much the same.
```
./gradlew applyPatches
./gradlew createReobfPaperclipJar
java -jar build/libs/anarchyfolia-bundler-1.19.4-R0.1-SNAPSHOT-reobf.jar
```
