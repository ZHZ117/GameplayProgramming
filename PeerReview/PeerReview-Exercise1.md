# Code Review for Programming Exercise 1 #
## Description ##

For this assignment, you will be giving feedback on the completeness of Exercise 1.  To do so, we will be giving you a rubric to provide feedback on. For the feedback, please provide positive criticism and suggestions on how to fix segments of code.

You only need to review code modified or created by the student you are reviewing. You do not have to review the code and project files that were given out by the instructor.

Abusive or hateful language or comments will not be tolerated and will result in a grade penalty or be considered a breach of the UC Davis Code of Academic Conduct.

If there are any questions at any point, please email the TA.

## Due Date and Submission Information ##
See the official course schedule for due date.

A successful submission should consist of a copy of this markdown document template that is modified with your peer-review. The file name should be the same as in the template: PeerReview-Exercise1.md. You also need to include your name and email address in the Peer-reviewer Information section below. This review document should be placed into the base folder of the repo you are reviewing in the master branch. This branch should be on the origin of the repository you are reviewing.

If you are in the rare situation where there are two peer-reviewers on a single repository, append your UC Davis user name before the extension of your review file. An example: PeerReview-Exercise1-username.md. Both reviewers should submit their reviews in the master branch.  

## Solution Assessment ##

## Peer-reviewer Information

* *name:* [Hauser Zhou] 
* *email:* [zhzzhou@ucdavis.edu]

### Description ###

To assess the solution, you will be choosing ONE choice from unsatisfactory, satisfactory, good, great, or perfect. Place an x character inside of the square braces next to the appropriate label.

The following are the criteria by which you should assess your peer's solution of the exercise's stages.

#### Perfect #### 
    Cannot find any flaws concerning the prompt. Perfectly satisfied all stage objectives.

#### Great ####
    Minor flaws in one or two objectives. 

#### Good #####
    A major flaw and some minor flaws.

#### Satisfactory ####
    A couple of major flaws. Heading towards a solution, however, did not fully realize the solution.

#### Unsatisfactory ####
    Partial work, but not really converging to a solution. Pervasive major flaws. Objective largely unmet.


### Stage 1 ###

- [x] Perfect
- [ ] Great
- [ ] Good
- [ ] Satisfactory
- [ ] Unsatisfactory

#### Justification ##### 
The Captain can move right with the same speed as moving left. And the Captain is facing the correct direction during both left and right movement.

### Stage 2 ###

- [x] Perfect
- [ ] Great
- [ ] Good
- [ ] Satisfactory
- [ ] Unsatisfactory

#### Justification ##### 
The three working patterns are working as required. The instance can be produced in the required time range. The item produced on the side of the pirate as the code comment says. If the item produced is not mandatory, all requirements for stage 2 are met.

### Stage 3 ###

- [ ] Perfect
- [ ] Great
- [x] Good
- [ ] Satisfactory
- [ ] Unsatisfactory

#### justification ##### 
The Motivate function randomly picks a working speed from slow, normal and assigns it to the pirate. A major flaw is the [random range is set from 1 to 3](https://github.com/ensemble-ai/exercise-1-command-pattern-SerpentSnek/blob/286c3a462164cb8f87b52438ef9a135aa170ceb2/Captain/Assets/Scripts/PirateController.cs#L33). And the switch case is 1,2,3. In that case the case 3 is not in the range, so the Motivate function can't choose the fast working speed.

### Stage 4 ###

- [ ] Perfect
- [x] Great
- [ ] Good
- [ ] Satisfactory
- [ ] Unsatisfactory

#### justification ##### 
As code says, the student implements an infinitely jump for the captain. The function works well in the first scene, the mushroom forest, where the captain can jump infinitely. But there is a minor flaw for the second and third scene, the captain will hit the ceiling of the map. The implementation is good, if it can detect the ceiling of the map then transport into the other map, that will be better.

## Code Style ##

### Description ###
Check the scripts to see if the student code follows the .Net style guide.

If sections don't adhere to the style guide, please permalink the line of code from GitHub and justify why the line of code has infractions of the style guide.

It should look something like this:

* [description of infraction](https://github.com/dr-jam/ECS189L) - this is the justification.

Here is an example of the permalink drop-down on GitHub.

![Permalink option](../images/permalink_example.png)

Here is another example as well.

* [I go to Github and look at the ICommand script in the ECS189L repo!](https://github.com/dr-jam/ECS189L/blob/1618376092e85ffd63d3af9d9dcc1f2078df2170/Projects/CommandPatternExample/Assets/Scripts/ICommand.cs#L5)

### Code Style Review ###

#### Style Guide Infractions ####
Overall, students followed the code guidelines well. And used a lot of comments to explain the code, making the whole code very readable. There is just a small infraction about the static fields naming. 
[The jumpForce field should use camelCase, but since it is static, it should use PascalCase, i.e. JumpForce.](https://github.com/ensemble-ai/exercise-1-command-pattern-SerpentSnek/blob/286c3a462164cb8f87b52438ef9a135aa170ceb2/Captain/Assets/Scripts/MoveCharacterUp.cs#L17)
#### Style Guide Exemplars ####

## Best Practices ##

### Description ###

If the student has followed best practices (Unity coding conventions from the StyleGuides document), then feel free to point at these segments of code as examples. 

If the student has breached the best practices and has done something that should be noted, please add the infracture.

This should be similar to the Code Style justification.

* [description of infraction](https://github.com/dr-jam/ECS189L) - this is the justification.

### Best Practices Review ###
Basically, the code fits the code style perfectly, much better than the work I did to adapt it for the first time. The code style is clean and readable.
#### Best Practices Infractions ####

#### Best Practices Exemplars ####

The field rigidBody uses camelCase, which conforms to the naming convention for non-static private fields.[Code](
https://github.com/ensemble-ai/exercise-1-command-pattern-SerpentSnek/blob/286c3a462164cb8f87b52438ef9a135aa170ceb2/Captain/Assets/Scripts/MoveCharacterUp.cs#L23)

The use of Swtich and the lines of code are very clean and easy to read. And the brackets get their own line as it is a C# convention.[Code](
https://github.com/ensemble-ai/exercise-1-command-pattern-SerpentSnek/blob/286c3a462164cb8f87b52438ef9a135aa170ceb2/Captain/Assets/Scripts/PirateController.cs#L33C9-L44C10)

The comments explain the code well.[Code](
https://github.com/ensemble-ai/exercise-1-command-pattern-SerpentSnek/blob/286c3a462164cb8f87b52438ef9a135aa170ceb2/Captain/Assets/Scripts/FastWorkerPirateCommand.cs#L14C9-L23C58)
