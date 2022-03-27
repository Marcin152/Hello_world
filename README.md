# Hello_world

- 1.Wpisujmey komendy po kolei
	mkdir FlaskApp
	cd FlaskApp
	py -3 -m venv venv
	venv\Scripts\activate
	pip install Flask
-2. Tworzymy plik hello_world w edytorze kodu z zawartością:
	from flask import Flask

	app = Flask(__name__)

	@app.route("/")
	def hello_world():
    		return "<p>Hello, World!</p>"
-3.Zapisać plik w stworzonym folderze FlaskApp
-4.Deklarujemy nasz kod hello_world jako flask app
	-set FLASK_APP=Hellow_world.py
-5.Włączenie aplikacji
	flask run
-6.Kopiujemy podany adres URL i wklejamy do naszej przeklądarki aby sprawdzić czy nasza aplikacja działa
-7.Zapisujemy listę zainstalowanych pakietów komendą
	pip freeze > requirements.txt
	
