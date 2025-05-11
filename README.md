<h1 align="center">GUI based 🏥 Hospital Management System</h1>

<p>This project is based on <strong>Hospital Management System GUI</strong> application built using <strong>Python</strong> for the frontend and <strong>SQL</strong> for data operations. It allows users to manage patient and prescription records efficiently.</p>

<h2>🚀 Features</h2>
<ul>
  <li>Add, Update, and Delete patient records</li>
  <li>Auto-fill form fields on selecting a record</li>
  <li>Generate prescription as formatted text</li>
  <li>Scrollable tabular view of stored data</li>
  <li>Form validation and error handling</li>
  <li>Exit confirmation dialog</li>
</ul>

<h2>🛠️ Built With</h2>
<ul>
  <li>Python</li>
  <li>Tkinter (for GUI)</li>
  <li>ttk (modern widgets)</li>
  <li>SQL (via SqlQueries.py)</li>
</ul>

<h2>📁 File Structure</h2>
<pre>
.
├── Hospital.py             # Main GUI application
├── SqlQueries.py           # SQL logic file (required)
├── images/                 # Optional folder for assets
└── README.html             # This file
</pre>

<h2>🔑 Key Functionalities</h2>
<ul>
  <li><code>Iprescription()</code> – Inserts new patient data into DB</li>
  <li><code>Iupdate()</code> – Updates selected record</li>
  <li><code>Idelete()</code> – Deletes selected entry</li>
  <li><code>Iprectioption()</code> – Generates formatted prescription</li>
  <li><code>clear()</code> – Clears all input fields</li>
  <li><code>get_cursor()</code> – Auto-fills form with selected row</li>
  <li><code>show_data()</code> – Displays latest data in table</li>
  <li><code>exist()</code> – Exits with confirmation</li>
</ul>

<h2>▶️ How to Run</h2>
<ol>
  <li>Ensure Python and Tkinter are installed</li>
  <li>Keep <code>Hospital.py</code> and <code>SqlQueries.py</code> in the same folder</li>
  <li>Run the program using:</li>
</ol>
<pre>python Hospital.py</pre>

<h2>📸 Screenshots</h2>

<h2>🙋‍♂️ Author</h2>
<ul>
  <li><strong>Name:</strong> Chitransh Shrivastava</li>
  <li><strong>Email:</strong> chitranshshrivastava102@gmail.com</li>
  <li><strong>GitHub:</strong> <a href="https://github.com/Shrivastava-1">Shrivastava-1</a></li>
</ul>

<h2>📄 License</h2>
<p>This project is intended for educational purposes. Feel free to modify and improve it.</p>

<hr />
<p><strong>Made with ❤️ by Chitransh Shrivastava</strong></p>
