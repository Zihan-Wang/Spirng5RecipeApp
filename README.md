## Data Format

Input : camera pose txt file. Format as [timestamp tx ty tz qx qy qz qw]
        cuboids directory. In every cuboid txt file, format as [x y z RotY Width/2 Length/2 Height/2 Rect.x Rect.y Rect.width Rect.height Prob]

output: several submap txt files. Format as [cuboid.x cuboid.y cuboid.z timestamp tx ty tz qx qy qz qw]
