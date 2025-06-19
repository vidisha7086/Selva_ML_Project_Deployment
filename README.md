<h1>First set up git by doing below setup :</h1>

<p>✅ <code>git init</code><br>
Initializes a new Git repository in your current folder by creating a hidden <code>.git/</code> directory.<br>
🔧 Makes the folder trackable by Git.
</p>

<p>✅ <code>git add .</code><br>
Stages all files in the current directory (and subfolders) for the next commit.<br>
📥 Adds everything to Git's "staging area" so it can be committed.
</p>

<p>✅ <code>git commit -m "Initial commit"</code><br>
Saves a snapshot of your staged changes with a message.<br>
💾 First version of your project saved in Git history.
</p>

<p>✅ <code>git branch -M main</code><br>
Renames the current branch to <code>main</code>.<br>
🌿 Standardizes your branch name (GitHub prefers <code>main</code> instead of older <code>master</code>).
</p>

<p>✅ <code>git remote add origin https://github.com/...</code><br>
Links your local Git repo to a remote GitHub repository named <code>origin</code>.<br>
🔗 So you can push and pull between local and GitHub.
</p>

<p>✅ <code>git push -u origin main</code><br>
Pushes your local <code>main</code> branch to the remote <code>origin</code> (GitHub).<br>
The <code>-u</code> sets up tracking, so you can later just use <code>git push</code> or <code>git pull</code>.<br>
🚀 Sends your code to GitHub.
</p>

<hr>

<h1>Classification ML Model as Flask API</h1>

<ol>
  <li>First create the ML model by running <code>python create_model.py</code>.</li>
  <li>Then, run <code>python app.py</code> to start the server.</li>
</ol>

<p>The URL to access the app will be provided in the console output.</p>


# Classification ML Model as Flask API

1. First create the ML model by running `python create_model.py`.
2. Then, run `python app.py` to start the server. 

The url to access the app will be provided at the console output.
