**A-FRAME**

A-Frame was developed to be an easy but powerfule way to develop VR content. It is based on top of HTML, so it's easy to get started. It is an open source framework that is primarily maintained by Mozilla. It has an enitty component framework, Three.js. <br>
It has compatability with most libraries and frameworks. Since it is based on HTML, it is accessible to everyone. Works on desktop and smartphones, in addition to VR headsets. It uses the DOM but its elements don't touch the browser layout. Updates are all done in memory under *requestAnimationFrame* call.
<br> 
A-Frame was built on the notion that it could be compatible with most libraries, frameworks, and tools like React, Three.js, Vue.js, Ember.js, and jQuery. <br>
WebVR is a JavaScript API for creating immersive 3D. This gains access to VR headset sensor data.

A-frame is mostly HTML and Javascript. Simply just enter a script tag in HTML and npm install aframe. <br>
<a href="https://aframe.io/">A-frame.io</a> was beyond helpful in gettng started and understanding it. <a href="https://github.com/donmccurdy/aframe-physics-system#components">Don McCurdy's Github</a> was also what I used to add to my shapes page. <br>
This is a framework of three.js with *entity-componenet-system* (ECS) architecture. This architecture is a common pattern in 3D and game development that follows the composition over inheritancea and hierarchy principle. With ECS, you have greater flexibity when defining objects, promotoes a clean design, most scalable way to build VR applications, and it allows for extending new features. The E in ECS are the entitites; which are container objects where componenets can be attached, they are the base of all objects in the scene. C is for components; which are reusable modules or data containers  that can be attached to entities to provide appearance, behavior, and/or functionality. And lastly, S, which are the systems that provide global scope, mgmt, and services for classes of components. Systems are optional.

I built a very simple example with basic shapes. A-Frame uses a handful of elements like "<a-box>" or "<a-sphere>" called *primitives*.

