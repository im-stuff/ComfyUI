# First TODO:

- modify comfy to run in batch mode.

# DUMP
- Port over all deforum functionality as nodes
  - Make it so that you can load in deforum templates, or stub out entire deforum processes
- Implement graphexec for running without gui slowing down 
- figure out what makes automatic1111 performant over Comfy
  - possibly just implement a graph GUI using the automatic1111 api?
- port over Parseq functionality as nodes?
  - nodes to sequence actions as reactions to music
- Create workflow to generate "3D" visualization, basically map all results in 3 dimensions (adjusting 3 parameters) 
- alllow generation of motion paths in blender
- indidicate when lines are overloappin by having one line "hop" over the other
- allow the creation of "entry" nodes to groups to define arguments needed for a more complex workflwo
- for batch mode (deforum) allow robust preprocessing of source video
- for batch mode (deforum) allow to indicate saving steps of frame generation, with verbose explanation of order of events
- when running in batch mode, have gui that shows progress
- allow app to cache extracted frames, etc
- look at comfy vid2vid
- add nodes for logic that happpnes at a ccertain frame/frame range
- add nodes for binding a property to an audio source file
- allow the ability to build an animation in pieces, and then blend those peices together, sort of like selecting a clip in premier to then render in after effects...
  - while binding those to the music
  - use 'guided images' to allow you to basically plan out how its goign to go, but actually diffuse the inbetween frames
- make it so that you can cache certain things being on/off 
- combine with ebsynth command line tool?
- export group of nodes as single node (create input and output nodes for the node)
  


