<h1 align="center"><b>Events</b></h1>

## About

Little project to practice 'Copy and Paste', 'Drag and Drop' and 'Blur' events.

## Learning

What I have learned on each of these events:

<p>COPY and PASTE:</p>
<p>Use the 'DOM' function 'getSelection()', to capture the 'data' that has been copied.</p>
<p>Use the 'event.clipboardData.setData' to transform this 'data' into Uppercase.</p>
<p>Then on the paste area, changed the backgroung color, font color and font weight.</p>

<p>DRAG and DROP:</p>
<p>For the drag and drop activities, I have used 3 events: 'dragstart', 'dragover' and 'drop'</p>
<p>On the 'dragstart' event I used the 'event.dataTransfer.setData' to set the elementId(this.id).</p> 
<p>This way it will be available on the dataTransfer and we can get it on the 'drop' event.</p>
<p>Just before the 'drop' event, I worked on the 'dragover' event, just to apply the 'eventPreventDefault()', so when the draggable element reaches a droppable area, it will be possible to drop it. </p>
<p>Finally, on the 'drop' event, I got the 'ElementId' from the dataTransfer by using 'event.dataTransfer.getData() and applied its value on the dropZone.value fields( Circle, Rectangle and Square)</p>

<p>BLUR:</p>
<p>On the blur event I have used a Regex to verify whether an email typed is valid of not.</p> 
<p>Then set the field background to change for each of these scenarios.</p>

## Languages used

- Html5 (Hypertext)
- Css3 (Cascading Style Sheet)
- Javascript

## Result

<h1 align="center">
    <img src='https://ik.imagekit.io/cnbmdh4b9w/events_rnch-92rR1.gif'>
</h1>

## To clone:

- Access te repository link : https://github.com/Gilmara-Git/Events.git
- Click on 'Code" and 'Download ZIP'
