How to connect shopify to github

1. Download the file on shopify
2. Initialize a New Git Repository: <br>
	If you are not in a Git repository, you might need to initialize a new one. Use the following command to create a new Git repository in the current directory:
	(git init)

3. use this command line <br>
echo "# Dawn-theme" >> README.md <br>
  git init // for initial git repo <br>
  git add README.md  // create readmefile  <br>
  git commit -m "first commit" // for commit  <br>
  git branch -M main // for change branch <br>
  git remote add origin https://github.com/ruksana-saifi/Dawn-theme.git  <br>
/* for connect shopify to local */  <br>
  git push -u origin main // for shortcut <br>

git add . <br>
git commit -m 'initail files' <br>
git push  <br>
if your files is visibles on git it means you successfully connect git to local <br>

4. now go to the shopify dashboard and click add theme > connect from Github
select yor repo and connect main

now publish you theme 
you have been successfull added github to shopify

