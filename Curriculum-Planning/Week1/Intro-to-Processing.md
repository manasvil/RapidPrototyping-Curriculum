Goals:
======

To give students an overview of what the course entails so they can take a decision on if the class is suited for them.

To introduce students to the Processing IDE and show them how to run a basic sketch

To teach them about components such as functions, setup(), loop () and comments

To use some Processing functions to visualize output on screen

To teach students about Creative Commons licensing.

Overview:
=========

Most programming courses follow a bottom-up approach where they expose students to theory first and then dive into making computing projects. However, we adopted a different approach to learning how to code whereby students are exposed to a programming IDE(Processing IDE) in their very first class.

By the end of the second class, students will have learned how to make a simple graphics application that plots sensor data against time.

While students do dive into programming the very first class, there are still **glass boxes** involved in the form of libraries which extend the functionality of the environment and provide code samples or even code snippets from the maker community. The goal is to impart students practical skills to make personalized projects by putting snippets of code together, **demystifying some programming constructs** and giving them t**he confidence that they do not have to be expert coders to make interesting applications**. Some component of the learning is incidental where students learn by experimentation and by failing. But we have found that for the most part being able to make what they like coupled with the inducement of some project deadlines is enough motivation for students to experiment.

In our experience, with two offerings of the class, students have learned about variables, loops, arrays, data types, debugging skills and also much more by way of putting together their projects. Given the diversity of of skill sets in the class some students have an easier time following along than others but this can be leveraged to make a peer-learning environment where the programmers can help the novices. It is also recommended that the TA conduct office hours (1-2 hours a week) for the initial weeks to support students who may not have a very good grasp on programming yet.

**Activity**

Let’s Get started!

**Downloading Processing IDE**

The first thing we want is for students to download the Processing IDE.

What is Processing?

Processing is a flexible software sketchbook and a language for learning how to code within the context of the visual arts. The project was initiated in 2001 by [Casey Reas](https://en.wikipedia.org/wiki/C.E.B._Reas) and [Benjamin Fry](https://en.wikipedia.org/wiki/Benjamin_Fry), both formerly of the Aesthetics and Computation Group at the [MIT Media Lab](https://en.wikipedia.org/wiki/MIT_Media_Lab).\[1\] Since 2001, Processing has promoted software literacy within the visual arts and visual literacy within technology. There are tens of thousands of students, artists, designers, researchers, and hobbyists who use Processing for learning and prototyping.- ([<span class="underline">https://processing.org/</span>](https://processing.org/))\[2\]

Why Processing?

-   Open Source

-   Popular among the maker community(students, artists, designers, researchers, and hobbyists) thus plenty libraries that extend functionality (eg. libraries for multimedia playing video sound etc. )

-   Easy debugging because of popularity, someone may have most likely encountered that error as well

-   High-level programming language, Java based

-   Can connect with Arduino

-   Can write code for Android as well

-   Graphics for not only data visualization but also storytelling and narrative

**It is recommended that students download the environment before class so as to not waste class time in downloads. However, ~10-15 minutes can be spent in class trying to help students who had trouble installing.**

<table>
<tbody>
<tr class="odd">
<td><p>To Download</p>
<p>Content from: <a href="https://processing.org/tutorials/gettingstarted/"><span class="underline">https://processing.org/tutorials/gettingstarted/</span></a></p>
<p>Start by visiting <a href="http://processing.org/download" class="uri">http://processing.org/download</a>(a donation page pops up, but there is an option to select no donation and proceed with the download) and selecting the Mac, Windows, or Linux version, depending on what machine you have. Installation on each machine is straightforward:</p>
<ul>
<li><blockquote>
<p>On Windows, you'll have a .zip file. Double-click it, and drag the folder inside to a location on your hard disk. It could be Program Files or simply the desktop, but the important thing is for the processing folder to be pulled out of that .zip file. Then double-click processing.exe to start.</p>
</blockquote></li>
<li><blockquote>
<p>The Mac OS X version is also a .zip file. Double-click it and drag the Processing icon to the Applications folder. If you're using someone else's machine and can't modify the Applications folder, just drag the application to the desktop. Then double-click the Processing icon to start.</p>
</blockquote></li>
<li><blockquote>
<p>The Linux version is a .tar.gz file, which should be familiar to most Linux users. Download the file to your home directory, then open a terminal window, and type:</p>
</blockquote></li>
</ul>
<blockquote>
<p>tar xvfz processing-xxxx.tgz</p>
<p>(Replace xxxx with the rest of the file's name, which is the version number.) This will create a folder named processing-2.0 or something similar. Then change to that directory:</p>
<p>cd processing-xxxx</p>
<p>and run it:</p>
<p>./processing</p>
</blockquote></td>
</tr>
</tbody>
</table>

The installation process should be smooth for the most part and if all goes well the main window of Processing Development Environment should be visible.

<img src="media/image7.png" style="width:6.25in;height:4.01042in" />

Troubleshooting:

Since there is so much variability in everybody’s setup there is a chance things will go wrong on somebody’s laptop, but we established early on that errors are part of the beauty of this course.

1.  In class we observed that in case of some students while the developing environment showed up the buttons <img src="media/image6.png" style="width:3.62581in;height:0.22917in" /> did not. On a hunch we asked the students to download one of the older stable releases from [<span class="underline">https://processing.org/download/?processing</span>](https://processing.org/download/?processing) and they were up and running.

2.  More troubleshooting tips at: https://github.com/processing/processing/wiki/Troubleshooting

3.  Google search the issue

**Processing Basics**

1.  A Processing program is called a sketch-this is because of its visual arts roots

2.  The buttons on the toolbar can run and stop programs,:

<table>
<thead>
<tr class="header">
<th></th>
<th></th>
<th><blockquote>
<p><img src="media/image4.png" style="width:0.20833in;height:0.20833in" />Run</p>
<p>Runs the sketch. In Java mode, it compiles the code and opens a new display window.</p>
</blockquote></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td></td>
<td></td>
<td><blockquote>
<p><img src="media/image5.gif" style="width:0.22396in;height:0.22396in" />Stop</p>
<p>Terminates a running sketch.</p>
</blockquote></td>
</tr>
</tbody>
</table>

1.  Additional commands are found within the six menus: File, Edit, Sketch, Debug, Tools, Help. The menus are context sensitive which means only those items relevant to the work currently being carried out are available.

2.  There are plenty examples found under File -&gt; Examples

3.  More information about the environment here: [<span class="underline">https://processing.org/reference/environment/</span>](https://processing.org/reference/environment/)

**Learning from Examples**

Now that the students have been walked through the basics of the environment it is time to start putting some code together.

Go to [<span class="underline">processing.org/tutorials/gettingstarted</span>](https://processing.org/tutorials/gettingstarted/)

1.  Do “Coordinate System and Shapes”([<span class="underline">https://processing.org/tutorials/drawing/</span>](https://processing.org/tutorials/drawing/)) and “Color” ([<span class="underline">https://processing.org/tutorials/color/</span>](https://processing.org/tutorials/color/)) tutorials

**Debrief**

1.  What is an IDE?

2.  Ask students what changes they observed

3.  How easy/hard they found it to read the guide

4.  How does the coordinate system in Processing work?

5.  What does rectMode(CENTER) mean, how is it different from rectMode(CORNERS)

6.  How is a shape drawn, what does the order of the numbers mean

7.  If anyone did not get the expected output, what went wrong?

8.  Also explain the structure of the

void setup()

#### **Setup: void setup() { }**

This is a declaration for a function called “setup”. This exact line is required in every Arduino sketch ever.

Any code that lives inside setup()’s curly brackets ({ and }) runs once at the very beginning of your program and then never again.

The setup() function is useful for … setting up the Processing environment for the rest of the program. For eg. suppose you were writing a sketch to count the number of mouse clicks you would want the count to begin from 0 every time the sketch was run and so you would give the value 0 to the variable count, or in other words initialize it to 0, in the setup function.

#### **Loop: void loop() { }**

Like the setup line before it, this is another required Processing function. The loop() function as the name suggests executes in a continuous loop, processing all the statements within in a serial order.

This is where the bulk of your Processing sketch is executed. The program starts directly after the opening curly bracket (}), runs until it sees the closing curly bracket (}), and jumps back up to the first line in loop() and starts all over.

#### **Comments**

You’ll get used to these – and tired of reading them – by the time you’re done experimenting. [Comments](http://arduino.cc/en/Reference/Comments) are lines or blocks of text in your code that are there solely for you or anyone reading your code. Comments have no effect on the operation of your sketch, but they can be immensely helpful in deciphering what you or someone else was thinking when that line of code was written.

Comments come in two flavors: single-line and multi-line. A single-line comment is any line in your code preceded by two forward slashes (//). For example:

> // This is a single-line comment.  
> code\_goes\_here();

A multi-line comment can be used to comment out one or more lines. Multi-line comments are initialized with a slash-asterisk (/\*) and they’re completed with an asterisk-slash (\*/). For example:

> /\* This  
> is  
> a  
> multi-line  
> comment \*/  
> code\_goes\_here();

Comments have no effect on your code’s operation – they’re completely ignored by the Processing environment itself – but they are very useful to you and anyone else reading your code. Always comment your code!

**Activity Continued**

Find an example from either the Tutorials on the website or from under Files -&gt; Examples

run to see the output

tweak the sketch to produce a different output,

save it.

Break into groups of 2 and pick a different example and run the sketch, modify it, save it.

Upload this to T-Square. Check Assignment for details.

Next lecture:

1.  First part of the lecture will be dedicated to discussing the Rudd paper on ‘[<span class="underline">Low vs. High-Fidelity Prototyping Debate.pdf</span>](http://gtprototyping2015.pbworks.com/w/file/99236814/p76-rudd%20Low%20vs.%20High-Fidelity%20Prototyping%20Debate.pdf)’

2.  We will dive deeper into the Processing environment and visit concepts such as variables, arrays etc.

**Homework for next class:**

1.  Reading reflection due on the Prototyping debate

2.  Modify a Processing sketch and upload the code along with screenshots of the output.

Details here:

[<span class="underline">http://gtprototyping2015.pbworks.com/w/file/fetch/99308403/Programming%20Assignment%201%20-%20Processing%20create%20a%20sketch.pdf</span>](http://gtprototyping2015.pbworks.com/w/file/fetch/99308403/Programming%20Assignment%201%20-%20Processing%20create%20a%20sketch.pdf)

Note:

Much of the code we will re-use has been posted under the CC license. However, when borrowing from the maker community it is important to give proper attribution as a way of giving back. Thus, as part of the assignment, students are required to go through the Creative Common licenses ([<span class="underline">https://creativecommons.org/licenses/</span>](https://creativecommons.org/licenses/)) and figure out which theirs was posted under and give appropriate credit at the top of the sketch within comments. If the sketch was Public Domain, students can say so within the comments.

Rationale for this exercise: Since we will be borrowing a lot of material (code, 3-D models, illustrations etc.) from the community, it is important that students be mindful of ethical practises in terms of using resources.

1.https://en.wikipedia.org/wiki/Processing\_(programming\_language)

2.https://processing.org/

**References to dig deeper**

**A lot of the content in these notes has been put together from Sparkfun’s guide**

[<span class="underline">https://learn.sparkfun.com/tutorials/</span>](https://learn.sparkfun.com/tutorials/digital-sandbox-arduino-companion/0-setup-and-loop)

[<span class="underline">https://processing.org/</span>](https://processing.org/)
