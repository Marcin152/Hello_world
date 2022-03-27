# Hello_world

- Wpisujmey komendy w tej kolejności
	- mkdir FlaskApp
	- cd FlaskApp
	- py -3 -m venv venv
	- venv\Scripts\activate
	- pip install Flask
- Tworzymy plik hello_world w edytorze kodu z zawartością:
	
	```
	from flask import Flask

	app = Flask(__name__)

	@app.route("/")
	def hello_world():
    		return "<p>Hello, World!</p>"
	```	
		
- Zapisać plik w stworzonym folderze FlaskApp
- Deklarujemy nasz kod hello_world jako flask app
	- set FLASK_APP=Hellow_world.py
- Włączenie aplikacji
	- flask run
- Kopiujemy podany adres URL i wklejamy do naszej przeklądarki aby sprawdzić czy nasza aplikacja działa
- Zapisujemy listę zainstalowanych pakietów komendą
	- pip freeze > requirements.txt
	
