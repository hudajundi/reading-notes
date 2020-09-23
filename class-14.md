# Read 14-A
## Transforms
With CSS3 came new ways to position and alter elements. Now general layout techniques can be revisited with alternative ways to size, position, and change elements. All of these new techniques are made possible by the transform property. 
* **2D Transforms**:Elements may be distorted, or transformed, on both a two-dimensional plane or a three-dimensional plane. Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes. Three-dimensional transforms work on both the x and y axes, as well as the z axis. These three-dimensional transforms help define not only the length and width of an element, but also the depth. We’ll start by discussing how to transform elements on a two-dimensional plane, and then work our way into three-dimensional transforms.

* **Combining Transforms**: It is common for multiple transforms to be used at once, rotating and scaling the size of an element at the same time for example. In this event multiple transforms can be combined together. To combine transforms, list the transform values within the transform property one after the other without the use of commas.
* **Transform Origin** :As previously mentioned, the default transform origin is the dead center of an element, both 50% horizontally and 50% vertically. To change this default origin position the transform-origin property may be used.
* **Perspective**: In order for three-dimensional transforms to work the elements need a perspective from which to transform. The perspective for each element can be thought of as a vanishing point, similar to that which can be seen in three-dimensional drawings.
* **3D Transforms** :
Working with two-dimensional transforms we are able to alter elements on the horizontal and vertical axes, however there is another axis along which we can transform elements. Using three-dimensional transforms we can change elements on the z axis, giving us control of depth as well as length and width.
 
## Transitions & Animations
**Transitions**
As mentioned, for a transition to take place, an element must have a change in state, and different styles must be identified for each state. The easiest way for determining styles for different states is by using the :hover, :focus, :active, and :target pseudo-classes. 
* Transitional Property:
The transition-property property determines exactly what properties will be altered in conjunction with the other transitional properties. By default, all of the properties within an element’s different states will be altered upon change. However, only the properties identified within the transition-property value will be affected by any transitions.
* Transition Duration:
The duration in which a transition takes place is set using the transition-duration property. The value of this property can be set using general timing values, including seconds (s) and milliseconds (ms). These timing values may also come in fractional measurements, .2s for example.
* Transition Timing :
The transition-timing-function property is used to set the speed in which a transition will move. Knowing the duration from the transition-duration property a transition can have multiple speeds within a single duration. A few of the more popular keyword values for the transition-timing-function property include linear, ease-in, ease-out, and ease-in-out.
* Shorthand Transitions:
Declaring every transition property individually can become quite intensive, especially with vendor prefixes. Fortunately there is a shorthand property, transition, capable of supporting all of these different properties and values. Using the transition value alone, you can set every transition value in the order of transition-property, transition-duration, transition-timing-function, and lastly transition-delay. Do not use commas with these values unless you are identifying numerous transitions.

## 8 SIMPLE CSS3 TRANSITIONS
1. Fade in
2. color
3. Grow & Shrink
4. Rotate elements
5. Square to circle
6. 3D shadow
7. Swing
8. Inset border


# Read 14-B
## What Google Learned From Its Quest to Build the Perfect Team
Project Aristotle’s researchers began by reviewing a half-century of academic studies looking at how teams worked. Were the best teams made up of people with similar interests? Or did it matter more whether everyone was motivated by the same kinds of rewards? Based on those studies, the researchers scrutinized the composition of groups inside Google: How often did teammates socialize outside the office? Did they have the same hobbies? Were their educational backgrounds similar? Was it better for all teammates to be outgoing or for all of them to be shy? They drew diagrams showing which teams had overlapping memberships and which groups had exceeded their departments’ goals. They studied how long teams stuck together and if gender balance seemed to have an impact on a team’s success.
magine you have been invited to join one of two groups.

Team A is composed of people who are all exceptionally smart and successful. When you watch a video of this group working, you see professionals who wait until a topic arises in which they are expert, and then they speak at length, explaining what the group ought to do. When someone makes a side comment, the speaker stops, reminds everyone of the agenda and pushes the meeting back on track. This team is efficient. There is no idle chitchat or long debates. The meeting ends as scheduled and disbands so everyone can get back to their desks.
