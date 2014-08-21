# python-observer-notebook

An ipython notebook for playing with observer pattern libraries

## Overview

I wanted to check out some libraries that implemented the observer pattern and compare them.

## Criteria

* simple event definitions with simple registration of multiple handlers
* all args of the event are passed to the handlers
* handler registration detects duplicate functions
  * multiple adds of the same function
  * avoid multiple dispatch to any handler
* errors in one handler do not prevent other handlers from running
* open source project health

## Libraries

* [nmevent](http://pythonhosted.org/nmevent/)
* [Observed](https://github.com/DanielSank/observed)
* [py-notify](http://download.gna.org/py-notify/reference/index.html)

## Running

This is an ipython notebook. To see the notes for comparing libraries, do

```
brew install zeromq  # Or whatever is appropriate for your OS 
pip install -r requirements.txt
ipython notebook
```
