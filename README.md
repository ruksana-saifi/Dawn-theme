<h1>How to connect shopify to github</h1>

<h3>1. Download the file on shopify</h3>
<h3>2. Initialize a New Git Repository: <br></h3>
	If you are not in a Git repository, you might need to initialize a new one. Use the following command to create a new Git repository in the current directory:
	(git init)

<h3>3. use this command line <br></h3>
  echo "# Dawn-theme" >> README.md <br>
  git init // for initial git repo <br>
  git add README.md  // create readmefile  <br>
  git commit -m "first commit" // for commit  <br>
  git branch -M main // for change branch <br>
  git remote add origin https://github.com/ruksana-saifi/Dawn-theme.git  <br>

  <h4>/* for connect shopify to local */  <br></h4>
  git push -u origin main // for shortcut <br>
  git add . <br>
  git commit -m 'initail files' <br>
  git push  <br>
  if your files is visibles on git it means you successfully connect git to local <br>

<h3>4. now go to the shopify dashboard and click add theme > connect from Github
    select yor repo and connect main</h3>
    now publish you theme 
    you have been successfull added github to shopify

