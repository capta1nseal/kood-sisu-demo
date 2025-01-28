# Version control



## Branches 

To summarize the main idea behind the branches is: 
You normally want to create a new branch when starting to develop a new feature for the application. This is to prevent any modifications (possibly leading to a stack of errors) from being made to the product that is currently working. 
For example you don't want to commit your changes straight to a released application unless you are finished with the development of the feature you are/were working on.


## Pull requests

To put it simply: Pull requests are designed to make merging safer. Also to make the project control easier.

The process in a nutshell:

> Quote:
>- **Fork Main Repository and Create a Local Clone**. First, the developer creates a fork of the main repository, and then clones this onto their local machine.
>- **Make Needed Changes Locally.** The developer then is able to make their needed changes or additions to the code whether they are working on resolving an issue or new feature.
>- **Push Local Changes to Forked Repository.** Once the developer has completed and tested the new code changes, they push these changes back to the forked repository they created in step one.
>- **Make a Pull Request.** This is where the actual pull request takes place! After requesting a pull request, the main repository maintainer is alerted for review. The maintainer will then review the work done in the developer’s forked repository, and then make any comments or request any edits that need to be made for approval.
>- Any edits are then sent back to the developer for additional commits (changes to code) that may be needed.
>- If no edits are needed, the pull request is approved by the maintainer.
>- **Merge with Main Project.** Once the repository maintainer has approved a pull request, the developer’s new updates in the forked repository are merged with the main project repository. The product is then updated with the new feature or bug fix, and can now be viewed by end users.

[Source](https://www.pagerduty.com/resources/learn/what-is-a-pull-request/#:~:text=A%20pull%20request%20%E2%80%93%20also%20referred,with%20the%20main%20project%20repository.) and more about **pull request**
