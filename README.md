# Portfolio

I am an iOS Developer with over 5 years of experience, specializing in iOS frameworks and technologies. I have extensively worked with Swift and Objective-C.

---

<p align='left'>
    <img src='https://img.icons8.com/color/344/swift.png' alt="Swift" width="40" height="40">
    <img src='https://img.icons8.com/color/344/swiftui.png' alt="SwiftUI" width="40" height="40">
    <img src='https://img.icons8.com/external-tal-revivo-bold-tal-revivo/344/external-apple-inc-logotype-of-an-american-multinational-technology-company-logo-bold-tal-revivo.png' alt="Apple" width="40" height="40">
    <img src='https://img.icons8.com/color/344/python--v1.png' alt="Python" width="40" height="40">
</p>

---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ajay Dhandhukiya - CV</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
        }
        h1, h2 {
            margin: 0;
        }
        h1 {
            margin-bottom: 0px; /* Adjust the value to decrease the space */
        }
        .section {
            margin-bottom: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
            overflow: hidden;
        }
        .section-title {
            cursor: pointer;
            background-color: #f4f4f4;
            padding: 10px;
            border-bottom: 1px solid #ccc;
        }
        .section-content {
            display: none;
            padding: 10px;
        }
        h3 {
            color: #333;
            cursor: pointer;
            margin: 0;
            padding: 10px;
            background-color: #f4f4f4;
            border-bottom: 1px solid #ccc;
        }
        .skills {
            display: flex;
            flex-direction: column;
        }
        .skills > div {
            margin-bottom: 10px;
        }
        ul {
            list-style-type: disc;
            padding-left: 20px;
        }
    </style>
</head>
<body>

    <h1>Ajay Dhandhukiya</h1>
    <h2>Senior iOS Developer</h2>

    <div class="section">
        <div class="section-title" onclick="toggleSection('about-me')">
            <h2>About Me</h2>
        </div>
        <div class="section-content" id="about-me">
            <p>
                I am a passionate and results-driven iOS developer with experience in the world of mobile app development.
                My journey in the iOS ecosystem has been marked by a deep commitment to crafting exceptional user experiences
                and pushing the boundaries of what's possible with Apple's cutting-edge technologies.
            </p>
        </div>
    </div>

    <div class="section">
        <div class="section-title" onclick="toggleSection('skills')">
            <h2>Skills</h2>
        </div>
        <div class="section-content" id="skills">
            <div>
                <h3 onclick="toggleSection('hard-skills')">Hard Skills</h3>
                <div class="section-content" id="hard-skills">
                    <p><strong>Languages:</strong> Swift, Objective-C</p>
                    <p><strong>Frameworks:</strong> UIKit, CoreData, CoreAnimation, CoreGraphics, SwiftUI</p>
                    <p><strong>Tools:</strong> Xcode, Interface Builder, Git, CocoaPods, Carthage</p>
                    <p><strong>API Integration:</strong> RESTful services, JSON parsing, Alamofire</p>
                </div>
            </div>
            <div>
                <h3 onclick="toggleSection('soft-skills')">Soft Skills</h3>
                <div class="section-content" id="soft-skills">
                    <p>Observation</p>
                    <p>Decision making</p>
                    <p>Communication</p>
                    <p>Multi-tasking</p>
                </div>
            </div>
        </div>
    </div>

    <div class="section">
        <div class="section-title" onclick="toggleSection('professional-experience')">
            <h2>Professional Experience</h2>
        </div>
        <div class="section-content" id="professional-experience">
            <div>
                <h3 onclick="toggleSection('justcode')">JustCode Software Development (2021 – Present)</h3>
                <div class="section-content" id="justcode">
                    <ul>
                        <li>Application Development</li>
                        <li>Architecture and Design</li>
                        <li>Code Review and Mentorship</li>
                        <li>Problem Solving</li>
                        <li>Performance Optimization</li>
                        <li>Team Collaboration</li>
                        <li>Technical Leadership</li>
                        <li>Version Control and Deployment</li>
                        <li>Code Documentation</li>
                        <li>Project Management</li>
                        <li>Security and Data Privacy</li>
                        <li>Continuous Learning</li>
                    </ul>
                </div>
            </div>
            <div>
                <h3 onclick="toggleSection('daemon')">Daemon Information System (2017 – 2021)</h3>
                <div class="section-content" id="daemon">
                    <ul>
                        <li>App Development</li>
                        <li>Programming</li>
                        <li>UI/UX Design</li>
                        <li>Bug Fixing and Debugging</li>
                        <li>API Integration</li>
                    </ul>
                </div>
            </div>
        </div>
    </div>

    <div class="section">
        <div class="section-title" onclick="toggleSection('projects')">
            <h2>Projects</h2>
        </div>
        <div class="section-content" id="projects">
            <ul>
                <li><strong>DaeBuild CRM:</strong> CRM of construction Builder</li>
                <li><strong>Islamic Cal:</strong> Utility app for islam</li>
                <li><strong>Selfume:</strong> Social media app with text, audio and video</li>
                <li><strong>HCT:</strong> Finance and Utility</li>
                <li><strong>Fitness Tarantula:</strong> Health & Fitness</li>
                <li><strong>JERA-DCM:</strong> Disaster Counter Management app for JERA Powerplant</li>
            </ul>
        </div>
    </div>

    <div class="section">
        <div class="section-title" onclick="toggleSection('education-background')">
            <h2>Education Background</h2>
        </div>
        <div class="section-content" id="education-background">
            <div>
                <h3>Gujarat Technological University</h3>
                <p>Bachelor in Engineering (Information Technology)</p>
                <p>Completed in 2017</p>
            </div>
            <div>
                <h3>Board Vishva Vidhyapith, Rajkot</h3>
                <p>HSC in Science</p>
                <p>Completed in 2013</p>
            </div>
        </div>
    </div>

    <script>
        function toggleSection(sectionId) {
            const section = document.getElementById(sectionId);
            if (section.style.display === 'none' || section.style.display === '') {
                section.style.display = 'block';
            } else {
                section.style.display = 'none';
            }
        }
    </script>

</body>
</html>