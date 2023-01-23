# Welcome to the Genesys workshops template repository

The purpose of this repository is to provide Genesys partners with guidance on how to create a workshop.

## Repository Structure
```
genesys-workshop-template
├───.github
│   └───workflows
├───archetypes
├───content
│   ├───010-Introduction
│   ├───020-Getting-Started
│   └───090-Conclusion
├───layouts
│   └───partials
├───resources
│   └───_gen
│       ├───assets
│       └───images
├───static
│   ├───css
│   └───images
└───themes
    └───hugo-theme-learn
 ```
## How to Contribute 

Once you have created your own fork, you can begin contributing to the "Content" folder seen in the repository structure above. You can think of the folders within "Content" as modules. For example, if you wanted to add a module about "Setting Up", you would add a folder to the "Content folder" and title it "030-Setting Up". You would then add your information to that module. The number before the title signifies the order of that module. So "030-Setting Up" would come after "020-Getting Started" and before "090-Conclusion". 


![Content](https://user-images.githubusercontent.com/101136030/176939994-2d754875-7924-49fc-bf14-000b64bc00df.jpg)


You can then organize your content within that folder by adding markdown files. To add a markdown file, right click the folder you want this file to appear in and select "New File". Give the submodule a title that reflects its numerical order followed by ".md". For example, if you wanted the module "020-Getting Started" to have 2 "submodules", you would title the first one  "10_first.md" and the second one "20_second.md". (Note: files have to end in ".md" for the system to recognize it as a markdown file).

![Submodules](https://user-images.githubusercontent.com/101136030/175968183-f93d1cab-7b62-42ce-a023-a283d3e32b13.jpg)


To add information to your module's landing page, you can edit the "index.md" file. For example, if I wanted my "030-Setting Up" landing page to have an objective, welcome, etc, I would add that to the "index.md" file.


![Index](https://user-images.githubusercontent.com/101136030/176941800-04b0b2ff-61e4-40c8-bf7c-07cb70923c73.jpg)


Images can be added to the "Images" subfolder under the "Static" folder. Once the images are uploaded to this folder, you can begin referencing them using markdown language.


![Images](https://user-images.githubusercontent.com/101136030/176941904-52a06bc6-051a-48b9-be36-a33e2e60d9b1.jpg)
