# MKSF-Shader
来源 基于Open4es-beta5(https://github.com/Open4Es/Open4Es-Shader-Android)
由于pojavlauncher的最新测试版移除了vgpu，导致Open4es的vgpu版本不起作用，beta5又不是很完美，因此我们研发了这款着色器

特点 这款着色器相当拥有比Open4es更好的视觉效果，更低配的要求，更小的体积

要求 渲染器：gl4es1.1.4，暂不支持iris，和Open4es一样，支持骁龙和联发科P22

未来的更新 未来，我们将添加景深以及光晕

其他 如果无法运行，迁移旧版运行库即可；由于Optifine渲染这个光影的水面有问题，所以暂时移除水面

已知问题 低版本开启色差会出现黑屏(如1.12)
