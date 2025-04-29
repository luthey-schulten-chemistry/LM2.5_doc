# LM2.5_doc
This is the documentation for Lattice Microbe v2.5

## How to update

Simply push the latest html files to the main branch, and the documentation webpages will be updated automatically.

# To-do List

## 1.Finish clean up the html-docs for LM2.5.

- [x] update the installation procedure (Hongyi)
- [ ] Create the navigation bar
- [ ] update the visualization part with VMD
- [ ] introduction part update
- [ ] add new examples for CME and RDME. 



## 2. Include several new python functions

+ [ ] Include the function to preprocess the trajectory before loading into the VMD using CPU multi cores (Hongyi)

+ [ ] Include the  function to discretize the trajectory by frame to reduce the size (Hongyi)

+ [ ] Include a function to directly import species and reactions from SBML model. (quite standard check `stochpy`  )

  

## 3. Maintain a developer log （All developers)

when you modify any important functions to accept new parameters, mention it in the developer log under`Lattice-Microbes/docs/changelog.txt`

## 4. All api function check(Hongyi)

check all API functions in `jLM`  to make sure it works as it stated. 
+ [ ] Add documentation and explanation for CME realted package in API.

## 5. RDME functions 

+ [ ] optimize the kernel to ignore the empty region 
+ [ ] add a diffusion type to allow exclusively diffuse.
+ [ ] add particle size to fully reflect the size of particles in the site lattice, to decide how many particles can actually be in the one lattice. 





