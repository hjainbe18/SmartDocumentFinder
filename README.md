# SmartDocumentFinder
How easy do you find it to remember the exact location of a document that you created last year? Not very easy, right? Big Organizations/people deal with hundreds of documents daily and forget about them, most of the time.
<br>
But what if we want that old documentation again for some work, but unfortunately you do not remember the name or the actual content of that document to retrieve it from the large storage of your computer.
<br>
In such cases, use of a __Smart document finder__ can really make a huge difference. As, it can Search for the document of your need based on a query input. This will not only help in faster access to the document, but will also help in grouping similar documents together and in analysing them.
<br>

# How to Install and Use <img src="https://img.icons8.com/color/40/000000/settings.png"/> ?

```> mkdir IntelligentDocumentFinder```
<br>
<br>
```> cd IntelligentDocumentFinder```
<br>
<br>
```> https://github.com/hjainbe18/SmartDocumentFinder.git```
<br>

Install Vitual Environment if not installed
<br>
- On Linux/MacOs
```> python3 -m pip install --user virtualenv```
- On windows
```> py -m pip install --user virtualenv```

Create Virtual Environment
- On macOS and Linux:
```> python3 -m venv env```
- On Windows:
```> py -m venv env```

Activate Environment:
- On macOS and Linux:
```> source env/bin/activate```
- On Windows:
```> .\env\Scripts\activate```

```> pip install -r requirements.txt```

__Download Glove Word Embeddings__ from this [link](https://www.kaggle.com/danielwillgeorge/glove6b100dtxt), decompress it and copy the ```glove.6B.100d``` file in ```DataBase``` folder

then, 
run initial_file.py through this command
```> python initial_file.py```

Now you are good to go.. Just type this command everytime you want to access it, and open the website in chrome/firefox
<br>
```> python src/app.py```
<br><br>
