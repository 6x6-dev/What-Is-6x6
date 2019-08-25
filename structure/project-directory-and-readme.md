# Project Directory Structure

```sh
README.md <-- 6x6 project description, should not be edited by author
project/ <-- empty / boilerplate directory where project source should go
  .gitignore <-- (or language equivalent) to prevent risky or inefficient commits
  README.md <-- author editable project description (can be empty or a template specific to the project)
  
  [other boilerplate can go in here]
  
  DO NOT initialize a git repo in the project/ directory
```

# Project `README.md` Structure
- remember that each project should be scoped to take one week (10-15 hours) to complete
- for something more advanced you can provide some starter code / boilerplate to fit within that timespan

# Project Title

## Contributors
- `[@username](<link to github profile>)`
- first one is initial author, contributors who edit are added chronologically afterwards

## Related
- list of projects / tracks that this project is related to
- related by similar topics / technologies
- does not have to be exhaustive or maintained, just a reference for when a project maintainer can remember to include
- helps to organize tracks or for members putting together their own tracks
- **must be included for `sequential` projects in a track`**

## Introduction
- introduction and context about the technology the project is based around
- suggestions
    - background / history of the technology
    - who / where / how the technology / type of project is used
    - important vocabulary and introductory definitions

## Learning Goals
- topics that will be covered in the project

### Learning Links
- links to learning resources
- links to commonly used libs 

## Specifications
- user story styled specifications
- should try to simulate the specs received by a project manager in a real job

### required
- minimum required specs
- should aim to be specific without mentioning actual implementation details (how to do something, what libs to use etc)

### bonus
- additional specs that the author can implement above the minimum
- can be more vague 

## Project Directory
- discuss what is included in the `/project` directory
    - author editable `project/README.md`
    - what is included in the `.gitignore` (or language equivalent) and why 
- if boilerplate discuss what files / config / libs are included

## Review Checklist
- granular, objective, minimum requirements the project needs to provide at minimum
- used by the author to guide the completion of the project
- used by the assigned reviewer to determine if the project is eligibile for
    - a scheduled pair-review meeting
    - submission into the weekly 6x6-group project review chat
- must be provable in a submitted project without inspecting the code itself