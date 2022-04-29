---
date: {}
title: Title goes here
published: true
---
This article with serve as an introduction, overview, and quick-start guide to K-Team's Khepera 4 robots. 

The Khepera 4 is a robot platform designed for indoor applications, meant to operate on tables and floor of labs. They are meant to provide a way to test algorithms developed in simulations or on paper in the real world. They're  most often used to test navigation, swarm, and artificial intelligence applications, providing researchers an easy way to see how their code runs on an actual robot. 

## Overview
Website about the Khepera 4: [link](https://www.k-team.com/khepera-iv)

The Khepera 4 is a circular, differential drive robot. It is 140.8 mm in in diameter and can carry up to 2 kg. It has a suite of sensors built-in: 3-axis gyroscope & accelerometer, 5 ultrasonic sensors, 12 infrared sensors, wheel encoders, and a front-facing camera. It also supports various add-ons through connectors at the top of the robot, allowing you to get [upward-facing camera](https://www.k-team.com/extensions-khepera-iv#stargazer) or install a [LIDAR sensor](https://www.k-team.com/extensions-khepera-iv#laserrangefinder). More detailed information can be found in the user manual: [link](https://ftp.k-team.com/KheperaIV/software/Gumstix%20COM%20Y/UserManual/Khepera%20IV%20User%20Manual%204.x.pdf)

## Quick-start guide
The quick-start guide will discuss how to program and compile for the Khepera 4, and how to get it onto the robot.

### Programming
To program for the Khepera 4, you will need a cross-compiler. A compiler turns high-level code into machine code that can be executed by a processor. A cross-compiler does the same thing, but for a processor other than the one compiling the code. While you will be developing and compiling the code on your computer, your computer won't run the code; the Khepera 4 will; therefore, you will need a cross-compiler.

The instructions for installing a cross-compiler can be found in the [user manual ch 5](https://ftp.k-team.com/KheperaIV/software/Gumstix%20COM%20Y/UserManual/Khepera%20IV%20User%20Manual%204.x.pdf#page=36). 

### WiFi

### ssh & scp

## Example

## First subheading
Use this section to cover important terms and information useful to completing the tutorial or understanding the topic addressed. Don't be afraid to include to other wiki entries that would be useful for what you intend to cover. Notice that there are two \#'s used for subheadings; that's the minimum. Each additional sublevel will have an added \#. It's strongly recommended that you create and work from an outline.

This section covers the basic syntax and some rules of thumb for writing.

### Basic syntax
A line in between create a separate paragraph. *This is italicized.* **This is bold.** Here is [a link](/). If you want to display the URL, you can do it like this <http://ri.cmu.edu/>.

> This is a note. Use it to reinforce important points, especially potential show stoppers for your readers. It is also appropriate to use for long quotes from other texts.


#### Bullet points and numbered lists
Here are some hints on writing (in no particular order):
- Focus on application knowledge.
  - Write tutorials to achieve a specific outcome.
  - Relay theory in an intuitive way (especially if you initially struggled).
    - It is likely that others are confused in the same way you were. They will benefit from your perspective.
  - You do not need to be an expert to produce useful content.
  - Document procedures as you learn them. You or others may refine them later.
- Use a professional tone.
  - Be non-partisan.
    - Characterize technology and practices in a way that assists the reader to make intelligent decisions.
    - When in doubt, use the SVOR (Strengths, Vulnerabilities, Opportunities, and Risks) framework.
  - Personal opinions have no place in the Wiki. Do not use "I." Only use "we" when referring to the contributors and editors of the Robotics Knowledgebase. You may "you" when giving instructions in tutorials.
- Use American English (for now).
  - We made add support for other languages in the future.
- The Robotics Knowledgebase is still evolving. We are using Jekyll and GitHub Pages in and a novel way and are always looking for contributors' input.

Entries in the Wiki should follow this format:
1. Excerpt introducing the entry's contents.
  - Be sure to specify if it is a tutorial or an article.
  - Remember that the first 100 words get used else where. A well written excerpt ensures that your entry gets read.
2. The content of your entry.
3. Summary.
4. See Also Links (relevant articles in the Wiki).
5. Further Reading (relevant articles on other sites).
6. References.

#### Code snippets
There's also a lot of support for displaying code. You can do it inline like `this`. You should also use the inline code syntax for `filenames` and `ROS_node_names`.

Larger chunks of code should use this format:
```
def recover_msg(msg):

        // Good coders comment their code for others.

        pw = ProtocolWrapper()

        // Explanation.

        if rec_crc != calc_crc:
            return None
```
This would be a good spot further explain you code snippet. Break it down for the user so they understand what is going on.

#### LaTex Math Support
Here is an example MathJax inline rendering $ \phi(x\|y) $ (note the additional escape for using \|), and here is a block rendering:
$$ \frac{1}{n^{2}} $$

#### Images and Video
Images and embedded video are supported.

![Put a relevant caption here](assets/images/Hk47portrait-298x300.jpg)

{% include video id="8P9geWwi9e0" provider="youtube" %}

{% include video id="148982525" provider="vimeo" %}

The video id can be found at the end of the URL. In this case, the URLs were
`https://www.youtube.com/watch?v=8P9geWwi9e0`
& `https://vimeo.com/148982525`.

## Summary
Use this space to reinforce key points and to suggest next steps for your readers.

## See Also:
- Links to relevant material within the Robotics Knowledgebase go here.

## Further Reading
- Links to articles of interest outside the Wiki (that are not references) go here.

## References
- Links to References go here.
- References should be in alphabetical order.
- References should follow IEEE format.
- If you are referencing experimental results, include it in your published report and link to it here.
