<!DOCTYPE html><html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Online Classes Portal</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f9f9f9; }
        header, footer { background: #2c3e50; color: white; padding: 1em; text-align: center; }
        nav { background: #34495e; padding: 1em; text-align: center; }
        nav a { color: white; margin: 0 15px; text-decoration: none; }
        .container { padding: 2em; }
        section { margin-bottom: 2em; }
        .card { background: white; padding: 1em; border-radius: 5px; box-shadow: 0 0 10px rgba(0,0,0,0.1); }
        .btn { background: #3498db; color: white; padding: 10px 20px; border: none; border-radius: 4px; cursor: pointer; }
        input, textarea { width: 100%; padding: 0.5em; margin: 0.5em 0; }
        iframe { width: 100%; height: 300px; border: none; margin-top: 10px; }
    </style>
</head>
<body>
    <header>
        <h1>Online Classes Portal</h1>
        <p>All your learning in one place</p>
    </header><nav>
    <a href="#signin">Sign In</a>
    <a href="#timetable">Time Table</a>
    <a href="#recorded">Recorded Classes</a>
    <a href="#schedule">Faculty Schedule</a>
    <a href="#feedback">Feedback</a>
</nav>

<div class="container">
    <section id="signin" class="card">
        <h2>Sign In</h2>
        <form>
            <input type="email" placeholder="Email" required>
            <input type="password" placeholder="Password" required>
            <button type="submit" class="btn">Login</button>
        </form>
    </section>

    <section id="timetable" class="card">
        <h2>Class Time Table</h2>
        <p>Download or view the current class schedule:</p>
        <iframe src="timetable.pdf"></iframe>
    </section>

    <section id="recorded" class="card">
        <h2>Recorded Classes</h2>
        <ul>
            <li><a href="#">HTML Basics - Watch</a></li>
            <li><a href="#">CSS Layouts - Watch</a></li>
            <li><a href="#">JavaScript Intro - Watch</a></li>
        </ul>
    </section>

    <section id="schedule" class="card">
        <h2>Faculty Class Schedule</h2>
        <p>See when faculty are teaching or available:</p>
        <iframe src="faculty-schedule.pdf"></iframe>
    </section>

    <section id="feedback" class="card">
        <h2>Feedback Form</h2>
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Feedback" rows="4" required></textarea>
            <button type="submit" class="btn">Submit Feedback</button>
        </form>
    </section>
</div>

<footer>
    <p>&copy; 2025 Online Classes Portal. All rights reserved.</p>
</footer>

</body>
</html>
