# 9. Ray Tracing

> Rainzor

## Content

- Implement path tracing algorithm.
- Importance sampling for environment map lighting.
- Set up scene (code, json) and render it

The requirements and methods based on the contents of two folders: `(1) documents` and `(2) project`.

### (1) Documentation `documents` [->](documents/) 

Requirements and some auxiliary materials for this assignment.

### (2) Source code `project ` [->](project/)

Basic code framework for this project (Complete).

## Rendering Result

<center><p>Figure 1: Only direct light</p></center>
<img src="./images/img-path-tracing/rst_dir.png" style="zoom:50%;" />
    

<center><p>Figure 2: Global Illumination</p></center>  
<img src="./images/img-path-tracing/rst_full.png" style="zoom:50%;" />
 
 
<center><p>Figure 3: Global Illumination by important sampling</p></center>  
<img src="./images/img-path-tracing/rst_full_impSamp.png" style="zoom:50%;" />


<center><p>Figure 4: Global Illumination with high spp</p></center>  
<img src="./images/img-path-tracing/rst_high_spp.png" style="zoom:50%;" />


## Reference

[1] [Framework](https://github.com/Ubpa/USTC_CG/tree/master/Homeworks/9_PathTracing)
