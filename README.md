# Getting Started

You must have Unity version *2022.3.5.f1* installed for intended behaviors.
Please follow this resource from Github to fork and set up the project:
https://docs.github.com/en/get-started/quickstart/fork-a-repo

# Workflow Recommendations - Merging on a team project

Make sure each member has a different branch for their working environments and keep one person per feature to limit overlap and possible conflicts. When it comes to Unity Scenes, you cannot manually fix merge conflicts by picking the line(s) of code you want. To prevent a lot of frustration pay attention to the folder structure in Unity. In the assets/scenes folder, there are two folders called **[myscenes]** and **production scenes**. When you wok on a feature, make sure you only work on scenes in the **[myscenes]** folder. When you want to give the team your changes, annouce to the team that you are merging ensuring no one else attempts to merge during this time. You will move your changes to the **production scenes**, save, and push to your branch. (Try to limit to adding or subtracting file only - not both). Create a pull request or follow your team's git protocols. Once your files are on the main branch, the rest of the team will pull changes, and merge main into their branch. Since team members are not working on the production scene, they will get no conflicts upon pulling and merging. They can copy/paste changes in production to their scene for their work to continue.

If you have further questions on git or github, please search out other resources or use this for now:
https://docs.github.com/en/get-started/using-git/about-git

# Make this repo better

When forking, you can suggest changes to this repo (or just use it for personal work). If you have some tools or resources you want on this branch, coordinate with a faculty member and work towards pushing your changes to the main project

# Future Plans

As new cohorts come in, we will be updating with the latest LTS release from Unity. We should have branches that have different templates like VR, AR, and 3D URP.
