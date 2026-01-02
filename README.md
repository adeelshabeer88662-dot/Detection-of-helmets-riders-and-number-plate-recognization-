<h1> SafeCity Monitor</h1>

<p>
SafeCity Monitor is an AI-powered smart surveillance and violation reporting platform. 
It provides real-time monitoring, incident detection, admin oversight, and data analytics 
for improving road and public safety.
</p>

<hr>

<h2> Key Features</h2>

<ul>
  <li> Real-time surveillance dashboard</li>
  <li> AI-based object & violation detection</li>
  <li> Automated report generation</li>
  <li> Admin analytics & insights</li>
  <li> User authentication (Login / Signup)</li>
  <li> System diagnostics & model checks</li>
</ul>

<hr>

<h2> Project Structure</h2>

<pre>
safecity-monitor/
 ├── backend/            → Python Flask API + AI Models
 │   ├── app.py
 │   ├── models.py
 │   ├── processor.py
 │   ├── diagnostic.py
 │   ├── requirements.txt
 │   └── uploads/
 │
 ├── components/         → Reusable React UI components
 │   ├── DashboardCard.tsx
 │   └── Sidebar.tsx
 │
 ├── pages/              → Application Pages
 │   ├── Dashboard.tsx
 │   ├── Surveillance.tsx
 │   ├── Reports.tsx
 │   ├── AdminOversight.tsx
 │   ├── Settings.tsx
 │   ├── Login.tsx
 │   └── Signup.tsx
 │
 ├── services/           → API & AI integrations
 │   ├── flaskApi.ts
 │   └── geminiService.ts
 │
 ├── App.tsx
 ├── index.tsx
 ├── constants.ts
 ├── package.json
 └── index.html
</pre>

<hr>

<h2> Backend — Installation & Setup</h2>

<h3> Requirements</h3>

<ul>
  <li>Python 3.10+</li>
  <li>Flask</li>
  <li>OpenCV / Torch (for models)</li>
  <li>SQLite DB</li>
</ul>

<h3>Install Dependencies</h3>

<pre>
cd backend
pip install -r requirements.txt
</pre>

<h3> Run Backend Server</h3>

<pre>
python app.py
</pre>

<p>Backend runs by default at:</p>

<pre>http://127.0.0.1:5000</pre>

<hr>

<h2> Frontend — Installation & Setup</h2>

<h3> Requirements</h3>

<ul>
  <li>Node.js</li>
  <li>npm / yarn</li>
  <li>React + TypeScript</li>
</ul>

<h3> Install Dependencies</h3>

<pre>
npm install
</pre>

<h3>Start Development Server</h3>

<pre>
npm start
</pre>

<p>App runs at:</p>

<pre>http://localhost:3000</pre>

<hr>

<h2> AI / Detection Utilities</h2>

<p>The repository also includes tools for:</p>

<ul>
  <li>Model performance benchmarking</li>
  <li>Image & frame diagnostics</li>
  <li>Database validation</li>
</ul>

<pre>
benchmark_inference.py
debug_detect.py
check_models.py
check_image_size.py
check_db.py
diagnostic.py
</pre>

<hr>

<h2> Database</h2>

<p>SQLite database files are stored in:</p>

<pre>
backend/instance/safecity.db
</pre>

<p>Upload logs & detections:</p>

<pre>
backend/uploads/
</pre>

<hr>

<h2> Environment Configuration</h2>

<p>Local environment variables are stored in:</p>

<pre>
.env.local
</pre>

<p>Make sure to configure:</p>

<ul>
  <li>Backend API URL</li>
  <li>Database path</li>
  <li>Model paths</li>
</ul>

<hr>

<h2> Use Cases</h2>

<ul>
  <li>Traffic & helmet violation monitoring</li>
  <li>City safety analytics</li>
  <li>Incident reporting system</li>
  <li>Smart surveillance dashboards</li>
</ul>

<hr>

<h2> Contributing</h2>

<p>
Pull requests are welcome. For major changes,
please open an issue first to discuss proposed updates.
</p>

<hr>

<h2>License</h2>

<p>This project is for academic & research purposes.</p>

<hr>

<h3> If you find this project useful, consider giving it a star!</h3>
