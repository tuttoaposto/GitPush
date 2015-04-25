#To git push ([more from railgirls] (http://guides.railsgirls.com/github/))

1. Change directory to where the file to be pushed is located	
cd 'C:\Users\Administrator\RFolder\Assignment2\ProgrammingAssignment2'

2. Initialize a git repository in the folder	
git init

3. Check file status	
git status

4. Add file(s) to be pushed	
git add yourfiles

5. Commit file(s)	
git commit -m 'first commit'

6.Set up link to GitHub repository. Copy URL from cliboard icon 'HTTP clone URL' on right.	Can skip this step if URL has been set up, e.g. modify a file in the same GitHub repository.

git remote add origin https://github.com/tuttoaposto/ProgrammingAssignment2.git


7. Push commits to GitHub	
git push -u origin master

8. If need further modification of the same file, just take steps 4, 5, 7	