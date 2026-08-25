<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BGDCF Organizational Development Academy</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <header>
        <h1>BGDCF Academy</h1>
        <p>Organizational Development Training</p>
    </header>

    <main>
        <section>
            <h2>Welcome</h2>
            <p>
                Welcome to the BGDCF Organizational Development Academy.
                This learning site supports NGOs, CSOs, community organizations,
                and development practitioners with practical training in organizational development.
            </p>
        </section>

        <section>
            <h2>Course Modules</h2>
            <p>Choose a learning path below. All courses are listed here first, then each course includes its own
                question set and short quiz.</p>

            <div class="course-grid">
                <button class="course-card" onclick="location.href='lessons/dashboard.html'">👤 Learner
                    Dashboard</button>
                <button class="course-card" onclick="location.href='lessons/lesson1.html'">Lesson 1: What is
                    Organizational Development?</button>
                <button class="course-card" onclick="location.href='lessons/lesson2.html'">Lesson 2: Why Organizational
                    Development Matters</button>
                <button class="course-card" onclick="location.href='lessons/lesson3.html'">Lesson 3: Organizational
                    Structure</button>
                <button class="course-card" onclick="location.href='lessons/lesson4.html'">Lesson 4: Organizational
                    Capacity</button>
                <button class="course-card" onclick="location.href='lessons/lesson5.html'">Lesson 5: Characteristics of
                    a Strong Organization</button>
                <button class="course-card" onclick="location.href='lessons/strategic-planning.html'">Strategic
                    Planning</button>
                <button class="course-card" onclick="location.href='lessons/leadership-governance.html'">Leadership
                    &amp; Governance</button>
                <button class="course-card" onclick="location.href='lessons/financial-management.html'">Financial
                    Management</button>
                <button class="course-card" onclick="location.href='lessons/project-management.html'">Project
                    Management</button>
                <button class="course-card" onclick="location.href='lessons/monitoring-evaluation.html'">Monitoring
                    &amp; Evaluation</button>
            </div>

            <h3>All Courses in This Academy</h3>
            <ul class="course-list">
                <li>Organizational Development Foundations</li>
                <li>Strategic Planning</li>
                <li>Leadership &amp; Governance</li>
                <li>Financial Management</li>
                <li>Project Management</li>
                <li>Monitoring &amp; Evaluation</li>
            </ul>

            <button onclick="location.href='lessons/quiz.html'">📝 Final Quiz</button>
        </section>

        <section class="registration-box">
            <h2>Learner Registration</h2>
            <input type="text" id="learnerNameInput" placeholder="Enter your name">
            <button onclick="saveLearnerName()">Save My Name</button>
            <p id="nameMessage"></p>
        </section>
    </main>

    <footer>
        <p>© 2026 BGDCF</p>
    </footer>

    <script src="app.js"></script>
</body>

</html>
