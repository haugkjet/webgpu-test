# webgpu-test

This demo shows Conways Game of Life using Webgpu, following the tutorial in

https://codelabs.developers.google.com/your-first-webgpu-app#0

In bindgroup i had to add visibility FRAGMENT in order to make it work.
From:
visibility: GPUShaderStage.VERTEX | GPUShaderStage.COMPUTE,

visibility: GPUShaderStage.VERTEX |GPUShaderStage.FRAGMENT | GPUShaderStage.COMPUTE,


Demo (need browser that support webgpu)

https://webgpu-test.vercel.app/
