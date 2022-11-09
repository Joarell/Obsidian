#underthehood/execution 
This stands of `Global Execution Context`. Under the hood on browsers needs to provide an special environment to run JavaScript code. The GEC is responsible to run inside the browsers engine, as V8 on google, JavaScript code in Execution Context. It means all code that's NOT inside of functions gets executed in this moment.

>["For every JavaScript file, there can only be one GEC".](https://www.freecodecamp.org/news/execution-context-how-javascript-works-behind-the-scenes/)