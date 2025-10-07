# Unreal Template Project

*Unreal template project. Includes, ignore files, lfs setup files (attributes).*

To start with this Unreal template, you can start a new repository in the course you want and under 'Template' use the 'unreal_template' repository. Then select 'Git Content', give a name to your repository and then click 'Create'. 

Alternative, you can go the the unreal_template repository (Go to Explore, and under repositories type 'unreal_template' without the quotes) and on the right top side you will see 'Fork'. Click it, as owner select the course (organization) you want, rename your repository, and fork. If you go now to the course, you should see your new repo.

When your repository is ready, you can rewrite your 'README.md' to reflect your project, or if you don't need one you can delete it. 

## No uassets LFS

Sometimes, if the your levels and blueprints are small enough, it might be better to version them with normal Git instead of Git LFS. You can also try this if
your project is having issues with levels dissappearing when using LFS. 

### To use this
Make a new repo using this template. On your computer, delete the .gitattributes file (you might need to enable hidden files), and rename no_uassets.gitattributes
to .gitattributes. Commit and then copy your project over. Make sure that LFS is not tracking .uasset and umap files. 
