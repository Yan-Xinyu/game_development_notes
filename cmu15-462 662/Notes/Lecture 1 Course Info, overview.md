# Lecture 1 Course Info, overview

- Two main objectives:
  - understand what CG(computer graphics) is about
  - implement first  algorithm to make 3d shapes 

- definition
  - the use of computers to synthesize visual information
  - ... to synthesize and manipulate **sensory**  information
  - ... to turn **digital information** into **sensory stimuli**



### Some theory & systems CG demands

- Theory
  - basic representations (how do you digitally encode shape, motion?) 
  - sampling & aliasing (how do you acquire & reproduce a signal?) 
  - numerical methods (how do you manipulate signals numerically?) 
  - radiometry & light transport (how does light behave?) 
  - perception (how does this all relate to humans?)

- system
  - parallel, heterogeneous processing 
  - graphics-specific programming languages 

### Example: Cube

1. map 3D vertices to 2D points in the image (pinhole model)
2.  connect 2D points with straight lines ( rasterization: diamond rule)