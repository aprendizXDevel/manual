# CODE's GUIA

* Install Sublime:
	
	`wget -qO - https://download.sublimetext.com/sublimehq-pub.gpg | sudo apt-key add -`
	
	`echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list` - (Nao precisa da 	lincença)
	
	`sudo apt update && sudo apt install sublime-text`
__________________________________________________________________________
*ALWAYS HAVE TO DO IN A NEW PROJECT 

* Install [virtualenv](https://virtualenv.pypa.io/en/stable/installation/)

	`sudo apt-get install python-virtualenv`

* Install [Python 3.6](https://www.python.org/)

	`sudo add-apt-repository ppa:deadsnakes/ppa`
	
	`sudo apt-get update`
	
	`sudo apt-get install python3.6`

* Create a virtualenv 
	
	`virtualenv -p python3.6 lib`

* Activate the virtual env 
	
	`source lib/bin/activate`   or   `. lib/bin/activate` 

* Install Flask:

	 `pip install flask`
__________________________________________________________________________

* Step-by-step Simple [Git](http://gabsferreira.com/criando-e-enviando-arquivos-para-seu-repositorio-no-github/)

	`git init`
	`
	git remote add origin "repository link"`
	
	`git add "name of what you'd like to commit`
	 
	 `git commit -m "mensagem/comentario"`(optional)
	
	`git push -u origin master`

* Updating remote-local

	`git remote add upstream (link)`

	`git remote update`

	`git pull --rebase upstream master`
__________________________________________________________________________
* Run the application: 

	`FLASK_DEBUG=1 FLASK_APP=app.py flask run`   or    `python app.py`
