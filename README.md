# Git Assignment - Building a branching model

![image](https://user-images.githubusercontent.com/123494344/214637468-d4d7f284-ecb4-43c1-b419-dff57ee12090.png)
<p align = "center">
Fig.1 - History of Commits in my Repository.
</p>

It contains 5 Branches - 
- Production (master)
- Integration
- HotFix 
- Feature1 
- Feature2
#### Step - 1
- I set up the Github repository and cloned it locally. then after that, Main Branch, a branching off of HotFix and Integration Branch, was developed.
#### Step - 2
- Making Feature1 and Feature2 Branches from the Integration Branch. Adding some changes then adding 2 reviewers Who made merging the pull request to integration.
#### Step - 3
- Change and commit in Feature1 in Local Environment. However, we now seek to act before the merge that occurred in the origin/Feature2 Therefore, we run the `git pull —rebase` command to rebase. This means that when we pull from the remote, our local commit will come first.
#### Step - 4
- Production(main) and HotFix branches now include changes from the Integration branch.
#### Step - 5
- Changes was developed on the HotFix branch and integrated into the Integration and Production branch.
#### Step - 6
- Feature1, Feature2, and HotFix branches were ultimately deleted after completing the aforementioned processes.
### Commands - 
- `git clone`
- `git log --online`
- `git push`
- `git pull`
- `git checkout`
- `git branch`
- `git checkout -d [branch name]`
- `git checkout -b [branch name]`

