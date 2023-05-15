# actions-branch-name-fail

A github actions workflow to check the current branch name, validate it according to a defined regex pattern in order to have the pull request allowed to be merged.

## To use it for your own workflow:

### Step 1

Open .github > workflows > workflow.yml and make changes to the regex pattern according to your requirements.

### Step 2:

Push the workflow in your own repo.

### Step 3:

Go to repo settings > Branches > Add branch rule >

Branch name pattern: (\*, or whatever you want it to be)

:white_check_mark: Require status checks to pass before merging >
Select the workflow you just pushed.
