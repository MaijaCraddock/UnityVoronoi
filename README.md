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

  ## User Calls ##
  TBD
