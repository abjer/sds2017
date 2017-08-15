Dear all, 

Just a quick update on today. 

There were some troubles loading the facebook data csv file. The solution to this was to use a pickled version instead. 
This means you should download [this file](https://dl.dropboxusercontent.com/u/5572785/fb_compiled2.pkl) instead.
Furthermore you should load the data as pkl instead of csv, this means:

`df = pd.read_pickle('fb_compiled2.pkl')`

Another problem was that the NLTK package does not come with all functions by the simple install. 
You should use the package's own downloader like this:

`nltk.download('punkt')`

or run the following command in your commandline:

`python -m nltk.downloader all`

and if that fails add sudo like this:
`sudo python -m nltk.downloader all`

Tomorrow we are gonna continue our work with this dataset and the NLTK package, so make sure it is up and running.

See you, 

Snorre

