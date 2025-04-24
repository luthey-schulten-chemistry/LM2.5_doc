# LM2.5_doc
This is the documentation for Lattice Microbe v2.5

## How to update

```bash
ghp-import -n -p -f ./doc
```

# To-do List

## 1.Finish clean up the html-docs for LM2.5.

- [ ] update the installation procedure (Hongyi)
- [ ] Create the navigation bar
- [ ] update the visualization part with VMD
- [ ] introduction part update



## 2. Include several new python functions

+ [ ] Include the function to preprocess the trajectory before loading into the VMD using CPU multi cores (Hongyi)

+ [ ] Include the  function to discretize the trajectory by frame to reduce the size (Hongyi)

+ [ ] Include a function to directly import species and reactions from SBML model. (quite standard check `stochpy`  )

  

## 3. Maintain a developer log 

when you modify any important functions to accept new parameters, mention it in the developer log under`Lattice-Microbes/docs/changelog.txt`

## 4. All api function check

check all API functions in `jLM`  to make sure it works as it stated. 

## 5. RDME functions 

+ [ ] optimize the kernel to ignore the empty region 
+ [ ] add a diffusion type to allow exclusively diffuse. 





