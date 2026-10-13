  ## THIS PROJECT IS STILL UNDER DEVELOPMENT ##
  ### What is left? ##
  - Unity shader template
  - API call template
  - Default site generation

  ## The Algorithm ##
  The algorithm used in this project is based on the Fortune Sweep algorithm, more specifically the description as proven and explained in Chapter 7 of [Computational Geometry 3rd Edition](https://dl.acm.org/doi/10.5555/1370949).
  The algorithm also handles additional edge cases that the book does not describe, including edge cases where sites are collinear or cocircular.

  ## Robustness ##
  The algorithm heavily leans on Jonathan Shewchuk's [Adaptive Precision Floating-Point Arithmetic and Fast Robust Predicates for Computational Geometry](https://www.cs.cmu.edu/~quake/robust.html) page, which implements the necessary calculations for robust floating point operations used when detecting the orientation of site triples. 
  Additionally, these robust functions are used to find the determinant of matrices. 

  ## How To Use This Project ##
  To view a simple output for how the project works, simply download the entire unity project and run it.\
  To use this project for yourself in a preexisting Unity project, download only the files in Assets/Scripts, which include all files necessary for Voronoi generation given a set of input sites, and optional upper and lower bounds for the bounding box's XY coordinates. /
  PS - If you use this project for a school project or something larger please let me know! I love seeing my stuff in the wild :p
  ### User Calls ###
  TBD
