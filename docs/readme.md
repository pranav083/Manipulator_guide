# Documentation

## Directory Structure overview

For better understanding of the documentation given in this folder follow this directory structure to navigate yourself to the right product:

```
docs
    |
    |-readme.md (for project overview)
    |--project-name-v# (with different version)
        |
        |-readme.md (for product overview)
        |-sections
            |
            |-readme.md (section overview)
            |-changelog.md
            |-sub-section
                |
                |-readme.md (sub section overview)
                |-hardware.md
                |-software.md
                |-changelog.md
```
Small description about the above  directory structure:

* `product` folder: It have the list of all the product with their particular version no.for easy navigation of the product.
  * `readme.md` : It provide the basis overview of what are the product which are currently their in the repository.
* `product-name-v#` folder : It contain all the information regarding the product development either in the field of hardware, software etc. 
  * `readme.md` : It provide the basis overview of what are the section present in the section. 
* `section` folder : It contain the list of all the subsection in the machine. whith additional folder like `depriciated` and `abandoned` folder which in the better understanding of the development process.
  * `readme.md` : It provide the basis overview of different sub section availble and short link to it.
* `sub-section` folder : It have all the indepth information of the system section all the change history associated to it etc.
    * `readme.md` : It has the full system description of how that section of the machine works.
    * `xyz.md` : These file are their to contain different system requirement file either hardware, software, guide etc.
    * `changelog.md` : It have the history of what ever change being made in the machine over a period of time.    

    **Note:**  For naming the version inside the `changelog.md` file, Use the following method to do so.

    e.g,
        
        Project-name-v# + incremental no.(start from  `0`) + date + (a-z)
                    |          |                             |       |
               riku-v2  +      1                 +    07-may-2021 +  a
        so, it becomes - v2.1.070521a 
        (a-z only use when multilple changes are made on same day in a single file)             


# Products List 

**Note :** link are not updated in the readme.
<!-- TODO: Update links below -->
The product which is being going on, Is being listed here with the particular version of the development stage. The content of each and every folder contain the same directory structure described on the home page of the repository [README.md](../readme.md)  

<!-- ## Test Video Link(if any) -->
