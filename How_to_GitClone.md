#To git fork and clone   

1. On GitHub, fork (i.e. copy) the original repo to my repo   
e.g. https://github.com/rdpeng/ExData_Plotting1   

2. In my forked repo page, copy the clone URL: https://github.com/rdpeng/ExData_Plotting1.git   

3. Go to GitBash, change directory to where you want the cloned repo to be   	
cd 'C:\Users\Administrator\RFolder\ExpDataAnalysis'   

4. Clone repo to local machine with the clone URL   
git clone 'https://github.com/rdpeng/ExData_Plotting1.git'   

5. Now files in the forked repo are copied to a sub-directory named after the original repo   
   i.e. C:\Users\Administrator\RFolder\ExpDataAnalysis\ExData_Plotting1   

6. Move files to be pushed to the directory created in step 5   

7. Add file(s) to be pushed   
git add \*.png \*.R  (**all png and R files**)

8. Commit file(s)    
git commit -m 'first commit'   

9. Push commits to GitHub   
git push -u origin master


## Indent items with 4 spaces to make ordered sublist