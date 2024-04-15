

###  👉 Create a virtual environment
Write whatever name you prefer (e.g. `conda` or `venv` or `test`)
```console
$ python3 -m venv test
```

### 👉 Activate it
Mac / Linux:
```console
. test/bin/activate
```
Windows:
```console
test\Scripts\activate
```

###  👉 Install  dependencies
.

You also need `nltk`:
 ```console
pip install Flask torch torchvision nltk
 ```

If you get an error during the first run, you also need to install `nltk.tokenize.punkt`:
Run this once in your terminal:
 ```console
$ python
>>> import nltk
>>> nltk.download('punkt')
```

### 👉 Usage
Run
```console
python train.py
```
This will dump `data.pth` file. 

```console
python app.py
```
This will help us connect the chatbot model with the frontend. 

Below command will run the chatbot in command line.

```console
python chat.py
```
