#Life.io MetLife US Direct


![alt text](https://github.com/kellydern/Life-features/blob/master/assets/logo.png)


This is the repository of features the MetLife US Direct client project. All project files include the user journey, wireframes, assets (including photos, illustrations, icons etc.), and high-fidelity mock-ups. Each sketch file is accompanied by their exported artboards, to view and compare the differences between versions.

##Set-Up
To manage design files, first install the <a href="https://github.com/mathieudutour/git-sketch-plugin">Sketch plugin</a> and follow the instructions to set up.

###Tips for managing files/artboards
- Give each artboard a meaningful title
- Create a new branch when you start working on a new feature. From the Plugin, go to Plugins > Git > New branch.
- Save the file
- When you're ready to commit, export the artboards by going to Plugins > Git > Generate files for pretty diffs
- Push your changes to the remote. (Plugins > Git > Push)
- Create a pull request to the master branch.

###Tips for naming convention
- Use client name + feature name + date for Sketch file names. For example, Lifeio_RewardsTracking_092616
- Artboard names should be organized chronologically (1.1, 1.2, 1.3 etc.)

###Large file storage
- If the Sketch or other design files are too large to store, follow the <a href="https://git-lfs.github.com/">Git Large File Storage (LFS)</a> instructions to get started.
+ Download and install `git lfs install`
+ Select the file types you'd like Git LFS to manage. In our case, Sketch files. `git lfs track "*.sketch"`
+ Commit and push 
`git add file.psd`
`git commit -m "Add design file"`
`git push origin master`

###Design file notation
- To take notes within the Sketch files, or view the Notebook plugin,  <a href="http://marcosvid.al/sketch-notebook/">download and set-up the plugin</a>
- To view notes, select the artboard and use Control > Option > Command > 0
- To add new notes, select the artboard and use Control > Option > Command > 9
