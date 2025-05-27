# LM2.5_doc
This is the documentation for Lattice Microbe v2.5
## User feedback

Please create a new issue in the issues session and we will work on it ASAP.

## How to update

Simply push the latest html files to the main branch, and the documentation webpages will be updated automatically.

# To-do List

## 1.Finish clean up the html-docs for LM2.5.

- [x] update the installation procedure (Hongyi)
- [x] Create the navigation bar
- [x] update the visualization part with VMD(Hongyi)
- [ ] introduction part update (citations)
- [ ] add new examples for CME and RDME. Add the galactose example (Tianyu, tutorial can use the one in summer school)
- [x] change the LM document version from 2.4 to 2.5(Hongyi)
- [ ] add the performance plot somewhere to show the benchmark. (Tianyu WU)

## 2. Include several new python functions

+ [x] Include the function to preprocess the trajectory before loading into the VMD using CPU multi cores (Hongyi)

+ [x] Include the function to discretize the trajectory by frame to reduce the size (Hongyi)

+ [ ] Include a function to directly import species and reactions from SBML model. (quite standard check `stochpy`  ) (Hongyi)
     check pyLM, there is it somewhere in CME

+ [ ] Add blender function(Tianyu )
  

## 3. Maintain a developer log （All developers)

when you modify any important functions to accept new parameters, mention it in the developer log under`Lattice-Microbes/docs/changelog.txt`

## 4. All api function check(Hongyi)

check all API functions in `jLM`  to make sure it works as it stated. 
+ [ ] Add documentation and explanation for CME realted package in API. (Hongyi)
+ [ ] Displaygeometry function not work in python 3.10
## 5. RDME functions 

+ [ ] optimize the kernel to ignore the empty region 
+ [ ] add a diffusion type to allow exclusively diffuse.  (Hongyi)
+ [ ] add particle size to fully reflect the size of particles in the site lattice, to decide how many particles can actually be in the one lattice.  (Hongyi)
+ [ ] Change the way to save the stoichiometry matrix



