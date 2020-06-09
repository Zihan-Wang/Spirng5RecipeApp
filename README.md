## Data Format

### Input : 
1. Camera pose txt file. Format : [ timestamp tx ty tz qx qy qz qw ]

2. Cuboids directory of all cuboid txt files. Format : [x y z RotY Width/2 Length/2 Height/2 Rect.x Rect.y Rect.width Rect.height Prob]

### Output: 
1. several submap txt files. Format as [cuboid.x cuboid.y cuboid.z timestamp tx ty tz qx qy qz qw]
