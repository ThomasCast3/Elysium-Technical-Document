---
title: Code
sidebar_position: 1
---

# Code

## Naming conventions

<div>
    In the project we decided to use camelcase for folder names, file names and variables. Except that folders will start with an uppercase letter while files and variables with a lowercase one.
</div>

## Architecture

### Front

<div>
    We chose to use an MVC architecture and we therefore divided the front into three large files:
        - component (for the modes)
        - screen (for the view) 
        - services (for the controller)
</div>

### Back

<div>
    Likewise for the back, we therefore have:
        - model (for the data structure) 
        - routes (for rendering views) 
        - controller (to retrieve or create data)
</div>

## Github

<div>
    The Github part is divided into two parts: new features and merge requests.
    </div>

### new features

<div>
    For each new feature the developer will have to create a branch with the naming convention: feature/name_of_the_feature/specificity.  
    Only one person at a time per branch to avoid merge problems.
</div>

### merge requests

<div>
    Once the features are finished, the developer, after having all push on his branch, must make a merge request which another developer must accept after reviewing the code to ensure that there are no problems.
</div>
