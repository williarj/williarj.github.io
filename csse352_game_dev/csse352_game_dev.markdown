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
* Assigned: Friday - Cabbage World (make a "Week2HW" folder in your repo, and put this there)
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
We will be using Unity for this course, you will need to download and [install Unity hub from here](https://unity.com/download).

After install you'll need to make a free account with Unity, you can use your RHIT email or a gmail or any of the other options.

Finish reading this paragraph before you click things. After you have Unity hub installed you should download and install [*Unity 6*](https://unity.com/releases/unity-6) Our testbook uses a slightly older version of Unity (from 2023). 95% of the things in the book will still work as is, but be aware there are some differences.You should be able to click the "Unity Hub" button to have the download launch Hub and get everything set up, regardless of your OS. During install it will prompt you to install Unity Editor, agree. Then you will be prompted to get a personal edition license, agree to this as well. When prompted for which "Components" you need to install, you should add the "WebGL support" if you see it in the list (We can add it later if we need to). It will take a few minutes to install then you will see the appropriate version listed in the "Installs" section of Unity Hub. 

Unity will default to using VisualStudio as the IDE, you can use whatever you want, I will stick to VisualStudio. However, there is a [VSCode extension for Unity](https://marketplace.visualstudio.com/items?itemName=visualstudiotoolsforunity.vstuc). To use this you'll need to tell Unity to make it your editor, go to: *Unity > Preferences External Tools > External Script Editor* and select VSCode (or any other prefered editor). Note, IntelliSense frequently stops working in VSCode (I can't get it to work at all on my Mac). If you find fixes to bugs, feel free to email your instructor.

Unity has some click-intensive activities, you are required to bring a mouse to class for working with this tool. *Track-pads are not sufficient.*

We'll be using Github classroom for code submissions. There will be only one repo for all homeworks. You should add a new folder for each Homework, you should name the folders based on the week they are assigned (e.g. "CabbageWorld" should be in folder "Week2HW" since it is assigned in week 2). When one homework builds on a previous one, please make a new folder and copy all the contents from the old homework over. You can find the [link for the homework assignments repos here](https://classroom.github.com/a/oH_ljSiL)

<h4>Texts</h4>
Required text:

The following book is our primary textbook, some projects in class are based on these, and I recommend you look at the associated readings for each week. This book is available for free through the Logan Library.

1. Hocking, Joe. "Unity in Action: Multiplatform game development in C#" Third edition. *Manning* (ISBN: 1617299332) **Called *UiA* below**

Instructions for free online access:

1. Connect to: https://www.oreilly.com/library-access/
2. Click on "Institution not listed."
3. Enter an email address with the institution domain.
4. Click "Let's Go."
5. You may get an email from O'Reilly asking you to confirm your email and do some initial set-up.
6. You can search for the book at the top of the page or [you can click this link to get to the book](https://learning.oreilly.com/library/view/unity-in-action/9781617299339/)

Optional reading:
This is an excellent book about software design patterns in game development. I'll be pulling examples from this book. I highly recommend you give this a look, but there are no required readings from it.

1.  Baron, David. "Game Development Patterns with Unity 2021" Second Edition. *Pakt* (ISBN: 1800200811)

<h4>Other resources</h4>
*SUPER WARNING* You will probably be using some assets for your games from other people on the internet. You must attribute all assets you use appropriately. If you do not, I will consider it plagiarism and academic misonduct. You should read this section so that you dont find yourself in a problematic position.

For all sources of creative materials below please ensure that you check the license requirements. You may need to add an attributions page to your game somewhere, or at the very least a README in the code. 

Every time you download an asset from any online source you should copy-paste the link into a text document in your repo. Even if you aren't sure you will use the asset. Save **all** the links, and sort out which you used later. It is a tragedy to find the perfect asset and then days or weeks later realize you have lost the source, meaning you cannot use it. Misattributing sources, or not following the rules of whatever CC license is attached to any work will result in an automatic fail for any assignment.

1. [Unity 6 manual](https://docs.unity3d.com/6000.0/Documentation/Manual/UnityManual.html)
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

At the end of week 8 we will host the RHIT annual [Game Jam](https://en.wikipedia.org/wiki/Game_jam). That Friday your instructor will announce a theme for the jam. In a group of 1-4 people you will design and create a game based on the theme. You will be expected to create a design document that specifies the gameplay mechanics, and the software designs of your system. You will be expected to deploy your game and source code online in an appropriate place (e.g. github and itch.io). On Friday of week 10 we will have a demonstration of the games open to the whole class and all of campus.

<h2>Course Administrative Info</h2>

<h4>Formatting guidelines</h4>

Assignments will be submitted and returned via gradescope or github classroom. If you need assistance using these tools contact your instructor.

<h4>Class attendance</h4>
This class will be highly interactive, I expect you to have read and assigned material before class and come prepared to discuss, ask questions, and think deeply about the topics of the day. 

<h4>Use of AI</h4>
Read this carefully, I am allowing (and encouraging) use of LLMs in this class. With some restrictions.

It is expected that any work submitted for assessment represents the intellectual work of the individual(s) submitting the work. Any attempt to pass off the intellectual work of another (including the work generated by Large Language Models, LLMs, like ChatGPT) as their own or without proper attribution is an example of academic misconduct and is subject to the penalties described in the Rose-Hulman Academic Rules and Procedures and Student Handbook documents. However, I believe that LLMs and other AI tools will become standard aids in most fields in our near future. So, I will not ban the use of these tools in this class. Before you use these tools you need to ask yourself:

  1.	Is my use ethical? (e.g. Am I using the tool appropriately? Is [the amount of energy that will be consumed by this query reasonable](https://www.washington.edu/news/2023/07/27/how-much-energy-does-chatgpt-use/)? 
  2. Am I harming others through my use? (e.g. by breaking copyright laws, or removing the opportunity for your peers to learn.)
  2.	Is my use harming my own intellectual growth? (“The one who does the work, does the learning.” should be your mantra)

If you use any LLM or any other AI as part of an assignment, I require you to attach the resulting inputs and outputs from the use to your assignments. This serves a few purposes. 1) I can see how you are using it, to make sure you aren’t missing something important in what you are supposed to be doing. 2) You are more protected from claims of academic dishonesty. 3) I can verify that the tool is not lying to you. 4) We can learn how to better use these tools together. If I discover that you have used an LLM without attribution you will receive a grade penalty appropriate to the severity of the use and I will submit a notice of academic dishonesty to the Dean of Faculty and Dean of Students, per the guidelines in the student handbook. 

You can even ask an LLM to generate a transcript for you, for example you can prompt with: *"Can you produce a printable transcript of this chat in PDF format?"* You should be able to paste the result into a word document, or otherwise download it. (In my recent test I was able to use the "share" button on the document panel in ChatGPT, to create a link. I used the link to go to the document, then I could print to PDF from my browser.) You could also ask it to produce a LaTeX transcript and then use a tex renderer (like Overleaf) to genreate a PDF.

When you do this, you should always include the pdf as the last few pages of any assignment you turn in on gradescope, and also include it in your github repo with a name like "LLMlog.pdf".

*Be warned* ChatGPT frequently gives incorrect answers when working with code that changes a lot. It may give you an answer that would have worked in Unity 2012, but wont work with Unity 6. These LLMs have a HUGE corpus of wrong or outdated answers. So tread carefully. You are an expert software developer, you need to be able to assess when the AI is sending you down a bad path.

<h4>Collaboration</h4>

Collaboration is a key part of the software development process, therefore collaboration is encouraged on homework, quizzes, and laboratories.  When you collaborate, you must properly credit your collaborators and clearly indicate the extent of the collaboration. In all cases, each individual is responsible for understanding and writing out the entire solution. Copying is not collaboration.

Any kind of plagiarism or cheating will result in a severe penalty in the course and Student Affairs will be notified. See [this page](https://www.rose-hulman.edu/campus-life/student-services/registrar/rules-and-procedures/discipline-and-suspension.html) for details.

Most importantly, any actions that reduce your ability or your opportunity to learn can be considered academic misconduct. Make sure you learn!

<h4> Academic Integrity and CSSE Integrity Committee Procedures </h4>

It is critical to maintain academic integrity. It is essential for all students to cite any and all sources of help received in completing coursework. This practice not only fosters a culture of honesty and transparency but also prevents misunderstandings that might otherwise escalate to formal proceedings. Students should also be aware of what is appropriate help on homework assignments – see [What Constitutes Misconduct](https://rosehulman.sharepoint.com/:w:/r/sites/CS/_layouts/15/Doc.aspx?sourcedoc=%7B72D3DC4B-233D-4DF6-8E10-736359A06C80%7D&file=IntegrityPilotPolicy%20-%20What%20Constitutes%20Misconduct.docx&action=default&mobileredirect=true). To ensure fairness and responsibility, any instances of suspected misconduct will be handled through the CSSE Integrity Committee.

If a case of suspected misconduct arises, it will be submitted to the CSSE Integrity Committee for review (see [Policies and Procedures](https://rosehulman.sharepoint.com/:w:/r/sites/CS/_layouts/15/Doc.aspx?sourcedoc=%7B72D3DC4B-233D-4DF6-8E10-736359A06C80%7D&file=IntegrityPilotPolicy%20-%20What%20Constitutes%20Misconduct.docx&action=default&mobileredirect=true) and [possible penalties](https://rosehulman.sharepoint.com/:w:/r/sites/CS/_layouts/15/Doc.aspx?sourcedoc=%7B916E293C-A31A-4493-BDBD-D6B78ED2D3DD%7D&file=IntegrityPilotPolicy%20-%20Penalties%20&%20Evidence.docx=&action=default&mobileredirect=true)). The process includes an initial review of the evidence by the committee, a time for students to explain or admit to potential misconduct, and potentially a hearing to examine the circumstances and evidence. Students are encouraged to continue their studies and engage with the course material and instructor normally throughout the investigation. 

<h4>Concerns or Feedback</h4>

I strongly encourage students to document special academic needs with staff at the Office of Student Affairs and/or the Counseling Center, and then to contact me as soon as possible so that we can work together to provide recommended academic accommodations while protecting your privacy.

If you have any concerns about any course matters, you should tell someone. You can email your instructor, speak to your instructor, or leave anonymous feedback in Moodle. You can also contact the department head, [Student Affairs](https://www.rose-hulman.edu/campus-life/student-affairs/index.html), or another Rose employee you feel comfortable with.

While you are more than welcome to consult any member of our department if you have concerns, we realize it's helpful to have a few names to start with. If you have a concern and are not sure where to go, the following CSSE faculty have volunteered to be help out with any concerns you may have: Amanda Stouder (F222) and Kim Tracy (D216).

This syllabus is subject to revision with prompt notification of enrolled students. 

