  ## THIS PROJECT IS STILL UNDER DEVELOPMENT ##
  ### What is left? ##
  - Unity shader template
  - API call template
  - Default site generation

  ## The Algorithm ##
  The algorithm used in this project is based on the Fortune Sweep algorithm, more specifically the description as proven and explained in Computational Geometry 3rd Edition.
  The algorithm also handles additional edge cases that the book does not describe, including edge cases where sites are collinear or cocircular.

  ## Robustness ##
  The algorithm heavily leans on Jonathan Shewchuk's Adaptive Precision Floating-Point Arithmetic and Fast Robust Predicates for Computational Geometry page, which implements the necessary calculations for robust floating point operations used when detecting the orientation of site triples. 
  Additionally, these robust functions are used to find the determinant of matrices. 

  ## User Calls ##
  TBD
