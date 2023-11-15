# AI.MD
Final project for the Building AI course

## Summary
Describe briefly in 2-3 sentences what your project is about. About 250 characters is a nice length!

The idea is to create a large language model similar to Open.Ai but focused on medicine. It should be used to support the making of diagnosis and writting of journal entries, and messages to patients and colleagues. The model needs to be trained on the lates medicine research, journals, and other relevant data. 

## Background

Which problems does your idea solve? How common or frequent is this problem? What is your personal motivation? Why is this topic important or interesting?

The idea solves a couple of problems, which I have some insight to due to my wife being a medical doctor in the primary healthcare system in Sweden. It is interesting because the primary healthcare system (e.g., health centres or Vårdcentral in Swedish) in Sweden is severly understaffed. Boosting efficiency through tech could reduce the problem and free up time for doctors. 

Some problems it can solve:
* problem 1: Low efficiency making diagnosis. Making diagnosis can be difficult and time consuming. Time consuming especially when young doctors need to call more experienced doctors for advice. Also, it can help make more accurate diagnosis. 
* problem 2: Low efficiency doing admin. The journal entry and admin system is outdated and badly designed. Today mds spend a lot of time just putting information into a slow system, which is a waste of time. The doctors even make audio dictations which are written by clerical staff. A smooth and updated intuitive system which allows for direct speech-to-text entry would be great. Could also be used to write and send messages to colleagues and patients. 



## How is it used?

Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?
The solution should be a combined journal and admin system with a large language model, primarly used by health providers like medical doctors, nurses, and medical lab workers. I focus on doctors and they should use it througout their work. 

Situations of use:
* After a doctor has met a patient they enter the reported symptoms into the AI to get help in making a correct diagnosis. The AI will suggest possible diagnosis and which tests to take. Tests are most likely taken by nurses who also put information into the AI. Advanced tests are analysed at labs, and information is add to the AI by lab workers. The doctor gets the results of the tests and the AI updates suggested possible diagnosis and says if further tests are needed. The doctor uses the output of the model as a support to make a final diagnosis and informs the patient. The doctor puts the diagnosis into the patients journal with speech-to-text function.
* Any time information is put into the system a speech-to-text function is used, any minor errors can be adjusted immidiately by changing the text which is put on the screen in front of the person. This means clerical staff might be replaced. 


## Data sources and AI methods
Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
This AI solution would need to be co-developed with the health authorities, and they would need to provide most of the data. 
Data sources:
* Journals of patients. 
* Internal documents.
* Messages to patients.
* Highly-reliable medical research articles, for example, peer-reviewed litterature studies in respected academic journals. 

Methods:
Word-to-speech translation to enter information into the AI. 
Large language model to write texts.
Neural networks used to guess diagnosis.

## Challenges

What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?
Surely there are some limitations to this solution, and the biggest is like the ethical consideration. I don't know if it is ethically okay to train the AI on sensitive information like journals and messages sent by patients and healthcare workers. Hopefully this can be resolved by all information being anonymous or ensuring that no human will read the training data.
Hallucination and error in diagnosis, the AI will not guess diagnose perfectly. Trusting the AI blindly is a bad idea! Doctors should only see it as a support to remember which tests to take and which possible unlike diagnosis (which could be forgotten) it could be. This challenge should be solved by instructing doctors how to use the software and what its limitations are. 



## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you need to move on? 
Well, I just made this up, it feels far off that I will take this project forward. But I guess I would need some skilled programmers, someone with insight into the available data in the healthcare system, and contacts with the big guys making the decisions in healthcare.

## Acknowledgments

