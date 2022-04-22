# sdf_editor

This package implements a RUST based SDF editor. 

Initially this package will only support loading `.STL` files. Over the time I plan to support `.dae` format as well. Later might also have to look at generating a Unity Scene directly from this utility. 



The SDF file then can be loaded in Gazebo or Ignition simulator!




## Notes:
Workflow can be found in [this PDF](./workflow.pdf)

Ref [7] has a `rust` based URDF Visualiser!

Ref [5] directly describes URDF in python. We don't need a separate XML based URDF file which
can be loaded in Gazebo or Ignition. 



### References:
Making custom URDF using a GUI:
1. Learn OpenGL in Rust: https://rust-tutorials.github.io/learn-opengl/
2. Rust Render STL: https://github.com/gkbrk/rust-renderstl
3. kiss3d (A simple graphics engine in Rust): https://rustrepo.com/repo/sebcrozet-kiss3d-rust-graphics 
4. Node Graph GUI: https://github.com/setzer22/egui_node_graph
5. URDF directly in Python: https://github.com/hauptmech/odio_urdf 
6. Open Rust Robotics: https://github.com/openrr 
7. URDF Visualiser in Rust: https://github.com/openrr/urdf-viz 
8. SDFormat Rust Parser: https://github.com/azm-project/sdformat-rs 
9. 



Unity:
1. Unity URDF Importer: https://github.com/Unity-Technologies/URDF-Importer 
2. Unity Robotics Hub: https://github.com/Unity-Technologies/Unity-Robotics-Hub 
3. Formant's Blog post on Unity: https://formant.io/news-and-blog/2019/10/09/analytics/robots-are-hard-game-engines-are-not-why-we-built-our-own-simulator-using-unity/
4. Unity Robotics Hub: https://forum.unity.com/forums/robotics.623/ 
5. 


Solidworks To URDF:
1. WPI Doc: https://blogs.solidworks.com/teacher/wp-content/uploads/sites/3/WPI-Robotics-SolidWorks-to-Gazebo.pdf


