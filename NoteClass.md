                                                            05/05/2018
# UPDATE FORK 

    git remote add upstream [link]

    git remote update

    git pull --rebase upstream master

# COMMITS GRAPHIC

    glog == git log --graph --decorate --pretty=oneline --abbrev-commit

# COMMIT CHANGES
 
    git rebase -i master~(amount of commits you what change)

    git push origin master --force
__________________________________________________________________________
                                                            12/05/2018
# Eloquent Javascript

    Vscode 10 - Debug - break point  

    Imutabilidade (const > let > var) = Respeita o scopo

* Look For
    
    map; reduce; filter
__________________________________________________________________________
							    19/05/2018
'-> * Continuation
	
	objeto = json --> a: 1

	./aquivo --> module.export = {obj}

	const x = require('./arquivo').objImported
	* |OR|
	import {obj} from './arquivo'	

	Object.keys(obj) = transformation in list to use functions 

# node.js and npm instalation

	sudo apt-get install curl

	curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash -

	sudo apt-get install -y nodejs

	npm init

