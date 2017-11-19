##Work in progress!!

This fork of Patrick Harrison's (@skipgram) notebook incorporates a few updates, most saliently: 

- Python 2.x -> 3.6
- spaCy 1.x -> 2.0

I've also updated to the current (newer, larger!) Yelp reviews dataset. 

##A few notes: 

- There's now an environment.yml file so setup should be a little more straightforward if you want to use the notebook yourself.
- I am _not_ including the yelp reviews dataset here, (a) because it's large, and (b) because I think the T&C's prohibit it. You can grab it yourself (instructions in the notebook).
- This is (as of 19 Nov 2017) a work in progress and I'm still figuring out how some things work (or whether they are working or not!). I HAVEN'T YET RUN THE WHOLE THING. PRs and issues and such are welcome.

##To use the notebook:

You'll need to have [Anaconda](https://www.anaconda.com/download/) (I think mini-conda will work, too, but I'm not sure) installed. 

Then: 

Clone the repository: 
`git clone https://github.com/herdingbats/modern-nlp-in-python.git`

Navigate to the directory: 

`cd modern-nlp-in-python/` 

Create the environment, downloading your needed dependencies: 
`conda env create`


Activate the new environment:
`source activate pynlp`

And download spaCy's default English-language model:
`python -m spacy download en`

Then launch Jupyter Notebook and you're off to the races!
`jupyter notebook`