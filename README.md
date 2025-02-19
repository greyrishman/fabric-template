# fabric-template
A skeleton template for building Minecraft mods using Fabric.

The baseline for this repository was generated using the Fabric Template Mod Generator at [this link](https://fabricmc.net/develop/template). The following advanced options were selected:
- [ ] Kotlin Programming Language
- [ ] Mojang Mappings
- [x] Data Generation
- [ ] Split Client and Common Sources

# Configuring for New Mod Development
To prepare the template for developing your new mod, a few sections need to be adjusted:
- [ ] Within the /net/name directory, change the 'templatefabric' package to what you want your mod's package name to be
- [ ] Within the /net directory, change the 'name' package to what you want your name to be
- [ ] Within the TemplateFabric class, change the class name and MOD_ID values to your mod class name and mod name
- [ ] Within the TemplateFabricDataGenerator class, change the class name value to 'YourModNameDataGenerator'
- [ ] Within the fabric.mod.json file, change the following:
  - [ ] "id": your mod id
  - [ ] "name": your mod name
  - [ ] "entrypoints": change main to your package name and mod class, change fabric-datagen to your package namd and data generator class
