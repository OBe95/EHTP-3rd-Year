#Django TP
<p><i>
This TP is realized using Django Framework and some AngularJS features to list Available Courses, Professors and Modules with an Advanced search page that allows user to filter courses by Module or Professor.
</i></p>
<p><i>
Database management using by Django Shell
</i></p>

<h2>Initial Pages screen-shots</h2>

<p align="center">
<img src="https://lh3.googleusercontent.com/-ZvgX8E-4cOw/WIPjRTk3xqI/AAAAAAAABZc/pj4Qx2_JzM0CW2yC6KjBE_KEUOy4Txe8gCLcB/h1600/Initial%2B-%2BAll%2Bcourses.png">
<h6 align="center">- Initial "Our Courses" Page -</h6>
</p>

<br>

<p align="center">
<img src="https://lh3.googleusercontent.com/-wGut4n31a04/WIPjX6gS12I/AAAAAAAABZg/Nixa4PuSBVEdx-BYJp75NGKkufHs5yPQACLcB/h1600/Initial%2B-%2BAll%2BModules.png">
<h6 align="center">- Initial "Our Modules" Page -</h6>
</p>

<br>

<p align="center">
<img src="https://lh3.googleusercontent.com/-hi59rC_1eHk/WIPkjoEnazI/AAAAAAAABZw/3Vo2fKmX_iEt4nJaEQHibXDo7r8Ovu4YACLcB/h1600/Initial%2B-%2BAll%2Bprofessors.png">
<h6 align="center">- Initial "Our Professors" Page -</h6>
</p>

<br>

<p align="center">
<img src="https://lh3.googleusercontent.com/-KFhFHJWx25o/WIPjQrsRFqI/AAAAAAAABZY/A3MPAIk_rkszyh0nvUBG10Kx7TtbKADZgCLcB/h1600/Initial%2B-%2BAdvanced%2Bsearch.png">
</p>
<h6 align="center">- "Advanced Search" Page -</h6>

<br>

<h2>Database Management</h2>
<p>
We start the Shell and import our models from "courses.models", our models/classes are Course, Professor and Module.
</p>
<p align="center">
<img src="https://lh3.googleusercontent.com/-aXP0VuasSys/WIPhyMbxCdI/AAAAAAAABZM/-BazR1NQhlcTm2_122fhGlti2MuvZ-UwgCLcB/h1600/Django%2BShell%2Bimport%2Bmodels.png">
</p>
<h6 align="center">- Django shell importing models -</h6>

<br>
<h3>Let's add three professors</h3>
<p align="center">
<img src="https://lh3.googleusercontent.com/-Q2CT-UBwq0M/WIPphWDkGbI/AAAAAAAABaE/ttlK_e7hHuIzJTdA7AqLkITaddLYuoLYwCEw/h1600/Shell%2Badding%2Bprofessors.png">
</p>
<h6 align="center">- Django shell creating and saving Professor objects -</h6>
<p>And the result:</p>
<p align="center">
<img src="https://lh3.googleusercontent.com/-tm570apnXH4/WIPpxsTIsSI/AAAAAAAABaI/qhy0dN9IlqMkiU6kwYje-qePSU4Vdk4TACEw/h1600/Professors%2BAdded.png">
</p>
<h6 align="center">- "Our Professors" Page after the inserts -</h6>

<br>
<h3>Let's add two modules</h3>
<p align="center">
<img src="https://lh3.googleusercontent.com/-DZB7jVm6S7U/WIPtrzmLWpI/AAAAAAAABag/B4Yr8cPZfGMIhZsGjPIA8JEWY-ulRiYMwCLcB/h1600/Shell%2Badding%2Bmodules.png">
</p>
<h6 align="center">- Django shell creating and saving Module objects -</h6>
<p>And the result:</p>
<p align="center">
<img src="https://lh3.googleusercontent.com/-VJE8MdhYzyU/WIPtrxAaeAI/AAAAAAAABaY/Cf6WHEC_ceMZknUu699HZvYU-ilL_KuZACLcB/h1600/Modules%2BAdded.png">
</p>
<h6 align="center">- "Our Modules" Page after the inserts -</h6>

<br>
<h3>Let's add six courses</h3>
<p align="center">
<img src="https://lh3.googleusercontent.com/-eX5axGxn1NI/WIPtrsLJRoI/AAAAAAAABac/8tid-fTfhbgzAx5wDPTqPNjXSvfihFxRgCLcB/h1600/Shell%2Badding%2Bcourses.png">
</p>
<h6 align="center">- Django shell creating Course objects, remember to save all of them -</h6>
<p>And the result:</p>
<p align="center">
<img src="https://lh3.googleusercontent.com/-5fJ-FklxtE4/WIPtrk8GW2I/AAAAAAAABaU/4bFpTw2vSqY6pY5pIlP20tsFAwBhHLaqACLcB/h1600/Courses%2BAdded.png">
</p>
<h6 align="center">- "Our Modules" Page after the inserts -</h6>

<br>

<h2>Advanced search test</h2>
<h3>Filter by Module</p>
<p align="center">
<img src="https://lh3.googleusercontent.com/-mKyhmEzWGYM/WIPxG3A33lI/AAAAAAAABbI/3oPi9y-neDAUdy5MH7RsNP6-daKvuUJXQCLcB/h1600/Filter%2Bby%2Bmodule.png">
<h6 align="center">- Filter by "Java" Module -</h6>
</p>
<p align="center">
<img src="https://lh3.googleusercontent.com/-BgSBWFhIwgc/WIPxGwBfclI/AAAAAAAABbA/-RMxr8gVUbEW8nkNi8vBp5qjZMckFM2ZACLcB/h1600/Filter%2Bby%2Bmodule%2Bresults.png">
<h6 align="center">- Filter by "Java" Module results -</h6>
</p>

<br>

<h3>Filter by Professor</p>
<p align="center">
<img src="https://lh3.googleusercontent.com/-lc5vW-hvZn4/WIPxHMoP-qI/AAAAAAAABbM/IKPdeKkuVCIBlBbGJsFfcY6kSXAiLn1zgCLcB/h1600/Filter%2Bby%2Bprofessor.png">
<h6 align="center">- Filter by Professor "Asma" -</h6>
</p>
<p align="center">
<img src="https://lh3.googleusercontent.com/-4wED5EBIkmY/WIPxGwkyTTI/AAAAAAAABbE/BlQe-BngKIcYOzvOznsy_bYR9XK2GVjdgCLcB/h1600/Filter%2Bby%2Bprofessor%2Bresults.png">
<h6 align="center">- Filter by Professor "Asma" results -</h6>
</p>
