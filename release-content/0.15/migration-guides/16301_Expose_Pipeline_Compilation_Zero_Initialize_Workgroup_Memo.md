- add `zero_initialize_workgroup_memory: false,` to `ComputePipelineDescriptor` or `RenderPipelineDescriptor` structs to preserve 0.14 functionality, add `zero_initialize_workgroup_memory: true,` to restore bevy 0.13 functionality.