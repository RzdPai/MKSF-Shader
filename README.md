# MKSF-Shader

<img src="icon.png" width="128">

### 为什么制作

* 基于[Open4es](https://github.com/Open4Es/Open4Es-Shader-Android)
由于pojavlauncher的最新测版移除了vgpu，virgl，并且一些设备不支持zink，angle暂时不支持光影，因此制作了这款着色器

### 特点

* Open4ES最新的Beta7版本添加了一些效果，此光影特点已无，待后续更新

### 已知问题

* 暂不支持iris，和Open4es一样，除骁龙和部分较早联发科机型外会出现渲染Bug，1.17后的OptiFine上不会正常工作(树叶抽搐及矮草不晃已修复但暂未发布)

### 未来的更新

* 景深，动态模糊，云，矿物发光，水下阴影，阴影模糊(新的方案，不再需要阴影采样，帧率更高)
* 由于gl4es更新了OpenGL3.3,可能未来还会有更多高版本OpenGL特有效果(目前Pojav团队还没有更新gl4es的计划)


### 其它
* 如果您的设备支持Vulkan但zink闪退，可以试试在PojavLauncher的目录(/storage/emulated/0/Android/data/net.kdt.pojavlaunch/files/)下创建一个名为custom_env.txt的文件，并在里面输入
```bash
MESA_GL_VERSION_OVERRIDE=4.6
MESA_GLSL_VERSION_OVERRIDE=460
```
* [Open4ES Renewed](https://modrinth.com/shader/open4es-renewed)这款光影效果更好但优化较差
