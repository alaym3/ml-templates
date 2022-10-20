# Things to remember about viz

## 1. sdw

### steps
1. understand the context
2. choose an appropriate display
3. eliminate clutter
4. focus attention where you want it
5. think like a designer
6. tell a story

### case study tips summary
- white backgrounds are easier
- leverage animation in presentations (e.g. starting from beginning, adding more lines to the graph as time goes on, etc... so people don't look ahead)
     - the final, annotated graph, can be used in email distributions, etc.
- group categories together by color blocks (e.g. satisfied = blues, unsatisfied = greys)
- think of how our eyes go in z shape
- sphagetti line graph tips:
    - pull the lines apart vertically (such as sparklines for each) if seeing trend for each category alone is more important than comparing values across categories
- pie alternatives
    - horizontal stacked to 100%
    - slopegraph

### Tips from swd - more examples
- title should be top left,  y axis label should be top left, x axis label should be bottom left (reduce eye movement)
- grey titles, axis labels, etc
- eye movement: 
    - top left of page, then right, then bottom left, then right (z shape)
    - key info should go top left
- who is the audience?
- what is the goal of your viz?
- simple is better
- keep as little elements as possible
- if you just need to show 1 or 2 numbers, just show them and not the graph
- add relevant context 
- stacked bars are very difficult to display trends overtime
- hbars are easiest for readers
- diagonal labels are hard to read
- ppl read things in a "z" format
- contrast: if there is something that needs to stand out, make it different than the rest, instead of making EVERYTHING different
- clutter
   - remove chart borders
   - gridlines are not always necessary
   - label data directly rather than using legends, sometimes: esp for lines comparing 2 things
   - use data labels sparingly to help draw attention
- memory
    - ppl can keep 4 chunks of data in short term memory - so don't make graphs with tons of different options and shapes and colors
        - solution: label them directly. form larger chunks of info
    - changing color intensity of things we want to stand out will make audience see what we want them to see before we even tell them anything
- preattentive attributes: what ppl notice immediately, and can create a visual heirarchy of info
    - orientation
    - shape
    - length
    - width
    - size
    - curvature
    - added marks
    - enclosure
    - color
    - intensity
    - position
    - motion
- use preattentive attributes to make heirarchies
    - color bars into 2 buckets
    - make text with the color of the buckets you want to highlight
- color
   - MUST BE USED SPARINGLY to be strategic and highlight the important pieces
   - must be sufficient contract to be effective
   - Cole uses grey as standard, and blue to call out important things
   - remember the preattentive attributes - we will try to view everything separately and get distracted. a better alternative is to use a continuous colorscale of a single color (which is what I typically do!)
   - be thoughtful of the **tone** the color conveys
- colorblind
   - red/green should not go together
        - blue for pos, orange for neg, is an alternative
- highlighting content
    - only 10% of info should be highlighted
    - bookmark on the guidelines - size, color, case, boldness
- remove distractions and declutter
    - when detail isn't needed, summarize/group
    - push non-message-impacting items to the background
    - ask yourself if removing the piece would change anything. if no, remove.
- accessibility
    - legible
    - clean
    - straightforward language
    - remove unecessary complexity
- annotation
   - use text to highlight key areas, explain nuance, etc.
- aesthetics/pretty graphs
   - people think prettier graphs are easier to use and like them more
   - be smart with color
   - keep things aligned nicely
   - leverage white spaces
- dark grey is good for the graph titles and axis labels because it has less contrast than black on white
   - black bars/text/line can help emphasize things!
- ways to start the story
     - chronoligically
     - lead with the ending (what you want the audience to do)
- storytelling tips
    - repetition so people remember
    - the main character is the audience
### Quotes from swd:
- If you’re wondering What is the right graph for my situation?, the answer is always the same: whatever will be easiest for your audience to read. There is an easy way to test this, which is to create your visual and show it to a friend or colleague. Have them articulate the following as they process the information: where they focus, what they see, what observations they make, what questions they have. This will help you assess whether your visual is hitting the mark, or in the case where it isn’t, help you know where to concentrate your changes. - Knaflic, Cole Nussbaumer. Storytelling with Data (p. 69). Wiley. Kindle Edition. 
   - **This is the key quote to use for testing/UX design!!**
- You should always want your audience to know or do something. If you can’t concisely articulate that, you should revisit whether you need to communicate in the first place - Knaflic, Cole Nussbaumer. Storytelling with Data (p. 22). Wiley. Kindle Edition. 
- Storyboarding is perhaps the single most important thing you can do up front to ensure the communication you craft is on point. The storyboard establishes a structure for your communication. It is a visual outline of the content you plan to create. - Knaflic, Cole Nussbaumer. Storytelling with Data (p. 31). Wiley. Kindle Edition. 
- Without other visual cues, your audience will typically start at the top left of the page or screen and will move their eyes in a “z” shape (or multiple “z” shapes, depending on the layout) across the page or screen as they take in information. Because of this, when it comes to tables and graphs, I like to upper-left-most justify the text (title, axis titles, legend). This means the audience will hit the details that tell them how to read the table or graph before they get to the data itself. - Knaflic, Cole Nussbaumer. Storytelling with Data (p. 83). Wiley. Kindle Edition. 
- When it comes to the orientation of text, one study (Wigdor & Balakrishnan, 2005) found that the reading of rotated text 45 degrees in either direction was, on average, 52% slower than reading normally oriented text (text rotated 90 degrees in either direction was 205% slower on average). It is best to avoid diagonal elements on the page. - Knaflic, Cole Nussbaumer. Storytelling with Data (p. 84). Wiley. Kindle Edition. 
- **This highlights the importance of the strategic use of contrast in visual design: the more things we make different, the lesser the degree to which any of them stand out... if there is something really important we want our audience to know or see (the hawk), we should make that the one thing that is very different from the rest.** - Knaflic, Cole Nussbaumer. Storytelling with Data (p. 86). Wiley. Kindle Edition. 
- If you think it will be helpful for your audience to trace their finger from the data to the axis, or you feel that your data will be more effectively processed, you can leave the gridlines. But make them thin and use a light color like grey. Do not let them compete visually with your data. When you can, get rid of them altogether: this allows for greater contrast, and your data will stand out more. - Knaflic, Cole Nussbaumer. Storytelling with Data (p. 93). Wiley. Kindle Edition. 
- Remember, we want to try to identify anything that will feel like effort to our audience and take that work upon ourselves as the designers of the information. In this case, we can leverage the Gestalt principle of proximity and put the data labels right next to the data they describe. - Knaflic, Cole Nussbaumer. Storytelling with Data (p. 96). Wiley. Kindle Edition. 
- limitations. Specifically, people can keep about four chunks of visual information in their short-term memory at a given time. This means that if we create a graph with ten different data series that are ten different colors with ten different shapes of data markers and a legend off to the side, we’re making our audience work very hard going back and forth between the legend and the data to decipher what they are looking at.
   - In this specific situation, one solution is to label the various data series directly (reducing that work of going back and forth between the legend and the data by leveraging the Gestalt principle of proximity that we covered in Chapter 3). More generally, we want to form larger, coherent chunks of information so that we can fit them into the finite space in our audience’s working memory. - Knaflic, Cole Nussbaumer. Storytelling with Data (pp. 101-102). Wiley. Kindle Edition. 
- The preattentive attribute of intensity of color, in this case, makes the 3s the one thing that stands out as distinct from the rest. Our brain is quick to pick up on this without our having to dedicate any conscious thought to it. This is remarkable. And profoundly powerful. It means that, if we use preattentive attributes strategically, they can help us enable our audience to see what we want them to see before they even know they’re seeing it! -Knaflic, Cole Nussbaumer. Storytelling with Data (p. 104). Wiley. Kindle Edition. 
- When used sparingly, preattentive attributes can be extremely useful for doing two things: (1) drawing your audience’s attention quickly to where you want them to look, and (2) creating a visual hierarchy of information. - Knaflic, Cole Nussbaumer. Storytelling with Data (pp. 105-106). Wiley. Kindle Edition. 
- Leveraging preattentive attributes to create a clear visual hierarchy of information establishes implicit instructions for your audience, indicating to them how to process the information. We can signal what is most important that they should pay attention to first, what is second most important that they should pay attention to next, and so on. We can push necessary but non-message-impacting components to the background so they don’t compete for attention. - Knaflic, Cole Nussbaumer. Storytelling with Data (p. 109). Wiley. Kindle Edition. 
- Especially in live presentation settings, repeated iterations of the same visual, with different pieces emphasized to tell different stories or different aspects of the same story (as demonstrated in Figures 4.7, 4.8, and 4.9), can be an effective strategy. This allows you to familiarize your audience with your data and visual first and then continue to leverage it in the manner illustrated. - Knaflic, Cole Nussbaumer. Storytelling with Data (pp. 111-112). Wiley. Kindle Edition. 
- When you’re doing exploratory analysis, you should mostly avoid the use of preattentive attributes for this reason. When it comes to explanatory analysis, however, you should have a specific story you are communicating to your audience. Leverage preattentive attributes to help make that story visually clear. - Knaflic, Cole Nussbaumer. Storytelling with Data (p. 112). Wiley. Kindle Edition. 
- When used sparingly, color is one of the most powerful tools you have for drawing your audience’s attention. Resist the urge to use color for the sake of being colorful; instead, leverage color selectively as a strategic tool to highlight the important parts of your visual. The use of color should always be an intentional decision. Never let your tool make this important decision for you! - Knaflic, Cole Nussbaumer. Storytelling with Data (p. 117). Wiley. Kindle Edition. 
- When it comes to the use of color, there are several specific lessons to know: use it sparingly, use it consistently, design with the colorblind in mind, be thoughtful of the tone color conveys, and consider whether to leverage brand colors. - Knaflic, Cole Nussbaumer. Storytelling with Data (p. 117). Wiley. Kindle Edition. 
- Note that our perception is more limited when it comes to relative saturation, but one benefit we get is that it does carry with it some quantitative assumptions (that more heavily saturated represents greater value than less or vice versa—something you don’t get with the rainbow colors used originally as categorical differentiators). This works well for our purpose here, where the low numbers (market leaders) are denoted with the highest color saturation. We are drawn to the dark blue first—the market leaders. This is a more thoughtful use of color. - Knaflic, Cole Nussbaumer. Storytelling with Data (p. 119). Wiley. Kindle Edition. 
- There is an easy test for determining whether preattentive attributes are being used effectively. Create your visual, then close your eyes or look away for a moment and then look back at it, taking note of where your eyes are drawn first. Do they immediately land where you want your audience to focus? Better yet, seek the help of a friend or colleague—ask them to talk you through how they process the visual: where their eyes go first, where they go next, and so on. This is a great way to see things through your audience’s eyes and confirm whether the visual you’ve created is drawing attention and creating a visual hierarchy of information in the way that you desire. - Knaflic, Cole Nussbaumer. Storytelling with Data (p. 120). Wiley. Kindle Edition. 
- Without other visual cues, most members of your audience will start at the top left of your visual or slide and scan with their eyes in zigzag motions across the screen or page. They see the top of the page first, which makes this precious real estate. Think about putting the most important thing here - Knaflic, Cole Nussbaumer. Storytelling with Data (pp. 124-125). Wiley. Kindle Edition. 
- Thoughtful use of text helps ensure that your data visualization is accessible. Text plays a number of roles in communicating with data: use it to label, introduce, explain, reinforce, highlight, recommend, and tell a story. - Knaflic, Cole Nussbaumer. Storytelling with Data (p. 141). Wiley. Kindle Edition. 
- Don’t assume that two different people looking at the same data visualization will draw the same conclusion. If there is a conclusion you want your audience to reach, state it in words. Leverage preattentive attributes to make those important words stand out. - Knaflic, Cole Nussbaumer. Storytelling with Data (p. 141). Wiley. Kindle Edition. 
- When it comes to communicating with data, is it really necessary to “make it pretty?” The answer is a resounding Yes. People perceive more aesthetic designs as easier to use than less aesthetic designs—whether they actually are or not. Studies have shown that more aesthetic designs are not only perceived as easier to use, but also more readily accepted and used over time, promote creative thinking and problem solving, and foster positive relationships, making people more tolerant of problems with designs. - Knaflic, Cole Nussbaumer. Storytelling with Data (p. 145). Wiley. Kindle Edition. 
- Another way to think about the imbalance-balance-solution in your communication is to frame it in terms of the problem and your recommended solution. If you find yourself thinking, But I don’t have a problem!—you may want to reconsider. As we’ve discussed, conflict and dramatic tension are critical components of a story. A story where everything is rosy and is expected to continue to be is not so interesting, attention-grabbing, or action-inspiring. Think of conflict and tension—between the imbalance and balance, or in terms of the problem on which you are focusing—as the storytelling tools that will help you to engage your audience. Frame your story in terms of their (your audience’s) problem so that they immediately have a stake in the solution. - Knaflic, Cole Nussbaumer. Storytelling with Data (pp. 172-173). Wiley. Kindle Edition. 
- The main character in every story we tell should be the same: our audience. It is by making our audience the protagonist that we can ensure the story is about them, not about us. By making the data we want to show relevant to our audience, it becomes a pivotal point in our story. No longer will you just show data. Rather, you will tell a story with data. - Knaflic, Cole Nussbaumer. Storytelling with Data (p. 185). Wiley. Kindle Edition. 
## 2. ????????

