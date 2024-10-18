# Job Portal

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Job Posting Board - README</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
        }
        h1, h2 {
            text-align: center;
        }
        pre {
            background-color: #f4f4f4;
            padding: 10px;
            border: 1px solid #ddd;
            overflow-x: auto;
        }
        code {
            font-family: "Courier New", Courier, monospace;
        }
        a {
            color: #3498db;
        }
    </style>
</head>
<body>

    <h1>Job Posting Board with Email Automation</h1>

    <h2>Overview</h2>
    <p><strong>JobLane</strong> is a full-stack job posting board built using the <strong>MERN</strong> stack (MongoDB, Express.js, React.js, Node.js). This application allows companies to register, verify their accounts via email, post job listings, and automate email notifications to candidates. It aims to simplify the job application process for both employers and job seekers.</p>

    <h2>Demo</h2>
    <p><a href="https://joblane.vercel.app/">Website Demo</a></p>

    <h2>Features</h2>
    <ul>
        <li><strong>User Registration and Verification:</strong> Companies can register and verify their accounts via email.</li>
        <li><strong>Company Login:</strong> Secure login system using JWT for authenticated sessions.</li>
        <li><strong>Job Posting:</strong> Companies can post jobs with detailed descriptions and requirements.</li>
        <li><strong>Candidate Email Automation:</strong> Automated emails to candidates regarding job postings and updates.</li>
        <li><strong>Responsive Design:</strong> User-friendly interface that works well on various devices.</li>
    </ul>

    <h2>Getting Started</h2>
    <h3>Prerequisites</h3>
    <p>Make sure you have <strong>Node.js</strong> installed. You can download it from <a href="https://nodejs.org">nodejs.org</a>.</p>

    <h3>Installation</h3>
    <ol>
        <li>Clone the repository to your local machine:
            <pre><code>git clone https://github.com/abhijha910/Job-Portal-Main.git</code></pre>
        </li>
        <li>Navigate to the <code>client</code> directory (frontend):
            <pre><code>cd client</code></pre>
        </li>
        <li>Install the frontend dependencies:
            <pre><code>npm install</code></pre>
        </li>
        <li>Run the frontend development server:
            <pre><code>npm run dev</code></pre>
        </li>
        <li>Navigate back to the main directory and go to the <code>server</code> directory (backend):
            <pre><code>cd .. && cd server</code></pre>
        </li>
        <li>Install the backend dependencies:
            <pre><code>npm install</code></pre>
        </li>
        <li>Run the backend development server:
            <pre><code>nodemon server.js</code></pre>
        </li>
    </ol>

    <h2>Functional Requirements</h2>
    <ul>
        <li><strong>User Registration:</strong> Companies can register by providing their basic details.</li>
        <li><strong>Email Verification:</strong> Implemented to activate accounts; unverified users cannot post jobs.</li>
        <li><strong>Job Posting:</strong> Authenticated companies can post jobs with:
            <ul>
                <li>Job Title</li>
                <li>Job Description</li>
                <li>Experience Level</li>
                <li>End Date</li>
                <li>Add Candidate Email</li>
            </ul>
        </li>
        <li><strong>Email Automation:</strong> Companies can send job alerts to multiple candidates.</li>
        <li><strong>Logout:</strong> Clear tokens or sessions on logout.</li>
    </ul>

    <h2>Technical Stack</h2>
    <ul>
        <li><strong>Frontend:</strong> React.js, Redux, Tailwind CSS, Material UI</li>
        <li><strong>Backend:</strong> Node.js, Express.js, Nodemailer for email services</li>
        <li><strong>Database:</strong> MongoDB</li>
    </ul>

    <h2>Contribution Guidelines</h2>
    <p>If you wish to contribute to this project, please:</p>
    <ul>
        <li>Read the README thoroughly.</li>
        <li>Familiarize yourself with the project structure and components.</li>
        <li>Report any bugs or issues by raising an issue in the repository.</li>
        <li>Wait for an issue to be assigned before starting development.</li>
        <li>After making changes, submit a pull request for review.</li>
    </ul>

    <h2>License</h2>
    <p>This project is licensed under the MIT License. See the <a href="LICENSE">LICENSE</a> file for details.</p>

    <h2>Acknowledgments</h2>
    <p>Special thanks to the contributors and mentors who supported the development of this project. For UI references, check out the <a href="https://www.figma.com/design/3ru768FzQDG5J6CLC1IPB4/Cuvette-Assignment?node-id=0-1&t=4kRZ1x3vuXhWBiu7-1">Figma Design</a>.</p>

    <h2>Video Explanation</h2>
    <p>A video explaining the working of the app can be found <a href="insert_your_video_link">here</a>.</p>

</body>
</html>
