# MAAC_3607_Final

# Interacting through the command line

You need Github's Large File Storage (lfs) to work with this repo. It allows us to upload blend files which are normally too large.

If you are working on this repo through the command line, you need lfs installed in your local repository. Everything works the same, lfs does not impact the way you use Git, it only modifies the back-end.

Follow this tutorial to download and install it.
https://git-lfs.github.com/

Go to your local repo, run `$ git lfs install` and `$ git track *.blend` in the parent directory.

** If you are uploading files through the website, you do not need to worry about any of this **

# Directory Structure

This repo is divided into folders, each of which is used for a different part in the project.

The character folder is for all the files/models associated with the robot character.

The room folder is for all the files/models associated with the main spaceship (the room the camera is in)

The space folder is for all the files/models associated with the scene in space.

The misc_props folder is for everything else. All the random props we make (broom, bucket of water, etc.) go here.