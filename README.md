<h1>🚀 Git Setup: Initialize and Push Your Project</h1>

<p>Follow these steps to set up Git for your project and push it to GitHub.</p>

<table>
  <thead>
    <tr>
      <th>✅ Git Command</th>
      <th>📘 Explanation</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>git init</code></td>
      <td>Initializes a new Git repository in the current folder by creating a hidden <code>.git/</code> directory. 🔧 Makes the folder trackable by Git.</td>
    </tr>
    <tr>
      <td><code>git add .</code></td>
      <td>Stages all files in the directory (and subfolders) for the next commit. 📥 Moves files to Git’s staging area.</td>
    </tr>
    <tr>
      <td><code>git commit -m "Initial commit"</code></td>
      <td>Creates a snapshot of the staged changes with a message. 💾 First version saved in Git history.</td>
    </tr>
    <tr>
      <td><code>git branch -M main</code></td>
      <td>Renames the current branch to <code>main</code>. 🌿 GitHub prefers <code>main</code> over the older <code>master</code>.</td>
    </tr>
    <tr>
      <td><code>git remote add origin &lt;your-repo-url&gt;</code></td>
      <td>Links your local repo to a remote one on GitHub. 🔗 Enables pushing/pulling code.</td>
    </tr>
    <tr>
      <td><code>git push -u origin main</code></td>
      <td>Pushes your local <code>main</code> branch to the <code>origin</code> repo on GitHub. 🚀 Sets up upstream tracking.</td>
    </tr>
  </tbody>
</table>

<hr>

<h1>📦 Classification ML Model as Flask API</h1>

<p>This project demonstrates how to build and deploy a Machine Learning classification model via a Flask API.</p>

<h2>🔧 Steps to Run</h2>

<ul>
  <li>Train the model using: <code>python create_model.py</code></li>
  <li>
