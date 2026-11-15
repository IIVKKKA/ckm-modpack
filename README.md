# CKM Aeronautics modpack

Minecraft 1.21.1, NeoForge 21.1.266. Managed with packwiz.

## Setup in PrismLauncher
1. Create an instance: Minecraft 1.21.1 + NeoForge 21.1.266, 8 GB RAM, Java 21.
2. Download `packwiz-installer-bootstrap.jar` from this repo into the instance's `minecraft` folder
   (Instance > Folders > Minecraft Folder).
3. Instance > Settings > Custom commands > tick "Override global settings", Pre-launch command:

```
"$INST_JAVA" -jar packwiz-installer-bootstrap.jar https://raw.githubusercontent.com/IIVKKKA/ckm-modpack/main/pack.toml
```

Every launch will then download new mods and remove old ones automatically.
Shaders (Complementary Reimagined, BSL) are included; enable them in Video Settings > Shader Packs.
