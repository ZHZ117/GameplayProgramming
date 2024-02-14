# Peer-Review for Programming Exercise 3 #

## Description ##

For this assignment, you will be giving feedback on the completeness of assignment three: Pikmini. To do so, we will give you a rubric to provide feedback. Please give positive criticism and suggestions on how to fix segments of code.

You only need to review code modified or created by the student you are reviewing. You do not have to check the code and project files that the instructor gave out.

Abusive or hateful language or comments will not be tolerated and will result in a grade penalty or be considered a breach of the UC Davis Code of Academic Conduct.

If there are any questions at any point, please email the TA.   

## Due Date and Submission Information
See the official course schedule for due date.

A successful submission should consist of a copy of this markdown document template that is modified with your peer review. This review document should be placed into the base folder of the repo you are reviewing in the master branch. The file name should be the same as in the template: `CodeReview-Exercise3.md`. You must also include your name and email address in the `Peer-reviewer Information` section below.

If you are in a rare situation where two peer-reviewers are on a single repository, append your UC Davis user name before the extension of your review file. An example: `CodeReview-Exercise3-username.md`. Both reviewers should submit their reviews in the master branch.  

# Solution Assessment #

## Peer-reviewer Information

* *name:* [your name here] 
* *email:* [your @ucdavis.edu email address here]

### Description ###

For assessing the solution, you will be choosing ONE choice from: unsatisfactory, satisfactory, good, great, or perfect.

The break down of each of these labels for the solution assessment.

#### Perfect #### 
    Can't find any flaws with the prompt. Perfectly satisfied all stage objectives.

#### Great ####
    Minor flaws in one or two objectives. 

#### Good #####
    Major flaw and some minor flaws.

#### Satisfactory ####
    Couple of major flaws. Heading towards solution, however did not fully realize solution.

#### Unsatisfactory ####
    Partial work, not converging to a solution. Pervasive Major flaws. Objective largely unmet.


___

## Solution Assessment ##
### Stage 1.1 ###

- [X] Perfect
- [ ] Great
- [ ] Good
- [ ] Satisfactory
- [ ] Unsatisfactory

___
#### Justification ##### 
The watcher is correctly set, and all pikminis groups can change their color.
___
### Stage 1.2 ###

- [X] Perfect
- [ ] Great
- [ ] Good
- [ ] Satisfactory
- [ ] Unsatisfactory

___
#### Justification ##### 
The stage1.2 is well implemented， the watcher checks the color every 1 sec.

___
### Stage 2.1 ###

- [X] Perfect
- [ ] Great
- [ ] Good
- [ ] Satisfactory
- [ ] Unsatisfactory

___
#### Justification ##### 
Correctly implement Subscribe, Unsubscribe, and Notify methods in Publisher.cs.

___
### Stage 2.2 ###

- [X] Perfect
- [ ] Great
- [ ] Good
- [ ] Satisfactory
- [ ] Unsatisfactory

___
#### Justification ##### 
Implement the Pbulisher class correctly. 

___
### Stage 2.3 ###

- [X] Perfect
- [ ] Great
- [ ] Good
- [ ] Satisfactory
- [ ] Unsatisfactory

___
#### Justification ##### 
The Pikminis can correctly receive the message and change the Subscriber to go to a different place.

___
### Stage 3 ###

- [ ] Perfect
- [ ] Great
- [X] Good
- [ ] Satisfactory
- [ ] Unsatisfactory

___
#### Justification ##### 
The code is correct, and the implementation is perfect. There is just a minor mistake that caused the problem. The script is not added to the Spawn component. So I can't click fire 2 to generate the Pikminis. But the code is correct since I add it to the Spawn, the generation works fine.

___
# Code Style #


### Description ###
Check the scripts to see if the student code adheres to the dotnet style guide.

If sections do not adhere to the style guide, please peramlink the line of code from Github and justify why the line of code has not followed the style guide.

It should look something like this:

* [description of infraction](https://github.com/dr-jam/ECS189L) - this is the justification.

Please refer to the first code review template on how to do a permalink.


#### Style Guide Infractions ####

___

# Best Practices #

### Description ###

If the student has followed best practices (Unity coding conventions from the StyleGuides document) then feel free to point at these code segments as examplars. 

If the student has breached the best practices and has done something that should be noted, please add the infraction.


This should be similar to the Code Style justification.


#### Best Practices Exemplars ####
The code successfully follows the code style guidelines. There are comment to express the code.

https://github.com/ensemble-ai/exercise-3-observer-pattern-JasonBMa/blob/e1a496faefc59561f4c1158a8fffb52463ab1b5e/Pikmini/Assets/Scripts/PikminiSpawner.cs#L7
And the code unsubscirbe the dying Pikminis, I think it is good way to aovid the bug or other issues when destory Pikminis.

https://github.com/ensemble-ai/exercise-3-observer-pattern-JasonBMa/blob/e1a496faefc59561f4c1158a8fffb52463ab1b5e/Pikmini/Assets/Scripts/MiniController.cs#L93

Overall the code was very clean and tidy and every step was completed as required. Great job!
