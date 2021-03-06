# fabricUtils
This is as a collection of useful bits of code for manipulation of data inside the Fabric Engine plataform. Basic components are written in KL and exposed as canvas nodes. Higher level presets are canvas only.

## Main Components
### Characters
Presets for loading FBX characters, drawing characters with multiple meshes and transforming character animation from  global to local space.

### Clips, TrackSets and Tracks
Nodes to deal with clips, tracks, and tracksets. Presets for cumulating Xfo, Vec3 and Scalar values as trackSets.

### Converters
Presets for converting Bones, Poses, Orientations, Scalars, Vectors, and Xfos back and forth.

### Dynamics
Presets for extracting implicit dynamic information from Xfos.

### FileIO
Reading and writing character pose clips to CSV files (quaternions only). Reading of BVH files (limited to local orientation of joints, reads translation only from the root node). Writing Clips as JSON files.

### Filters
Filters for arrays.

### Kinematics
Basic retargeting. Name mapping and orientation transfers. Simple footskating detector, but no fullbody-ik techniques at the moment.