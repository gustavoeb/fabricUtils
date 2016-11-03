# fabricUtils
This is as a collection of useful bits of code for manipulation of data inside the Fabric Engine plataform. Basic components are written in KL and exposed as canvas nodes. Higher level presets are canvas only.

## Main Components
### Characters
Presets for loading FBX characters, drawing characters with multiple meshes and transforming character animation from  global to local space.

### Converters
Presets for converting a pose or reference pose to Xfo arrays, CSV strings, and back.

### FileIO
Reading and writing character pose clips to CSV files (quaternions only). Reading of BVH files (limited to local orientation of joints, reads translation only from the root node).

### Kinematics
Basic retargeting. Basicly just name mapping and orientation transfers. Simple footskating detector, but no fullbody-ik techniques at the moment.