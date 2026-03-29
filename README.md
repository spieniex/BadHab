<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>BadHab</title>

<style>
body{
    margin:0;
    font-family:Arial, sans-serif;
    background:#0f172a;
    color:white;
}

section{
    padding:60px 20px;
    max-width:1000px;
    margin:auto;
}

h1,h2{
    text-align:center;
}

.hero{
    text-align:center;
    padding:80px 20px;
    background:linear-gradient(135deg,#1e293b,#0f172a);
}

.hero h1{
    font-size:60px;
}

.hero span{
    color:#ff4d4d;
}

.card{
    background:#1e293b;
    padding:20px;
    border-radius:15px;
    margin:15px 0;
}

.grid{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:20px;
}

@media(max-width:700px){
    .grid{
        grid-template-columns:1fr;
    }
}

.authors{
    display:flex;
    gap:20px;
    flex-wrap:wrap;
    justify-content:center;
}

.author{
    background:#1e293b;
    padding:20px;
    border-radius:15px;
    width:300px;
}

button{
    padding:15px 30px;
    border:none;
    border-radius:30px;
    background:#ff4d4d;
    color:white;
    font-size:18px;
    cursor:pointer;
}

button:hover{
    background:#e63b3b;
}
</style>

</head>

<body>

<!-- HERO -->
<section class="hero">
    <h1><span>Bad</span>Hab</h1>
    <p>Break Bad Habits. Build Better You.</p>
    <button>Support Project</button>
</section>

<!-- PROJECT DESCRIPTION -->
<section>
<h2>Project Description</h2>

<div class="card">
<p><strong>BadHab</strong> is a mobile app designed to help teenagers track and reduce bad habits such as phone addiction, procrastination, and unhealthy routines.</p>

<p>Many teens are not aware of how often they repeat harmful behaviors, which affects their mental health and productivity.</p>

<p>This problem is important because habits formed at a young age often continue into adulthood.</p>

<p>Our app is unique because it not only tracks habits but also analyzes mood, detects triggers, and provides advice.</p>
</div>
</section>

<!-- FUNCTIONAL -->
<section>
<h2>Functional Requirements</h2>

<div class="grid">
<div class="card">Track daily bad habits</div>
<div class="card">Mark habits as done/not done</div>
<div class="card">Select mood (good, okay, bad)</div>
<div class="card">Track relapse</div>
<div class="card">Provide advice</div>
<div class="card">Show progress</div>
</div>
</section>

<!-- TECH -->
<section>
<h2>Technical Requirements</h2>

<div class="card">
<p>HTML, CSS, JavaScript</p>
<p>GitHub for version control</p>
<p>GitHub Pages for hosting</p>
<p>Future: database and mobile app development</p>
</div>
</section>

<!-- PROTOTYPE -->
<section>
<h2>Sketches / Prototype</h2>

<div class="card">
<p>Our project started with hand-drawn sketches of the app interface.</p>
<p>We designed screens for habit tracking, mood selection, and advice system.</p>
<p>These sketches helped us visualize the final product.</p>
</div>
</section>

<!-- AUTHORS -->
<section>
<h2>About the Authors</h2>

<div class="authors">

<div class="author">
<h3>Dinmukhamed</h3>
<p><strong>Programmer, Researcher</strong></p>
<p>15 years old. Loves video games and helped with coding and publishing the project.</p>
</div>

<div class="author">
<h3>Yerassyl</h3>
<p><strong>Programmer, Designer</strong></p>
<p>15-year-old team member. His drawing and sketching helped create early designs. His research and brainstorming skills helped develop the idea of solving bad habits in teenagers.</p>
</div>

</div>
</section>

<!-- EXTRA -->
<section>
<h2>Additional Information</h2>

<div class="card">
<p><strong>Timeline:</strong></p>
<p>Week 1 – Idea & Research</p>
<p>Week 2 – Design</p>
<p>Week 3 – Development</p>
<p>Week 4 – Testing</p>

<br>

<p><strong>Future Improvements:</strong></p>
<p>Add accounts, statistics, and full mobile app</p>

<br>

<p><strong>Impact:</strong></p>
<p>BadHab helps teenagers improve habits, mental health, and productivity.</p>
</div>

</section>

</body>
</html>
