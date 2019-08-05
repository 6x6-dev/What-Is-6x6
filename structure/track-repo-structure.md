# Track Repo Structure
- repo name should be specific without being too long to make it identifiable and unique
    - must be prefixed by `track-`
    - examples:
        - terrible: `atomic-api-project`
            - too generic to uniquely identify 
        - bad: `atomic-graphql-api-project`
            - does not adequately describe the project
        - good: `atomic-js-graphql-starter-api`
            - describes the language used `js`
            - describes the technology used `graphql api`
            - describes the scope `starter`
- directories
    - each project in the track should be put in a `week-#/` directory to represent its position in the track schedule
    - for including `atomic` projects in the track see [Including Atomic Projects](#Including-Atomic-Projects)
    - for adding `sequential` projects to the track see [Including Sequential Projects](#Including-Sequential-Projects) 

```sh
README.md <-- 6x6 track description (should not be edited by author)

week-1/
week-2/
week-3/
week-4/
week-5/
week-6/
```

- each `week-#/` directory (whether `atomic` or `sequential`) should follow the [6x6 Project Structure](TODO: link)

# Including Atomic Projects
- steps to take when creating or editing the projects in a track repo
- should be used when adding an `atomic` project to a track
- perform [a shallow clone](https://git-scm.com/docs/git-clone#Documentation/git-clone.txt---depthltdepthgt) of the project repo `master` branch and rename it `week-#`
    - shallow so its faster and gets the latest project content 

```sh
# issue the command from inside the track repo

$ git clone <project-repo-uri> --depth 1 week-<#>
```

```sh
# example to clone the project-name repo into the directory week-2/

$ git clone https://github.com/6x6-dev/project-name.git --depth 1 week-2
```

- remove the `.git` directory (git history) from the `week-<#>/` directory
    - prevents confusion where author commits are made to a project repo rather than to the forked track repo
    - removes the remote url to prevent confusing pushes

```sh
# issue the command from inside the week-#/ project directory

$ cd week-<#>/

$ rm -r .git/
```

```sh
# example for the directory week-2/

$ cd week-2/

$ rm -r .git/

# shorthand

$ rm -r week-2/.git/
```

- add / update the `Project Schedule - Week N` entry about the added project  
- commit the changes to the track repo

# 6x6 Track Boilerplate
- link to 6x6 org / homepage
    - short description of what 6x6 is
- general description of how a 6x6 track works
    - how the project schedule works
    - project pair-review meetings 
- links to original track repo
- describe how the issues / discussion area for the track works

# 6x6 Track `README.md` Structure

# Track Title

## What is a 6x6 Track?
- copy over the `6x6 Track Boilerplate` here

## Contributors
- `[@username](<link to github profile>)`
- first one is initial author, contributors who edit are added chronologically afterwards

## Introduction
- introduction and context about the technology the track is based around
- suggestions
    - background / history of the technology
    - who / where / how the technology / type of project is used
    - important vocabulary and introductory definitions

## Learning Goals
- describe the learning goals of the track
- suggestions
    -  

### Learning Links
- links to learning resources
- links to commonly used libs 

### Week N
- repeat for each week in the track
- describe how this week's project relates to the learning goals of the track


## Completion Record
- single line records for every 6x6 member who completes the track
- grouped by the season the track was run
- although the source track repo projects and content may change over time the member-forked repos (linked in the record) will always be consistent with what was completed by that member
- format
    - `6x6 Season: MM/dd/YY-MM/dd-YY` 
        - `[@username](<link to github profile>) - [completed track repo](<link to forked track repo>)` 