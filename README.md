# Unity Low Poly (Work in progress)

Low poly assets for metaverse

## Development environment

- Blender for making low-poly 3D models
- Unity 2022 3.7f LTS

## 1. Testing URP BakedLit shader

In this project, I make Unity generate lightmap UV.

The URP BakedLit shader does not support PBR, so I use Blender to bake 2D Textures for realness.

- Unity project: [TestingBakedLit](unity/TestingBakedLit)
- Settings: [URP BakedLit Shader](docs/URP_BakedLit_Shader)

<img src="docs/URP_BakedLit_Shader/Test.jpg" width=500>

## References

- [URP BakedLit shader](https://docs.unity3d.com/Packages/com.unity.render-pipelines.universal@7.1/manual/baked-lit-shader.html)
- [Blender how to Reduce Poly Count and Bake Textures](https://youtu.be/Yx9TvvnxCAM)

## Links to my Github projects

- [Baking a normal map](https://github.com/araobp/blender-3d/tree/main/bake_normal)
