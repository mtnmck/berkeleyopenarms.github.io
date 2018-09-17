---
layout: default
---

This is Blue, a dexterous back-drivable low-cost 7-dof robot manipulator. This website is a companion to our paper (submitted to ICRA/RA-L 2019) and is intended to provide more detail into the technical capabilities of the robot and the metrics we used to characterize its performance.

<!-- [Link to the paper:](<iframe src="https://drive.google.com/file/d/1IIJE8LaXqsBkqYoe7xZxhNppKoo9f9eV/preview" width="640" height="480"></iframe>). -->

<iframe src="https://drive.google.com/file/d/1IIJE8LaXqsBkqYoe7xZxhNppKoo9f9eV/preview" width="640" height="480"></iframe>


---

<!-- # Summary
{: #summary }
<iframe src="https://www.youtube.com/embed/G4QQ8Mfjb_g" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
Quick highlight reel for Blue!
-->

# Lead-through
{: #leadthrough }

<iframe width="560" height="315" src="https://www.youtube.com/embed/S5guqiHGjSE?rel=0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

Here we record a set of joint states while a human guides the robot through an arbitrary set of motions. We then replay the recording and demonstrate the back-drivability of the arm by apply external force (through a second human).

# VR Demos
{: #vrdemos }

A Virtual Reality system was developed using the HTC Vive and interfaced with our robot over ethernet. We developed an inverse dynamics solver that translates the 6-DoF controller pose to a 7-DoF robot pose that prioritizes 'elbows out'.
We found two-armed teleoperation to be extremely difficult to coordinate.

## Coffee & Cleaning
{: #espresso }
<iframe width="560" height="315" src="https://www.youtube.com/embed/gMbaLvTCDYo?rel=0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
Our operator demonstrates the ability to make coffee using the telepresense system. This is a difficult task for a robot to accomplish becauise there are small targets (such as the 'on' button), deformable objects (such as the paper cup), fine movements (loading the machine), and liquids (pouring the coffee). The robot spills a little in the process and then shows its ability to clean up a mess afterwards.

<!-- ## VR Teleoperation
{: #vr }
<iframe src="https://www.youtube.com/embed/G4QQ8Mfjb_g" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
-->


## Screw Pick and Place
{: #pickandplace }
<iframe width="560" height="315" src="https://www.youtube.com/embed/M-6HgR2gT_I?rel=0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

This video demonstrates the accuracy and stability of the system while operated remotely. Here we pick screws off a flat surface and place them into a storage container. The screws are M5 cap heads (5mm in diameter, 20mm long).

## Payload Demonstration
{: #payload }
<iframe src="https://drive.google.com/file/d/1UxRmDHHIO3JF8z4g471OeV1izaAI5V2I/preview" width="640" height="480"></iframe>
Blue has the ability to hold over 2kg at arms-length. Closer to its body, the robot's payload increases. Note (at the end of the video) when the robot drops the 5lb weight on the the hand of the robot!

# Repeatability Tests
{: #repeatability }

<iframe width="560" height="315" src="https://www.youtube.com/embed/Y4ltW0phI20?rel=0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

This test shows the accuracy of our system in returning to a given home position from a set of eight end poses. The home pose repeatability is within a 4mm radius. The end-pose repeatability is within 3mm.

# Step Response
{: #stepresponse }

<iframe width="560" height="315" src="https://www.youtube.com/embed/SeSDWsjHMtk?rel=0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

We apply an immediate position offset and observe a quick, smooth transition.

# Position Bandwidth
{: #positionbandwidth }

<iframe width="560" height="315" src="https://www.youtube.com/embed/7U2GJyjpbi4?rel=0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/XqewGmuDq2E?rel=0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/sodNIZs1Zpo?rel=0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/gO6OIa-8Rqk?rel=0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

<iframe width="560" height="315" src="https://www.youtube.com/embed/XOwPUNmwlpQ?rel=0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

A single link is stably mounted and oriented vertically. A rod with a mass is attached at fixed radii to create pre-determined inertias. A chirp signal is then run to oscillate the arm over the frequency range of 0.1 to 40Hz.

# Torque Bandwidth
{: #torquebandwidth }

<iframe width="560" height="315" src="https://www.youtube.com/embed/x70Ds4cHSCw?rel=0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

A single upper link is locked down and connected to an output bar with load cells on either end. Similar to the position bandwidth, a chirp signal is then commanded through each motor to cause alternate rotations from 0.1 to 40Hz.


