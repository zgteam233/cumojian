# cumojian

a skin of the game Casualties Unknown

一个未知伤亡的皮肤

this skin was open source under the **CC BY-NC-ND 4.0** license

这个皮肤据 **知识共享 署名-禁止商用-禁止演绎 4.0** 协议开源

# Dependence / 依赖

- [BepInEx mod loader 模组加载器](https://github.com/BepInEx/BepInEx)
- [SkinSync 皮肤同步 mod](https://github.com/Bytechey/SkinSync)

# File Structure Example 文件结构示例

```log
Casualties Unknown/
├── BepInEx/
│ └── plugins/
│   ├── SkinSync.dll <- skinsync mod
│   ├── CustomSprites/
│   │  └── mojian/ <- skin file 皮肤文件
│   └──...
└──...
```

# NOTICE 注意事项

in multiplayer (together mod) mode 多人模式下

it's needed that all player must install skinsync to make sure
taht can sync skin properly

需所有玩家安装 skinsync 模组才能正确同步皮肤