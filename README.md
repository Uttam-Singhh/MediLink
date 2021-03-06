# MediLink
A Web App that connects students on our Campus (Medicaps University). 
* People can write & share Blogs.
* They can find their Class notes.
* They can know their Subject Syllabus.
* Anyone can post a Question & can Answer.

It helps students to interact virtually.

## Contributions to this repo are WELCOME ⚡️🙌🏻
- :art: give suggestions on how to improve the UI design
- :hammer: try to break the website by testing it to find any bugs. If you find any, check if there is an issue already open for it, if there is none, then report it

## Tools, Languages & Frameworks used
* Django (Backend Framework)
* HTML
* CSS
* JavaScript
* Bootstrap

## Steps to be followed in order to make valid contributions ☘️

**1.** Fork the [MediLink](https://github.com/Uttam-Singhh/MediLink) repo by clicking on the fork button on the top of the page. This will create a copy of this repository in your account.

**2.** Clone the forked repository

	git clone "https://github.com/<your-github-username>/MediLink"
	
* Download and install Python 3.7
* Download and install Git.
* Change directory to MediLink `$ cd MediLink`
* Install virtualenv `$ pip3 install virtualenv`
* Create a virtual environment `$ virtualenv env -p python3.7`( You can also use conda to create a virtual env)
* Activate the env: `$ source env/bin/activate` (for linux) `> ./env/Scripts/activate` (for Windows PowerShell)
* Install the requirements: `$ pip install -r requirements.txt`
* Run the server `$ python manage.py runserver`
	
**3.** Make necessary changes and commit those changes.<br/>
Remember never push anything to the Main branch.<br/>
Always change your branch to "develop" using:

        git checkout develop
	
Again check your current branch using:
        
	git branch
	
It should point *develop

Now add your changes using:

	git add files-you-edited
If there are multiples file you can use:

        git add .
	
Now create a commit message using:

	git commit -m "<commit-message-goes-here>"
	
**4.** Push changes to GitHub

	git push origin develop
	
**5.** Create a Pull Request 🤟🏻 
	<br>Now you go to your repository on GitHub, you’ll see a `Compare & pull request` button. Click on that button and now write a summary of what changes you have done.( Attach images if required). We'll review your code and merge it if it passes all the tests.❤️
