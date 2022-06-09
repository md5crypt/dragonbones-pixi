# Dragonbones Fork

So dragonbones is dead. I took some time to take the code form https://github.com/DragonBones/DragonBonesJS and

1. updated it to modern js
2. updated it to pixi 6
3. applied a few pull requests hanging on DragonBonesJS
4. removed shared ticker support as I don't want that ticker dependency
5. changed armature display to use Container instead of Sprite

now you can `import { PixiFactory } from "@md5crypt/dragonbones-pixi"` like a normal person
