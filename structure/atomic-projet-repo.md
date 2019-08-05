# Atomic Project Repo Structure
- should follow the [Project Directory Structure](TODO: link)
- repo name should be specific to make it uniquely identifiable and descriptive
    - must be prefixed by
        - `atomic-`: a standalone project that can be completed without requiring other projects to setup or conclude 
    - examples:
        - terrible: `atomic-api-project`
            - too generic to uniquely identify 
        - bad: `atomic-graphql-api-project`
            - does not adequately describe the project
        - good: `atomic-js-graphql-starter-api`
            - describes the language used `js`
            - describes the technology used `graphql api`
            - describes the scope `starter`
```

- should include the `6x6 Atomic Project Boilerplate` under the Title of the project description `README.md`


```sh
repo/
  README.md <-- put Atomic Project Boilerplate in here

  project/ <-- empty / boilerplate directory where project source should go
    .gitignore <-- (or language equivalent) to prevent risky or inefficient commits
    README.md <-- author editable project description (can be empty or a template specific to the project)
  
    [other boilerplate can go in here]
  
    DO NOT initialize a git repo in the project/ directory
```

# 6x6 Atomic Project Boilerplate
- link to 6x6 org / homepage
    - short description of what a 6x6 and a 6x6 project is
- links to original project repo
- describe how the issues / discussion area for the project works