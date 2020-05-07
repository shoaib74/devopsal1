# devopsal1
# This is a Devops CI/CD (git+github+jenkins interation) Project.
Here I'm going to explain you step by step how to create this project.
Step1.
You have to install git on your windows/mac os. and also you have to create an account on github.Afte Creating an Account on git hub go to github repository and create ne repository and copy read.md details and go to git bash and also create one repository heare then paste the url into git bash repo.

Step2.
Now Create one branch using git branch dev1.
go to the branch you create using git checkout dev1.

Now you are in dev2 branch here you develop you site
example: notepad index.html
This is CI CD website

now save it.

type git add index.html in your git bash.

git commit index.html
git push

above process push your code into github.

Step3.
Now install jenkins and login then
go to create job.
here we are creating 3 jobs.
1. testing job1
2. production job2
3.QAT job3

we used job 1 for testing ,job 2 to for productiom and and job 3 for quality accurance team.

job1 is upstream for job3 and job3 is upstream for job2.

Now for better understanding please go to project documentation

Thank you :)
