# Project

**Due: Thursday, December 16, 4:00pm CDT**

This is an empty repository for your course project.  You should add your project files to this repository, fill out the readme file, and then commit and push to complete your submission.

*If you run into a technical problem with GitHub, such as an error due to a large file size, then you can alternatively submit a Google Drive link to download a zip file of your project.  In this case, you should add the link to the Submission Information below and commit the readme file to the repository .* 

## Submission Information

#### Team Members:

1. Akar (Ace) Kaung, <kaung006@umn.edu>
2. Nilei Pan, <pan00128@umn.edu>

#### Third Party Assets:

1. Weapons: *[Blink](https://assetstore.unity.com/packages/3d/props/weapons/free-rpg-weapons-199738)*

#### Project Description:

This project contains the implementation of telekinesis grabbing and storing object. With the telekinesis grabbing, user can select the object from far away then with the movement of the hand controller, the selected object will either come toward the user’s position or get thrown away. For the storage feature, user will be able to store up to 4 items that they want to store.

#### Instructions:

Download .apk link: *[Bionic_pointing_and_grabbing](https://drive.google.com/drive/folders/104JPe4OljoR1rPTS0E01siShoL-ZTamT?usp=sharing)*

###### **Telekinesis grabbing**
1)	Touch the select trigger button on the controller to activate the laser (laser is just a guiding component).
2)	Point the laser to any objects and if the object is grabbable, the laser color will change to Purplish.
3)	Press and hold the select trigger button and move the controller
- *To make the object come toward the user*: Move the controller toward you
- *To make the object thrown away*: Move the controller outward you at the desire direction
4)	The select trigger button must be hold until the object stops in front of the user, once the object halt in front of the user it will start to float (this is to give the sensation of having the telekinesis ability), otherwise, the object will cease to move and just fall onto the ground.

###### **Storing objects**
To store:
1)	Grab the object using right hand controller 
2)	Move the right-hand controller close enough to the box near the left-hand controller (once its close enough, the box will expand)
3)	If expands, release the grab button and it will be stored
Note: Objects cannot be store in the box which another object is already being stored

To take out stored objects:
1)	Move the right-hand controller close enough to the box where the desired object is being stored (once its close enough, the box will expand)
2)	Press the grab button and move the right-hand controller away from the box
3)	The object will come out as the original size as when it was stored

## Rubric

Graded out of 80 points. 

1. UI Contribution (25).  How significant is the UI contribution of the project? Is the project simply an application, or does it have a substantial focus on new UI technology? How novel and creative is the system?
2. Technical Complexity (25). Projects should represent a substantial implementation effort.
3. Usability (25).  Does the project work as intended?  Are there any serious usability problems or bugs?  
4. Documentation (5).  Are all the functions sufficiently described in the documentation?  Are the instructions clear?

Make sure to document all third party assets in your readme file. ***Be aware that points will be deducted for using third party assets that are not properly documented.***

## Submission

You will need to check out and submit the project through GitHub classroom.  **Make sure your APK file is in the root folder.** Do not remove the `.gitignore` or `README.md` files.

Please test that your submission meets these requirements.  For example, after you check in your final version of the assignment to GitHub, check it out again to a new directory and make sure everything opens and runs correctly.  You can also test your APK file by installing it manually using [SideQuest](https://sidequestvr.com/).

If your project is intended for use on a PC with Oculus Link, then you should include a Google Drive link to download a zip file of your build folder instead of an APK file.

## License

Material for [CSCI 5619 Fall 2021](https://canvas.umn.edu/courses/268490) by [Evan Suma Rosenberg](https://illusioneering.umn.edu/) is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).

The intent of choosing CC BY-NC-SA 4.0 is to allow individuals and instructors at non-profit entities to use this content.  This includes not-for-profit schools (K-12 and post-secondary). For-profit entities (or people creating courses for those sites) may not use this content without permission (this includes, but is not limited to, for-profit schools and universities and commercial education sites such as Coursera, Udacity, LinkedIn Learning, and other similar sites).   