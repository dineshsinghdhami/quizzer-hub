<!DOCTYPE html>

<html lang="en">


<h1>🎓 Quizzer</h1>
<p><em>A web-based quiz application built with Flask and Python to test knowledge with multiple-choice quizzes and email OTP authentication.</em></p>

<h2>📌 Table of Contents</h2>
<ul>
    <li><a href="#features">Features</a></li>
    <li><a href="#project-structure">Project Structure</a></li>
    <li><a href="#quick-start">Quick Start</a></li>
    <li><a href="#security-features">Security Features</a></li>
    <li><a href="#browser-compatibility">Browser Compatibility</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#support">Support</a></li>
</ul>

<h2 id="features">✨ Features</h2>
<ul>
    <li>🔒 <strong>Email OTP Verification</strong>: Secure login using one-time passwords sent via email</li>
    <li>🎯 <strong>Multiple-Choice Quizzes</strong>: Test knowledge instantly</li>
    <li>📊 <strong>Real-Time Scoring</strong>: Scores calculated as you finish each quiz</li>
    <li>📋 <strong>User Registration & Login</strong>: Personalized experience</li>
    <li>📱 <strong>Responsive Design</strong>: Works on desktop, tablet, and mobile</li>
</ul>

<h2 id="project-structure">📂 Project Structure</h2>
<pre>
quizzer/
│
├── app.py               # Main Flask app
├── templates/           # HTML templates
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   └── quiz.html
├── static/              # CSS, JS, images
│   ├── style.css
│   └── script.js
├── requirements.txt     # Python dependencies
├── README.html          # Project README
└── .gitignore
</pre>

<h2 id="quick-start">🚀 Quick Start</h2>
<ol>
    <li>📥 <strong>Clone the repository</strong>:
        <pre>git clone https://github.com/yourusername/quizzer.git
cd quizzer</pre>
    </li>
    <li>🌐 <strong>Set up virtual environment and install dependencies</strong>:
        <pre>python -m venv venv
venv\Scripts\activate  # Windows
source venv/bin/activate # macOS/Linux
pip install -r requirements.txt</pre>
    </li>
    <li>🎯 <strong>Run the app</strong>:
        <pre>python app.py</pre>
        Open <code>http://127.0.0.1:5000/</code> in your browser
    </li>
</ol>

<h2 id="security-features">🛡️ Security Features</h2>
<ul>
    <li>🔐 OTP ensures secure login</li>
    <li>💾 No user passwords stored in plaintext</li>
</ul>

<h2 id="browser-compatibility">🌐 Browser Compatibility</h2>
<ul>
    <li>✅ Chrome</li>
    <li>✅ Firefox</li>
    <li>✅ Safari</li>
    <li>✅ Edge</li>
</ul>

<h2 id="contributing">🤝 Contributing</h2>
<p>We welcome contributions! Please see <a href="CONTRIBUTING.md">CONTRIBUTING.md</a> for guidelines.</p>

<h2 id="license">📄 License</h2>
<p>This project is licensed under the CUSTOM License - see the <a href="https://github.com/thecodingdhami/quizzer/blob/main/LICENSE.md">LICENSE</a> file for details.</p>

<h2 id="support">📞 Support</h2>
<ul>
    <li>🐛 <strong>Bug Reports:</strong> <a href="https://github.com/thecodingdhami/quizzer/issues">Open an issue</a></li>
    <li>💡 <strong>Feature Requests:</strong> <a href="https://github.com/thecodingdhami/quizzer/discussions">Start a discussion</a></li>
</ul>

<hr>
<p>⭐ <strong>Like this project? Give it a star!</strong> ⭐</p>

</body>
</html>
