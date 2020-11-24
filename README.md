# Counting Calories for 9 Days - Sortable Bar Chart

Annie Zhang

Cameron Henritzy

Daniel Augenbaugh

Where we built this project, also the best place to see our code in action: https://observablehq.com/@danaaraug/sortable-bar-chart@286

Example we based our project on: https://observablehq.com/@d3/sortable-bar-chart

---

Notes: The files PaxHeader, caloriesCounted.csv, fd6c17ec40fe27da@286.js, index.html, index.js, inspector.css, package.json, and runtime.js are all necessary to run the code properly in a webserver. This is due to how Observablehq formats projects.

The file "fd6c17ec40fe27da@286.js" is our primary javascript code where the D3 stuff lives.

The file "TeamMapProject2DemoVideo.mp4" is a quick video demonstration of the interactivity/animations of our code running on a webserver.

---

The following is the default Readme content from Observablehq when you download code from their website:

View this notebook in your browser by running a web server in this folder. For
example:

~~~sh
python -m SimpleHTTPServer
~~~

Or, use the [Observable Runtime](https://github.com/observablehq/runtime) to
import this module directly into your application. To npm install:

~~~sh
npm install @observablehq/runtime@4
npm install https://api.observablehq.com/d/fd6c17ec40fe27da.tgz?v=3
~~~

Then, import your notebook and the runtime as:

~~~js
import {Runtime, Inspector} from "@observablehq/runtime";
import define from "@danaaraug/sortable-bar-chart";
~~~

To log the value of the cell named “foo”:

~~~js
const runtime = new Runtime();
const main = runtime.module(define);
main.value("foo").then(value => console.log(value));
~~~
