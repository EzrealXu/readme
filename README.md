# readme
I use LOTClass to make the prediction.
To reproduce the result run the following code in your workspace
```
$ git clone https://github.com/yumeng5/LOTClass
```
Then install the dependencies

```
$ pip3 install -r requirements.txt
```
Then download 'stopwords'

```
import nltk
nltk.download('stopwords')
```

Replace the ```datasets``` folder from LOTClass with the folder with same name in the file I submit.

Add files ```news.sh``` and ```movies.sh``` in the ```LOTClass``` workspace.

Then run ```news.sh``` and ```movies.sh```, you can get the result.

