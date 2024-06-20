# earthscape.github.io

UPDATE

To bring in changes to a submodule, change (cd) to the submodule's folder and do

	git pull

Or run

	cd localsite &&
	git pull https://github.com/ModelEarth/localsite main &&
	cd ../earthscape &&
	git pull https://github.com/DreamStudioCode/earthscape main


INITIALLY

	You only have to run the recursive command once at the end.

	git submodule add https://github.com/ModelEarth/localsite localsite && 
	git commit -m "localsite submodule"

	git submodule add https://github.com/ModelEarth/earthscape earthscape && 
	git commit -m "earthscape submodule"

	git submodule update --init --recursive