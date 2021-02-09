# ItemPhysic-Lite

### Minecraft version 1.7.10

* Не требует библиотеки CreativeMD
* Не использует конфигурацию
* Полное использование Lite

Чтобы включить в среде используйте VM arguments
- ``-Dfml.coreMods.load=com.creativemd.itemphysic.ItemPatchingLoader``
### Сборка
Чтобы в MANIFEST.MF появились нужные вам строки, добавьте в build.gradle следующий код:
```
jar {
    manifest {
        attributes 'FMLCorePlugin': 'com.creativemd.itemphysic.ItemPatchingLoader'
        attributes 'FMLCorePluginContainsFMLMod': 'true'
    }
}
```
