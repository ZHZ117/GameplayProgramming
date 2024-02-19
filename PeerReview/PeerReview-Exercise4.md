# Peer-Review for Programming Exercise 4 #

## Description ##

For this assignment, you will be giving feedback on the completeness of assignment four: Aegis. To do so, we will give you a rubric to provide feedback. Please give positive criticism and suggestions on how to fix segments of code.

You only need to review code modified or created by the student you are reviewing. You do not have to check the code and project files that the instructor gave out.

Abusive or hateful language or comments will not be tolerated and will result in a grade penalty or be considered a breach of the UC Davis Code of Academic Conduct.

If there are any questions at any point, please email the TA.   

## Due Date and Submission Information
See the official course schedule for due date.

A successful submission should consist of a copy of this markdown document template that is modified with your peer review. This review document should be placed into the base folder of the repo you are reviewing in the master branch. The file name should be the same as in the template: `CodeReview-Exercise4.md`. You must also include your name and email address in the `Peer-reviewer Information` section below.

If you are in a rare situation where two peer-reviewers are on a single repository, append your UC Davis user name before the extension of your review file. An example: `CodeReview-Exercise4-username.md`. Both reviewers should submit their reviews in the master branch.  

# Solution Assessment #

## Peer-reviewer Information

* *name:* [Hauser] 
* *email:* [zhzzhou@ucdavis.edu]

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

### Stage 1 ###

- [ ] Perfect
- [ ] Great
- [ ] Good
- [X] Satisfactory
- [ ] Unsatisfactory

___
#### Justification ##### 
Looking at the code logic, the code should work well to implement blocking replies, the blocking will reply based on the RechargeRate after the set ReachargeDelay. However, due to a problem in the Laboratory scenario "The associated script can not be loaded." I was unable to do a normal run to test if the shield return was successful. When I add the ShieldFactory script to the scene, I can see that the shield slowly returns to its original size, but the healthbar doesn't react.
___
### Stage 2 ###

- [X] Perfect
- [ ] Great
- [ ] Good
- [ ] Satisfactory
- [ ] Unsatisfactory

___
#### Justification ##### 
I apologize that I'm not very good at running your scene. Code-wise, this part of the functionality is well implemented, experimentally I didn't succeed in changing the type of shield, but by being in the initial shield and different projectiles does reflect the success of this part of your code.

___
### Stage 3 ###

- [ ] Perfect
- [X] Great
- [ ] Good
- [ ] Satisfactory
- [ ] Unsatisfactory

___
#### Justification ##### 
The code does a good job of implementing the requested functionality, but there are two more very minor bugs, the color of the shield doesn't change depending on the type, and the position of the projectile generation is a little bit off from where it was originally, and the second issue could be a problem when I was setting up your script, also whenever I manually fire the projectile a scrolling text with 0 damage appears before the real damage.

___
### Stage 4 ###

- [ ] Perfect
- [ ] Great
- [X] Good
- [ ] Satisfactory
- [ ] Unsatisfactory

___
#### Justification ##### 
Write Justification here.
I'm sorry I didn't find a way to run this part either, but I'm looking at the code and I think your code meets most of the requirements. But your code for detecting whether a projectile has fired or not via a boolean value is slightly problematic because the projectile still has a recharge and flight time, so your code may cause the projectile to not spawn and fire properly. The code looks good on the random projectile generation as well as the number of randomizations.
___
# Code Style #


### Description ###
Check the scripts to see if the student code adheres to the dotnet style guide.

If sections do not adhere to the style guide, please peramlink the line of code from Github and justify why the line of code has not followed the style guide.

It should look something like this:

* [description of infraction](https://github.com/dr-jam/ECS189L) - this is the justification.

Please refer to the first code review template on how to do a permalink.


#### Style Guide Infractions ####
Local variables should use camelCase. Count, Timer and some other local variables use PascalCase.
https://github.com/ensemble-ai/exercise-4-factory-pattern-dt89eor/blob/3edd5f57369a520406d2a719aa3ee28162eaf7a8/Aegis/Assets/Scripts/TestFactory.cs#L27
https://github.com/ensemble-ai/exercise-4-factory-pattern-dt89eor/blob/3edd5f57369a520406d2a719aa3ee28162eaf7a8/Aegis/Assets/Scripts/TestFactory.cs#L47
https://github.com/ensemble-ai/exercise-4-factory-pattern-dt89eor/blob/3edd5f57369a520406d2a719aa3ee28162eaf7a8/Aegis/Assets/Scripts/ProjectileFactory.cs#L18-L19
There maybe need more comment to explain the code, since this project is more open than others.
https://github.com/ensemble-ai/exercise-4-factory-pattern-dt89eor/blob/3edd5f57369a520406d2a719aa3ee28162eaf7a8/Aegis/Assets/Scripts/ShieldFactory.cs#L6-L78
___

# Best Practices #

### Description ###
Overall the code is in line with code style requirements, the code is also clearly written, some of the code may need more comments to introduce, overall very well written.
the comment is very good explain the key step of the code. And I like the use of 2D array to keep the damage table with clear comment.
https://github.com/ensemble-ai/exercise-4-factory-pattern-dt89eor/blob/3edd5f57369a520406d2a719aa3ee28162eaf7a8/Aegis/Assets/Scripts/DamageEngine.cs#L11-L28
