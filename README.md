# Rasa Test Bot

---
## What's in this repository?

- Contains elementary rasa-nlu bot which is in itself a medicare locator
- New training data is uploaded from time to time, so please keep a check.

## What do you need to follow this episode?

Steps to run:
-  go to the project directory
- create Virtual environment
- ```pip3 install rasa``` // install the rasa package
- ```rasa train``` // train the existing nlu model
- ```rasa run actions & rasa shell``` //initialize the bot in command-line

## Optional:

In addition to this you need to install additional dependency to run Rasa on Jupyter 
notebooks:  
```pip install nest_asyncio```

