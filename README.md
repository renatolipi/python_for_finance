Mastering Python for Finance - Updated examples
=====

This repository is an update version from the 2015 edition of the book *Mastering Python for Finance*.


### Getting started


Clone this project:

```
$ git clone <reponamegitstufhere>
```


It's recommended that you create a virtualenv using Python 3, in order to istall Python libraries used in this project:

```
$ virtualenv -p python3 VENV
```

Then activate it:

```
$ source VENV/bin/activate
```


### Chapter 1 

This chapter introduces *IPython Notebook*. This is the first difference: nowadays it was "replaced" by *Jupyter Notebook*. It's the **new** *IPython Notebook*.

So, you're going to install *Jupyter Notebook*. The author also uses some libs like *numpy*  and *matplotlib*, but the book doesn't mention it. This repo put all the necessary libs into `requirements.txt` in order o make it easier to get your workspace done.

Install all the necessary libraries:

```
$ pip install -r requirements.txt
```

Start Jupyter Notebook:

```
$ jupyter notebook
```

