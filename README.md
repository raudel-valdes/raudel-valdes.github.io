<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Raudel Valdes - Software Engineer</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #272727;
            color: #fff;
        }
        header {
            background-color: #1a1a1a; /* Darker header background color */
            color: #fff;
            text-align: center;
            padding: 2em;
        }
        header img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            object-fit: cover;
            margin-bottom: 1em;
        }
        section {
            max-width: 800px;
            margin: 2em auto;
            padding: 1em;
            background-color: #1a1a1a; /* Darker section background color */
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
    </style>
    <script>
        function calculateJobDuration(startDate) {
            let start = new Date(startDate);
            let now = new Date();
            let years = now.getFullYear() - start.getFullYear();
            let months = now.getMonth() - start.getMonth();
            if (months < 0) {
                years--;
                months += 12;
            }
            return `${years} year${years !== 1 ? 's' : ''} ${months} month${months !== 1 ? 's' : ''}`;
        }
        
        function updateJobDuration() {
            document.getElementById("job-duration").innerText = `Sep 2022 - Present (${calculateJobDuration('2022-09-01')})`;
        }
        
        window.onload = updateJobDuration;
    </script>
</head>
<body>
    <header>
        <img src="https://media.licdn.com/dms/image/C4E03AQGN_89WzlqB4Q/profile-displayphoto-shrink_400_400/0/1599837504183?e=1704931200&v=beta&t=f0U5cZe5yKR5U47x-dJerfiBsz3VtNHz7S9ivvV8YQk" alt="Profile Picture">
        <h1>Raudel Valdes</h1>
        <p>Experienced Software Engineer</p>
    </header>
    <section>
        <h2>About Me</h2>
        <p>
            Hello! I am an experienced software engineer with a demonstrated history of helping businesses thrive
            through leveraging modern software solutions. I specialize in full-stack mobile and web development,
            emphasizing security and reliability in my work. My journey in the tech world began with a Bachelor of
            Science in Computer Engineering from the University of Louisville.
        </p>
    </section>
    <section>
        <h2>Experience</h2>
        <div>
            <h3>Software Engineer at SentriLock</h3>
            <p id="job-duration"></p>
            <ul>
                <li>Developed full-stack mobile and web applications using Flutter/Dart, Native Android, Angular, Node.js, SQL, TDD, GCP, and Cloud Firestore.</li>
                <li>Specialized in Flutter/Dart development of Geofencing and Bluetooth Low Energy (BLE) for time-sensitive operations.</li>
                <li>Implemented and maintained TDD and Continuous Development (CI / CD) pipelines for software releases.</li>
                <li>Developed and maintained microservices for loosely decoupling service dependencies.</li>
            </ul>
            <p>Notable Apps: SentriConnect, SentriKey Access, SentriKey Real Estate</p>
        </div>
        <div>
            <h3>Computer Engineer at GE Appliances</h3>
            <p>Aug 2021 - Sep 2022 (1 year 2 months)</p>
            <ul>
                <li>Leveraged IoT to build modern solutions for repetitive home tasks through smart appliances.</li>
                <li>Developed and maintained mobile applications in native iOS and Android using Swift and Java/Kotlin.</li>
                <li>Rotated through different departments, presenting successful projects to top executives.</li>
                <li>Worked on GE Profile Wall Ovens, using Android OS and developing Flutter apps for use via the integrated
                    LCD screen.</li>
            </ul>
        </div>
        <div>
            <h3>Application Developer at UPS</h3>
            <p>Jan 2020 - Aug 2021 (1 year 8 months)</p>
            <ul>
                <li>Part of an agile software development team providing applications to improve efficiency across 12 UPS
                    hubs worldwide.</li>
                <li>Focused on developing Angular front-end features and ASP.NET Core back-end functionality.</li>
                <li>Deployed through OpenShift and Jenkins pipelines for various APIs, offering 24/7 support for zero
                    downtime of legacy and replacement systems.</li>
            </ul>
        </div>
    </section>
    <section>
        <h2>Education</h2>
        <p>
            <strong>University of Louisville - Speed School</strong><br>
            Bachelor of Science - BS, Computer Engineering (2015 - 2020)
        </p>
    </section>
    <section>
        <h2>Skills</h2>
        <ul>
            <li>Programming Languages: JavaScript, Dart, Kotlin, C, C++, Object-Oriented Programming (OOP)</li>
            <li>Development Practices: Test-Driven Development (TDD), Integration and Continuous Delivery (CI/CD)</li>
            <li>Web Technologies: Node.js, Angular</li>
            <li>Mobile Development: Flutter, Android</li>
            <li>Cloud Platform: Google Cloud Platform (GCP)</li>
            <li>Team Leadership</li>
            <li>Mentorship</li>
        </ul>
    </section>
    <footer>
        <p>&copy; 2023 Raudel Valdes. All
