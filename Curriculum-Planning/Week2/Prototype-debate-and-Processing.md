Goals:

Discuss what a prototype is, why one prototypes and how can one prototype?

To discuss the differences between Low fidelity and HIgh fidelity prototypes

To refresh concepts such as primitive data types(int, boolean), variables, arrays etc.

To learn how to load data from a file in processing

**Class Outline**

**Lecture**

Discussion on Prototyping

Hi-fidelity vs. Low fidelity prototype debate

**Debrief**

Previous weeks activity-What was hard/ easy about processing

**Activity**

Going Deeper with processing- plotting sensor data

**Assignments**

Merge and extend two example sketches to read data from a file and create visualization of sensor data

**Due:** Two weeks from now before class of Week 4

Read Zimmerman, John and Forlizzi, Jodi. "Chapter 6: Research Through Design." Ways of knowing in HCI and write summary and Interactive lamp idea

**Due:** Two weeks from now before class of Week 4

**Discussion- Some points to talk about**
=========================================

**What is prototyping?**
========================

"Prototyping is the iterative development of artifacts – digital, physical, or experiential – intended to elicit qualitative or quantitative feedback." (Geehr, 2008)

**Why should one Prototype?**

Fail early, fail often

Video on Learning from failure: [<span class="underline">https://vimeo.com/69977212</span>](https://vimeo.com/69977212)

More discussion points available at: [<span class="underline">http://hci.stanford.edu/dschool/resources/prototyping/prototyping.pdf</span>](http://hci.stanford.edu/dschool/resources/prototyping/prototyping.pdf)

**What can be a Prototype? **

Sketches • Diagrams & Frameworks • Hand Made Constructions • Machined Constructions • Virtual Models • Graphics • Packaging • Spaces • Role Play, Experiences • Video (d.School Resources)

Prototypes can have varying degrees of fidelity based which stage of the design you are at

**Food for thought question- Is a brick a prototype?**

[<span class="underline">Palm Pilot</span>](http://pretotyping.blogspot.com/2010/08/one-of-my-favorite-pretotype-stories.html) example-

According to a [story on Time magazine](http://www.time.com/time/magazine/article/0,9171,987979,00.html):

*"Hawkins, 40, Palm's chief technologist and Pilot's creator, designed one of the first handheld computers, the GRiDPad, a decade ago. It was **an engineering marvel but a market failure** because, he says, it was still too big. **Determined not to make the same mistake twice**, he had a ready answer when his colleagues asked him how small their new device should be: "Let's try the shirt pocket."*

*Retreating to his garage, he cut a block of wood to fit his shirt pocket. Then he carried it around for months, **pretending** it was a computer. Was he free for lunch on Wednesday? Hawkins would haul out the block and tap on it as if he were checking his schedule. If he needed a phone number, he would **pretend** to look it up on the wood. Occasionally he would try out different design faces with various button configurations, using paper printouts glued to the block."*

**Food for thought Video: **

Do you really need fancy tools for prototyping?

[<span class="underline">Prototyping iOS 7 interface in Word l</span>](https://www.youtube.com/watch?%20v=RZp7BvQJnU8&list=PLkTfLuE2Kz-5g8Na6ocRB4vNvgOR1WWV&index=1) - Prototyping an iOS feel using Microsoft Word

‘How long did you think it took to prototype the experience of wearing Google glass?’

Video (Rapid Prototyping google glass):

1.  Prototyping Google glass- https://www.youtube.com/watch?v=d5\_h1VuwD6g

Key points about the video:

-   use of everyday materials

-   choice of materials is influenced by one’s familiarity with with them, one could have used a Kinect sensor to prototype a similar experience- follow the path of least resistance

-   Wizard of Oz. prototyping- faking functionality to test with users

-   Detailed note on Wizard of Oz Prototyping- [<span class="underline">http://futureofstuffchallenge.org/download/prototype/bootleg-wizardofoz.pdf</span>](http://futureofstuffchallenge.org/download/prototype/bootleg-wizardofoz.pdf)

> Or same note also available at
>
> [<span class="underline">https://dschool.stanford.edu/wp-content/uploads/2011/03/BootcampBootleg2010v2SLIM.pdf</span>](https://dschool.stanford.edu/wp-content/uploads/2011/03/BootcampBootleg2010v2SLIM.pdf)

**Lo fidelity vs. Hi Fidelity paper(Rudd) Reading Discussion**

Since much of this class is about getting students comfortable building prototypes of varying degrees of fidelity, this debate is highly relevant. Discussion may also serve to open up some people’s minds about high-fidelity prototyping, as there is a school of thought that believes that you can get enough user feedback using low-fi prototypes without spending too much time on details

Key points and Questions to discuss:

-   pros and cons on Low Fidelity - High Fidelity (you can ask a student to pen these on the board) with input from the class

-   does fidelity have more to do with the appearance(form) or functionality?

-   when should you design a high fidelity prototype and when will a low-fidelity prototype suffice?

Interesting perspectives we heard in class-

-   with high-fidelity prototypes users may be more about sharing their honest feedback because of how close the prototype looks to a product whereas with a low-fi prototype they’d be more comfortable suggesting changes because of its sketchiness

**Debrief (Intro to Processing)**
=================================

What was difficult, what was easy about it?

Were the tutorials easy to follow?

Did anyone make mistakes? How did they figure out what was wrong and how did they fix it?

Does anyone want to share with the class what they made?

Recapture Processing

-What is an IDE?

-What is the organization of code and flow in Processing Development Environment? -What do setup() do, what do loop() do?

-How many times do they run?

**Activity (Going deeper with Processing, Reading and Visualizing Data assignment)**
====================================================================================

The goal of the next Homework assignment is for students to make a plot data from an accelerometer(x,y,z coordinates) as it changes in time.The data is stored in **a file** called accelerometer.txt and is **read line by line** instead of being received real-time for the sake of simplicity. Show the dataset to the students as well.

**Setup- The instructor/TA should load sketches along with students and have their screen projected in class.**

**Step 1:** **Demonstration of expected outcome**

Run the sketch that has been attached in this folder and demonstrate the output of their next programming assignment

We can break this problem down into two parts:

1.  Reading from dataset

2.  Visualization of information

To achieve this output we will make use of two example codes that address each of the above mentioned parts and combine them with necessary modifications to get our expected output.<img src="media/image6.png" style="width:2.21706in;height:3.24479in" />

**Step 2: Walk Through Read from file example**

a)The sample code for this can be found under File - &gt; Examples -&gt; File IO -&gt; LoadFile1

The following code sequentially reads x, y coordinates from a file called positions.txt and plots them on the screen.

b)Before we dive in the code it is worth **looking at how data in the positions.txt file has been organized. **

**In the Processing menu bar one can go to Sketch(ketch&gt;&gt;Open Sketch Folder to find the folder for this sketch(both WIndows and MAC)**

The file stores corresponding x and y co-ordinates separated by a tabbed space(8-single spaces) and different pairs of values individual lines.

eg.

x1 y1

x2 y2

…

**Analogy-**

This information is important because it will help us unpack the data correctly when we are trying to read individual elements. This is akin to reading dates that are conventionally separated by the symbol / . Assuming date is in mm/dd/yy the first number before the / symbol is the month, the number after is the date and the number after the second / symbol is the year. The / symbol thus acts as a delineator that separates numerical values and helps read the information.

There are other ways that the data could have been packed for eg. we could have agreed that all numbers will be represented as two digit thus producing mmddyy which would make it possible to make sense of 122515 as December 25th ‘15. It is important to realize that data could be packed in multiple ways but we ought to know the format when trying to access it.

**Other key points:**

-String\[\] lines - what do the square brackets mean, explain arrays

-what is index being used for? Talk about variables in programming

-what is loadStrings(“positions.txt”); explain how this is a function provided by Processing, what do students think this function does?

-explain the split( ) , why the value received from loadString() is being split?

\- what does void mean? Discuss return types. What value do students think loadStrings() returns?

\- other constructs such as if statement and the semicolon and ;blocks { }

\- consider statement if (pieces.length == 2) , why this check? what would students have to change here for their own accelerometer dataset?

-What else would they have to change?(add another variable int z to receive the value of z)

-What is the separator in positions.txt for x and y values, how does the separator between change in the accelerometer.txt dataset?

-Why are some variables declared outside of setup? global vs. local scope

<table>
<tbody>
<tr class="odd">
<td><p>/**</p>
<p>* LoadFile 1</p>
<p>*</p>
<p>* Loads a text file that contains two numbers separated by a tab ('\t').</p>
<p>* A new pair of numbers is loaded each frame and used to draw a point on the screen.</p>
<p>*/</p>
<p>String[] lines;</p>
<p>int index = 0;</p>
<p>void setup() {</p>
<p>size(200, 200);</p>
<p>background(0);</p>
<p>stroke(255);</p>
<p>frameRate(12);</p>
<p>lines = loadStrings(&quot;positions.txt&quot;);</p>
<p>}</p>
<p>void draw() {</p>
<p>if (index &lt; lines.length) {</p>
<p>String[] pieces = split(lines[index], '\t');</p>
<p>if (pieces.length == 2) {</p>
<p>int x = int(pieces[0]) * 2;</p>
<p>int y = int(pieces[1]) * 2;</p>
<p>point(x, y);</p>
<p>}</p>
<p>// Go to the next line for the next run through draw()</p>
<p>index = index + 1;</p>
<p>}</p>
<p>}</p></td>
</tr>
</tbody>
</table>

**Step 3: Walk Through Visualizing **

&gt;&gt;The sample code for this can be found under File - &gt; Examples -&gt; Input-&gt; MouseSignals

1.  Run the sketch and figure out how mouse clicks affect the output

2.  Notice interger arrays xvals, yvals, zvals- explain indexing in arrays

3.  What is **width**?- Processing environment provides this **constant**

4.  Why is the size of the array equal to **width?-** we are displaying not just the current status of the mouse but also past values a history of values. At a time we can only display as many values along the x-axis as the width of the screen. This is almost like a series of values where we can only display a window of values and as new values come in the window slides forward and previous values are discarded.

Note-since it is assumed that the values in the dataset are changing successively with time it can be considered a time-series graph. We however do not know how the time is increasing. Are the values recorded every second or every millisecond or practically continuously?

<img src="media/image2.png" style="width:4.53292in;height:2.55729in" />

Image from [<span class="underline">http://www.sourcecodefiles.com/uncategorized/sliding-window-protocol</span>](http://www.sourcecodefiles.com/uncategorized/sliding-window-protocol)

1.  In our program the window is represented by the arrays. The first part of the draw function is responsible for updating the arrays with the new incoming values and discarding old values.

2.  Once students understand how indexing in an array works show how in our example new values are added to the end of the array at width-1 index and the other values shift one to the left.

3.  The first for block shifts old values to one left- what is a loop-give a high level view

4.  The next statement assigns new values to the last position in the array

5.  We then want to visualize this data- The first step is to draw the canvas

> rect(0, height/3, width, height/3+1); This statement draws that central band that divides the screen into three parts

10. FInally we use another loop to plot different streams for xvals, yvals and bvals(button click)-- notice two functions point and line--see difference in output

11. What are the parameters for both functions?

12. Relate this to how there are three sensor streams in accelerometer.txt

**Step 4 Show the expected output for this programming assignment and give an overview of what students are supposed to do. Relate this to the previous two examples and how students may merge those.**

<img src="media/image5.png" alt="Screen Shot 2016-04-18 at 10.37.29 PM.png" style="width:5.81771in;height:3.77592in" />

Key points- 3 different regions

A label for each of the sections

Plot of the sensor streams- line connecting different points

Values change against time- does this resemble the point() graph or the line() graph?

Other requirements-

Students required to create a different function

Use good variable name, Comment code well- good code hygiene

Read other requirements from the assignment description

**Troubleshooting tips**

The TA may use these to help students debug their code during office hours-

&gt;Read console output to see any compile time errors

&gt;Isolate different parts of the code and use console output to see which parts are being executed vs. which are causing trouble for eg. your code may be reading values correctly but the visualization code may be incorrect

&gt;Remember the draw function draws over previous canvas- this may cause unexpected output eg. in our current example if we fail to reset canvas background to its grey color the visualizations would keep drawing on the canvas creating a zig-zaggy mess

&gt;Remember to change the color and set stroke width before making plots

&gt;Some students used the point function instead of line function to draw their graphs which led to an unexpected output

&gt;Always remember there’s Stackoverflow!

References and Digging deeper

[<span class="underline">https://www.smashingmagazine.com/2014/10/the-skeptics-guide-to-low-fidelity-prototyping/</span>](https://www.smashingmagazine.com/2014/10/the-skeptics-guide-to-low-fidelity-prototyping/)

[<span class="underline">http://hci.stanford.edu/dschool/resources/prototyping/prototyping.pdf</span>](http://hci.stanford.edu/dschool/resources/prototyping/prototyping.pdf)

What do Prototypes Prototype?

[<span class="underline">https://uwdata.github.io/hcid520/readings/Houde-Prototypes.pdf</span>](https://uwdata.github.io/hcid520/readings/Houde-Prototypes.pdf)
