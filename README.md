# Unity - A big picture on game development. - Getting started

[¶](#Unity---A-big-picture-on-game-development.---Getting-started)
==================================================================================================================================

![Unity Logo](https://unity3d.com/profiles/unity3d/themes/unity/images/company/brand/logos/primary/unity-master-black.svg)

Intro:[¶](#Intro:)
------------------

Hello there, It doesn't matter wether you want to pursuade a career in game development or want to just discover the process of how to create a game, a good start would be by learning the amazing engine Unity which has absolutely a lot to offer. Actually, game development nowadays consists of exploiting this power to create 2D/3D games and focus more on the concept and the design rather than physics engines, etc ..

In this article, you will learn how easy it actually is to get your feet wet with Unity and the essentials of starting a project using this game development platform. The chain of processes will be presented in more of a hands-on manner where each task answers a given question.

### How to create a blank project?[¶](#How-to-create-a-blank-project?)

After downloading Unity, and when you first start it, you will be prompted the launch wizard which will give you the ability to create a new project or browse previous projects and download tutorials. To create a new project:

1.  Click on _"New"_
2.  Choose a name for your project
3.  Choose a location for your project, in which all assets and needed files will live.
4.  Click on _"Create project"_ Once that's done, you will need to wait until Unity generates the files needed for beginning your new project.

### How to open a project?[¶](#How-to-open-a-project?)

From your launch wizard, you can select _"Open"_ in order to browse using your file explorer for a desired existing projectproject. Then you can choose _"On Disk"_ to browse local files in your computer or _"In the Cloud"_

### Project files' hierarchy?[¶](#Project-files'-hierarchy?)

![]https://unity3d.com/sites/default/files/styles/original/public/learn/VZfolderstructure0img1.png?itok=VfFkx2IQ)

In order to set our folder structure in Unity, from our _Project_ window (location of all assets and from where we add objects to the scene view) we right click the mouse and hit _Create_ >\> _Folder_ and then give it a name. Now, this folder we created for our assets officially is created under the path we chose for the project. exactly at : {path of project}/Assets/{created folder}

**Note that every change in the folder structure from the project manager affects the project folder and vice versa**

### How to import packages?[¶](#How-to-import-packages?)

The Unity asset store and already done Unity projects provide Unity packages, things you are likely to need while building your very own project. In order to import such packages (**UAS**):

1.  Select _Window_ >\> _Asset store_.
2.  In the search bar type the type of assets you need, you can use the filtering feature to find what best suits your needs.
3.  After selecting the desired package, click on the button _download_ and agree the terms of service. ![](//i.imgur.com/SysTU6F.png)
4.  Once the downloaded package is ready, you can import it using the _import_ button. ![](//i.imgur.com/OwHisWr.png)
5.  After the previous step, you will notice that the assets in the project window. To explore them, you can double-click the added folder.

**To import a specific installed package, you need to right click in the project manager area >> _import package_ >\> {wanted asset folder name}, after that the same steps above apply**

### What are 3D assets?[¶](#What-are-3D-assets?)

When creating your gameplay, you will actually need to add some sort of assets and environments, such as placeholder objects. That can be done by:

1.  Choosing _create_ from the _hierarchy_ panel.
2.  Selecting "3D Object" >> {an object} ![](//i.imgur.com/7nEtCNA.png)
3.  After choosing the desired shape, modifying the dimensions can be done using the _Scale tool_ by dragging the colored cubes . ![](http://i.imgur.com/ANJf9WN.png)

Once you have a boundry (floor), you can add a character. A standard when prototyping games is to insert capsules (3D primitives) to replace/represent casual players, instead of 3D modeling the shape of the character and UVing it and using something like PhotoShop to create the final look and importing everything as assets (animation clips).

*   \### How to import them?

After setting up the 3D model, and making sure it fits Unity scale, and the pivot point then exporting it to the Unity project 's asset/Meshes folder location in fbx format... 
