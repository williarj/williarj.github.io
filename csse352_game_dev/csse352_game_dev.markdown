---
title: RHIT CSSE352 - Video Game Development
permalink: /CSSE352_game_dev
---
 
<h1>RHIT CSSE352 - Video Game Development</h1>

<h2>Course Info</h2>
<h4>Course Description</h4>

An introduction to designing and developing computer games. Topics include game genres, game design, sprites, game physics, collisions, characters, scripting, graphics, and sound. Students will design and implement their own game using an available game engine.

**Prerequisites:** CSSE230

<h4>Instructor</h4>

Robert Williamson - [Robert's schedule](/figs/Rose_Schedule.png)

Office: Moench F205

[Book a meeting with Robert](https://calendly.com/williarj/15min)

<h2>Schedule</h2>

You are assumed to have a working knowledge of object oriented programming, UML, and basic software architecture patterns. If you need a review you should ask for additional sources.

Over the term more details and links to assignments will appear in this schedule. Topics may shift with prompt notice to students, based on interest of the class and pacing of the material.

You are expected to complete readings by Friday of each week. Reading chapters before the start of the week will help, however.

<h3> Week 1 - Unity Intro </h3>
* Readings: Ch 1-2
* Due: Set up and install unity, see [the Tools section below](#tools)
<!-- set up unity, reading docs, sources of art, and sounds, components, cabbage game -->

<h3> Week 2 - Raycasts and physics </h3>
* Readings: Ch 3
* Assigned: Friday - Cabbage World
<!-- Raycasts, build simple AI, component based, add simple game mechanics with some basic score? Number of cabbages collected? Just click cabbages? -->

<h3> Week 3 - Input, Game Managers </h3>
* Readings: Ch 5, Ch 7, Ch 8
* Patterns: Singleton 
* Due: Friday - Cabbage World
* Assigned: Friday - UI Presentation
<!-- Write a tutorial for cabbage world -->

<h3> Week 4 - Scenes and UI  </h3>
* Readings: Ch 4 
* Patterns:  EventBus
* Due: Friday UI Presentation
* Assigned: Friday - Cabbage Tutorial
<!-- * Assigned: Friday - Particle System -->
<!-- build a level design system, Build a particle system, add particles to cabbage world-->

<h3> Week 5 - Sprites and Animations </h3>
* Readings: Ch 9
* Patterns: State Pattern
* Friday (optional): Pixel Art crash course
* Due: Friday - Cabbage Tutorial
<!-- * Due: Friday - Particle System -->
<!-- * Assigned: Friday - Messenger System -->
<!-- Write a Messenger System, have cabbage AIs communicate with game managers -->

<h3> Spring Break </h3>

<h3> Week 6 - Midterm Project</h3>
* Readings: Ch 11, Ch 13
* Due: Friday - Midterm Game Project Demonstrations
<!-- * Assigned: Friday - Cabbage sounds -->
<!-- Deploying code, saving data, add sounds to cabbage world, have them upload to itch.io  -->

<h3> Week 7 - Sound and Modding </h3>
* Readings: Ch 6
<!-- * Due: Friday - Messenger System -->
<!-- Write a modding system or a set of mods? Write a modding system to read in a bunch of level files, add levels to cabbage world? Add new entities to cabbage world via mod? Steam mod workshop integration -- future iteration? -->

<h3> Week 8 - More Game Features and Deploying </h3>
* Readings: Ch 10
* Patters: Visitor
<!-- * Due: Friday - Cabbage sounds -->
<!-- * Assigned: Friday - Cabbage network <!-- extra credit maybe? --> -->
<!-- Networking, high scores for cabbage world, maybe multiplayer cabbages? -->
<!-- power ups, save game, reading files, modding, procedural generation?, ScriptableObjects -->

<h3> Weekend - Game Jam </h3>
* Readings: NA
* Due: Monday - Jam Entry
* Notes: You will make a team repo for your code. You can name your team anything, but your team name must start with the prefix `csse352-2223c-` (e.g. `csse352-2223c-roberts-awesome-team`). [This is the link to your Game Jam repo](COMING SOON)
<!-- Game Jam -->

<h3> Week 9 - Game Demos and Advanced topics </h3>
* Readings: Ch 12
* Assigned: SuperAutoProfs
<!-- demo games to each other and get feedback, procedural generation, basic networking, SAP should include ScriptableObjects for generating
the different characters, and networking to share battles, and record teams etc -->

<h3> Week 10 - Advanced topics </h3>
* Readings: NA
* Due: Jam Entry Updates (Friday we will demo games to campus in the CS labs)
* Due: Friday - SAP
<!-- Add feature to games, build an autobattler with all the features -->
<!-- basic Ai and have an "AI" off? -->

<!--
TOPICS THAT NEED TO EXIST:
* scenes, loading
* saving data
* changing settings
* multiplayer?
* random generation -- spelunky map thing?
-->

<h2>Course Management</h2>
<h4>Course Objectives</h4>

Upon completion of this course, students will be able to:

1. **Apply** software engineering techniques to design and implement video games.
2. **Identify** when to use features of a game engine or build custom software.
3. **Explain** why they have chosen particular design elements for their software.

<div id="tools"></div>
<h4>Tools</h4>
We will be using Unity for this course, you will need to download and install Unity hub [from here](https://unity.com/download). 

After install you'll need to make a free account with Unity, you can use your RHIT email or a gmail or any of the other options.

Finish reading this paragraph before you click things. After you have Unity hub installed you should download and install [*Unity 2020.3*](unityhub://2020.3.11f1/99c7afb366b3) released June 15, 2021, If that link does not work you can go to the [Unity download archive](https://unity.com/releases/editor/archive) and navigate to the correct version. This is a slightly older version of Unity, we're using this to stay consistent with the textbook. You should be able to click the "Unity Hub" button to have the download launch Hub and get everything set up, regardless of your OS. During install it will prompt you to install Unity Editor, agree. Then you will be prompted to get a personal edition license, agree to this as well. It will take a few minutes to install then you will see the appropriate version listed in the "Installs" section of Unity Hub. Check the version of unity that installs from that link, the first time I installed Unity Hub showed only *Unity 2021.3.20f1*, I had to click the link and install a second time to get the correct version (it prompted me to install Visual Studio for Mac the second time). 

Unity has some click-intensive activities, you are required to bring a mouse to class for working with this tool. *Track-pads are not sufficient.*

You can use any IDE you chose for code editing, I'll be using Visual studio, but Unity comes bundles with Mono if you prefer.

We'll be using Github classroom for code submissions, you can find the [link for the homework assignments repos here](https://classroom.github.com/a/oH_ljSiL)

<h4>Texts</h4>
Required text:

1. Hocking, Joe. "Unity in Action: Multiplatform game development in C#" Third edition. *Manning* (ISBN: 1617299332) **Called *UiA* below**

Optional reading:
1.  Baron, David. "Game Development Patterns with Unity 2021" Second Edition. *Pakt* (ISBN: 1800200811)

<h4>Other resources</h4>
For all sources of creative materials below please ensure that you check the license requirements. You may need to add an attributions page to your game somewhere, or at the very least a README in the code. 

Every time you download an asset from any of these links you should copy-paste the link into a text document in your repo. Even if you aren't sure you will use the asset. Save **all** the links, and sort out which you used later. It is a tragedy to find the perfect asset and then days or weeks later realize you have lost the source, meaning you cannot use it. Misattributing sources, or not following the rules of whatever CC license is attached to any work will result in an automatic fail for any assignment.

1. [Unity 2020.3 manual](https://docs.unity3d.com/2020.3/Documentation/Manual/index.html)
1. [OpenGameArt.org](https://opengameart.org/)
1. [List of CC music sources](https://creativecommons.org/about/program-areas/arts-culture/arts-culture-resources/legalmusicforvideos/)
1. [Leshy Sound Effect Designer](https://www.leshylabs.com/apps/sfMaker/)
1. [GIMP - open source art program](https://www.gimp.org/)
1. [Texture Packer - make 2D sprite sheets](https://www.codeandweb.com/texturepacker)
1. [Pyxel Edit - tilesets and pixel art](https://pyxeledit.com/)
1. [Blender - 3D modelling](https://www.blender.org/)

<h2>Assessments</h2>
Assessments in this course will be based on the following items:
* Homework assignments (40%)
* Game jam project (40%)
* Participation in class (including pre-class readings) (20%)

<h5>Homework</h5>
These will usually consist of coding assignments where you will implement part of a system for a game. Occasionally these homeworks may include design and written assignments.

<h5>In-Class Participation</h5>

You are expected to participate in discussions, activities, and some group work as part of class. This grade will reflect your participation in activities and assessments of reading. I don't plan on having reading quizzes, but will implement them if it becomes necessary.

<h5>Game jam</h5>

During week 10 we will host the RHIT (semi)annual [Game Jam](https://en.wikipedia.org/wiki/Game_jam). The preceding Friday your instructor will announce a theme for the jam. In a group of 1-4 people you will design and create a game based on the theme. You will be expected to create a design document that specifies the gameplay mechanics, and the software designs of your system. You will be expected to deploy your game and source code online in an appropriate place (e.g. github and itch.io). On Friday of week 10 we will have a demonstration of the games open to the whole class and all of campus.

A rubric for the assignment will be posted partway through the quarter.

<h2>Course Administrative Info</h2>

<h4>Formatting guidelines</h4>

Assignments will be submitted and returned via gradescope or github classroom. If you need assistance using these tools contact your instructor.

<h4>Class attendance</h4>
This class will be highly interactive, I expect you to have read and assigned material before class and come prepared to discuss, ask questions, and think deeply about the topics of the day. 

<h4>Collaboration</h4>

Collaboration is a key part of the software development process, therefore collaboration is encouraged on homework, quizzes, and laboratories.  When you collaborate, you must properly credit your collaborators and clearly indicate the extent of the collaboration. In all cases, each individual is responsible for understanding and writing out the entire solution. Copying is not collaboration.

Any kind of plagiarism or cheating will result in a severe penalty in the course and Student Affairs will be notified. See [this page](https://www.rose-hulman.edu/campus-life/student-services/registrar/rules-and-procedures/discipline-and-suspension.html) for details.

Most importantly, any actions that reduce your ability or your opportunity to learn can be considered academic misconduct. Make sure you learn!

<h4>Concerns or Feedback</h4>

I strongly encourage students to document special academic needs with staff at the Office of Student Affairs and/or the Counseling Center, and then to contact me as soon as possible so that we can work together to provide recommended academic accommodations while protecting your privacy.

If you have any concerns about any course matters, you should tell someone. You can email your instructor, speak to your instructor, or leave anonymous feedback in Moodle. You can also contact the department head, [Student Affairs](https://www.rose-hulman.edu/campus-life/student-affairs/index.html), or another Rose employee you feel comfortable with.

While you are more than welcome to consult any member of our department if you have concerns, we realize it's helpful to have a few names to start with. If you have a concern and are not sure where to go, the following CSSE faculty have volunteered to be help out with any concerns you may have: Amanda Stouder (F222) and Kim Tracy (D216) or appropriate BIO faculty.

This syllabus is subject to revision with prompt notification of enrolled students. 

