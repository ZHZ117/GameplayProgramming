# Peer-Review for Programming Exercise 2 #

## Description ##

For this assignment, you will be giving feedback on the completeness of assignment two: Obscura. To do so, we will give you a rubric to provide feedback. Please give positive criticism and suggestions on how to fix segments of code.

You only need to review code modified or created by the student you are reviewing. You do not have to check the code and project files that the instructor gave out.

Abusive or hateful language or comments will not be tolerated and will result in a grade penalty or be considered a breach of the UC Davis Code of Academic Conduct.

If there are any questions at any point, please email the TA.   

## Due Date and Submission Information
See the official course schedule for due date.

A successful submission should consist of a copy of this markdown document template that is modified with your peer review. This review document should be placed into the base folder of the repo you are reviewing in the master branch. The file name should be the same as in the template: `CodeReview-Exercise2.md`. You must also include your name and email address in the `Peer-reviewer Information` section below.

If you are in a rare situation where two peer-reviewers are on a single repository, append your UC Davis user name before the extension of your review file. An example: `CodeReview-Exercise2-username.md`. Both reviewers should submit their reviews in the master branch.  

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

### Stage 1 ###

- [X] Perfect
- [ ] Great
- [ ] Good
- [ ] Satisfactory
- [ ] Unsatisfactory

___
#### Justification ##### 
The code works perfectly in any direction and speed. And the 5*5 cross is perfectly drawn on the screen. The drawing code is very concise, which is way better than what I did( 9 positions change).

___
### Stage 2 ###

- [X] Perfect
- [ ] Great
- [ ] Good
- [ ] Satisfactory
- [ ] Unsatisfactory

___
#### Justification ##### 
The code prefect drew the box and constrained the target to move in the box, the auto scroll part is also perfect. 
Just one little thing I want to share with you is that I think the target should move at the same speed of the auto scroll camera when the target is idle. Because I saw it in the discussion, and I think it is reasonable since it is just how 2D games simulate the jet fly moving. If I'm the player I may not want the camera to chase me when the target is idle which doesn’t mean the jet is static in the air.
But this is just a friendly suggestion, you did a very great job for the stage2 requirement.

### Stage 3 ###

- [X] Perfect
- [ ] Great
- [ ] Good
- [ ] Satisfactory
- [ ] Unsatisfactory

___
#### Justification ##### 
The third part three is also perfect, the camera does follow the target very smoothly. And I saw you used the MovementControllerLib.KeepLeash() which is great to bulid a class to help you move the camera. And all the requirements are fulfilled.
___
### Stage 4 ###

- [X] Perfect
- [ ] Great
- [ ] Good
- [ ] Satisfactory
- [ ] Unsatisfactory

___
#### Justification ##### 
The code works perfectly, and the code uses a function to avoid the large chunk of code. The requirement is all fulfilled.

___
### Stage 5 ###

- [X] Perfect
- [ ] Great
- [ ] Good
- [ ] Satisfactory
- [ ] Unsatisfactory

___
#### Justification ##### 
The code did implement a four way speed up push zone camera, the push zone has a correct speed with push ratio. For stage four the code is still well commented and concise, and all requirements are perfectly met.
___
# Code Style #


### Description ###
Check the scripts to see if the student code adheres to the dotnet style guide.

If sections do not adhere to the style guide, please peramlink the line of code from Github and justify why the line of code has not followed the style guide.

It should look something like this:

* [description of infraction](https://github.com/dr-jam/ECS189L) - this is the justification.

Please refer to the first code review template on how to do a permalink.


#### Style Guide Infractions ####
Overall, the student follow the style guide , just one litte flaw.
The constant should use 'PascalCase', so it should be Precision.
https://github.com/ensemble-ai/exercise-2-camera-controllers-xydxydxyd1/blob/fb6191870f2f800fe42ee3cfbc964ec5656dc9ce/Obscura/Assets/Scripts/TargetFocusCameraController.cs#L38


#### Style Guide Exemplars ####

___
#### Put style guide infractures ####

___

# Best Practices #

### Description ###

If the student has followed best practices (Unity coding conventions from the StyleGuides document) then feel free to point at these code segments as examplars. 

If the student has breached the best practices and has done something that should be noted, please add the infraction.


This should be similar to the Code Style justification.

#### Best Practices Infractions ####
Use the fuction to aovid fuction over 100 line of code, and it is clear and consice.
https://github.com/ensemble-ai/exercise-2-camera-controllers-xydxydxyd1/blob/fb6191870f2f800fe42ee3cfbc964ec5656dc9ce/Obscura/Assets/Scripts/TargetFocusCameraController.cs#L64C21-L64C38
https://github.com/ensemble-ai/exercise-2-camera-controllers-xydxydxyd1/blob/fb6191870f2f800fe42ee3cfbc964ec5656dc9ce/Obscura/Assets/Scripts/TargetFocusCameraController.cs#L71

Avoid the extreme length of a line of code, which I think is the most eye watering thing.
https://github.com/ensemble-ai/exercise-2-camera-controllers-xydxydxyd1/blob/fb6191870f2f800fe42ee3cfbc964ec5656dc9ce/Obscura/Assets/Scripts/FourWaySpeedupPushZoneCameraController.cs#L67

The short and clear comment for the code, and the code is pretty organized in the format.
https://github.com/ensemble-ai/exercise-2-camera-controllers-xydxydxyd1/blob/fb6191870f2f800fe42ee3cfbc964ec5656dc9ce/Obscura/Assets/Scripts/FrameAutoScrollCameraController.cs#L54C73-L54C79



#### Best Practices Exemplars ####
