
# GitHub

1. What is GitHub
2. Overview of GitHub
3. GitHub account creation
4. Difference between Git & GitHub
5. Difference with other tools
6. Create repo in local machine and push to GitHub
7. Clone existing repos from GitHub
8. Managing tags remotely
9. Fetch and Pull
10. Workflow
11. Forking Repos
12. Pull Request
13. Deleting and renaming GitHub Repos

## Remote Repos / Source Code Repositories
1. GitHub
2. Bitbucket
3. GitLab
4. Azure DevOps Repo
5. AWS CodeCommit
...etc

## GitHub
GitHub is a website and cloud-based service that helps developers store and manage their code, as well as track and control changes to their code.
@ It is a website to upload repositories online.
@ Provides remote backup.

## GitHub Account Creation
Sign up at: https://github.com/
Note: Steps to create an account are in the "GitHub installation folder" in Google Drive.

## Difference between Git vs GitHub
1. Git is a tool                                 -    GitHub is a website (github.com)
2. Git is Command Line Interface (CLI)           -    GitHub is Graphical User Interface (GUI)
3. We can't view data in a bare repo             -    But we can view and manage bare repos in GitHub
4. Bare is just bare here                        -    In GitHub, you can convert bare repo to non-bare
5. Here, we create non-bare by cloning bare repo -    In GitHub, we can directly create/init non-bare repos
6. Local                                         -    Remote
7. We push changes from non-bare to bare repo    -    We push from non-bare to GitHub remotely


## Difference with Other Tools (Why GitHub?)
@ Provides a nice visual interface for repos
@ Makes user collaboration easier
@ Security
@ 24/7 support
@ User-friendly
@ Flexibility
@ Provides backup for repos
@ Acquired by Microsoft

## 1. Create Repo in Local Machine and Push to GitHub

git init  
git add README.md  
git commit -m "first commit"  
git remote add origin https://github.com/VmTutes/hello.git  
git push -u origin master  
username:-  
password:- PAT Token  

Note: To generate PAT token, go to settings > developer settings > personal access tokens > classic > generate new token

## 2. Clone Existing Repos from GitHub
- Clone existing repository from GitHub to your local machine:  
  >> git clone https://github.com/VmTutes/Vinodh-Machireddy-Tutorials.git

- Make changes, add, commit, and push:  
  git push (or) git push origin master

## Managing Tags Remotely
To create a tag:  
  - git tag tag_name

Push tags from local repo to GitHub:  
  - git push origin --tags

To delete tags remotely in GitHub:  
  - git push origin -d tag_name

To delete tags locally:  
  - git tag -d tag_name

## Fetch and Pull Differences
pull = fetch + merge

fetch: Downloads changes to the local machine but does not integrate them.  
merge: Integrates downloaded changes into the local repo.

# Workflow
   |		Add	       |	Commit	       |			      |	 	
	     |------------------------>|---------------------->| 			      |  		       			      
	     |----------------Commit -a ---------------------->|	  git push            |
	     |			       |		       |----------------------------->|
	Working Dir		     Index		Commiting Area 		          Repo(GitHub)
	(work space)  	  	   (Staging)	    	    (HEAD)			      | 	
	     |			       |		       |<----------git fetch----------|
	     |<-------------------Merge------------------------|			      |	
	     |			       |		       |			      |	
	     |<----------------------------------Pull-----------------------------------------|
	     |<--------------------diff HEAD------------------>|			      |
	     |<----------diff--------->|

## Forking Repos
A fork is a copy of a repository. Forking allows you to experiment with changes without affecting the original project.

## Pull Request
Send a request to merge your forked or feature branch into the original repository.

## Deleting and Renaming GitHub Repos
Go to the repository settings page to rename or delete.  
https://github.com/VmTutes/Vinodh-Machireddy-Tutorials/settings

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


                                     ========= THE END =========

                        +91-7204143230 (WhatsApp/Call), Email: VmTutes@gmail.com
