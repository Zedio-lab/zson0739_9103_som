# zson0739_9103_som
Quiz 8 – Design Research  
Part 1: Imaging Technique Inspiration  
Inspiration: Interactive Drawing with Mouse (p5.js)   

I am inspired by the interactive drawing technique in p5.js, where shapes follow the mouse and update in real time. This creates a direct connection between user input and visual output. I want to use this technique to generate moving shapes that respond to interaction. This is beneficial because it makes the work more engaging and dynamic, which fits the requirement of creating interactive and responsive visual media.
  

Part 2: Coding Technique Exploration    
Technique: mouseX / mouseY + ellipse()  

In p5.js, mouseX and mouseY track the cursor position in real time. By using these values with functions like ellipse(), shapes can follow the user's movement. This technique allows dynamic positioning and interaction, making visuals responsive. It can help create moving elements or simulate motion-based effects, which supports the interactive goals of my project.

![example](https://happycoding.io/tutorials/processing/images/input-1.gif)

### Example Code

```javascript
function setup() { 
  createCanvas(300, 300);
}

function draw() {
  background(32);
  circle(mouseX, mouseY, 50);
}