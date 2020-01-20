# Code Review 



# Definition
Code review is a software quality assurance activity in which one or several humans check a program mainly by viewing and reading parts of its source code, and they do so after implementation or as an interruption of implementation. At least one of the humans must not be the code's author. The humans performing the checking, excluding the author, are called "reviewers".

# WHY ?

 - **Better code quality** - improve internal code quality and maintainability (readability, uniformity, understandability, ...)
 - **Finding defects** - improve quality regarding external aspects, especially correctness, but also find performance problems, security vulnerabilities, injected malware, ... The earlier the bugs are detected the cheaper they are to fix.
 - **Learning/Knowledge transfer** - help in transferring knowledge about the codebase, solution approaches, expectations regarding quality, etc; both to the reviewers as well as to the author. The author gains additional insight on how to improve their code. the reviewer can learn new techniques and ideas from the code they're reviewing
 - **Finding better solutions** -   generate ideas for new and better solutions and ideas that transcend the specific code at hand.
 - **Complying to QA guidelines** -   Code reviews are mandatory in some contexts, e.g., air traffic software.
 - **Increase sense of mutual responsibility** -   increase a sense of collective code ownership and solidarity.

# Types

Pre- and post-commit review concepts are quite self-explanatory:

 - **Pre-commit** is a type of review when the code is reviewed before it goes to the main repository of the version control system.
 - **Post-commit** review takes place after the code has been submitted to the public repository.

## Pre-Commit Reviews
|Pros  |Cons  |
|--|--|
| A developer  can  work  and  commit  changes  to  the  repository  continuously |  Increased  chances  of  poor  code  making  it  into  the  main  repository, hence  affecting  the  entire  team's  work|
Other team  members  see  the  code  changes  and  can alter their  work  accordingly|When  defects  are  found, it  may  take a while  for  the  developer  to  switch back  to  the  module  they  had  been  working on|
|Some  changes  can  be  complex  and  require multiple steps, so it's  convenient  to  examine  each  step  separately after all of  them  have  been  committed|


## Post Commit Reviews

| Pros |Cons  |
|--|--|
| A developer  can  work  and  commit  changes  to  the  repository  continuously | Increased  chances  of  poor  code  making  it  into  the  main  repository, hence  affecting  the  entire  team's  work |
Other team  members  see  the  code  changes  and  can alter their  work  accordingly  | When  defects  are  found, it  may  take a while  for  the  developer  to  switch back  to  the  module  they  had  been  working on | 
Some  changes  can  be  complex  and  require multiple steps, so it's  convenient  to  examine  each  step  separately after all of  them  have  been  committed   |

## Which one?
Depends on the particular project conditions.

 - Branching strategy
 - Developer profiles


# Good Practises

 - Committing  early  and  often. It's  far  easier  to  run multiple small  reviews  than a single  huge  one
 - Encouraging  developers  to  produce  well-documented  code  before  review  is  issued
