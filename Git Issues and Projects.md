![Git Logo](/images/logos/git_logo.png)

# Git Issue Tracking
## Issues
GitHub's method of tracking tasks for an existing repository, and its respective project(s), is known as Issues.  Issues can be used to track not only tasks, but enhancement requests, questions, and bugs as well.

### Adding an Issue
Issues can be added within the desired repository by clicking on the plus (+) icon in the menu bar and selecting "New Issue" or by navigating to the "Issues" section of the repository and clicking the "New Issue" button.

![Add Issue](/images/add_issue.png)

### Creating a Simple Issue
At minimum, an issue should have a title and a descriptive comment. The "Submit new issue" button saves and submits the issue.

![Simple Issue](/images/create_simple_issue.png)

### Creating a Descriptive Issue
During issue creation, additional information can be added to the issue which can save steps and time in the future. 

#### Assignees
Clicking on the gear icon in the "Assignees" section and allows for the selection and assignment of assignees to the issue.

#### Labels
Issues can be further classified with the use of labels. Labels also allow for enhanced search capabilities since they add an extra layer of metadata to existing issues.  Clicking on the gear icon in the "Labels" section displays a list of all labels which are available for selection.

![Advanced Issue](/images/create_advanced_issue.png)

At the time of this writing, the list of labels available within GitHub are shown below.

Label | Description
-|-
bug | Something isnt' working
documentation | Improvements or additions to documentation
duplicate | This issue or pull request already exists
enhancement | New feature or request
good first issue | Good for newcomers
help wanted | Extra attention is needed
invalid | This doesn't seem right
question | Further information is requested
wontfix | This will not be worked on

##### Adding/Editing/Deleting Labels
The default list of labels can be changed by navigating to the "Issues" section of the repository and clicking the "Labels" button.

![Labels](/images/labels.png)

### Existing Issues
Issues which have been created can always be commented upon and edited as needed.

![Existing Issue](/images/existing_issue.png)

### Configuring Issue Templates (Optional)
An issue template provides a standardized format for contributors to create and track issues within a repository.

#### Creating Issue Templates
Clicking the "Settings" section of the repository begins the launches the Settings screen which is used to creat issue templates.

![Repo Settings](/images/repo_settings.png)

Scrolling down in the Settings page leads to the "Features" section. Within the "Features" section, clicking the "Set up template" button launches the template screen.

![Setup Template](/images/setup_templates.png)

Clicking the "Preview and edit" button displays the actual layout of the template and also allows for changes to be made.

![Preview Template](/images/preview_template.png)

To proceed with editing, the pencil icon can be clicked.

![Edit Template](/images/edit_template.png)

Once editing is complete, clicking the "Propose changes" button launches a commit changes set of controls.

![Propose Changes](/images/propose_changes.png)

A commit message and extended commit message should be provided prior to clicking the "Commit changes" button which will finalize and save the template.

![Commit Changes](/images/commit_changes.png)

The next time an issue is to be created within the repository, a new interface will appear which will launch the newly created template. Clicking the "Get started" button launches the tempate.

![Get Started](/images/get_started.png)

The template allows for the standarized input of information as designed.

![Issue Template](/images/issue_template.png)

## Projects
Projects offer a containerized approach to manage development and issue tracking throughout a repository. Project boards also help with the organizationa and prioritization of outstanding work. They are a visual method in comprehending and communicating the status of all issues, tasks, requests, development within a project. 

### Adding a Project
Projects can be added within the desired repository by navigating to the "Projects" section of the repository and clicking the "Create a Project" button.

![Add Project](/images/add_project.png)

The "Add template" drop-down control can be used to select a template.

![Add Template](/images/add_template_select.png)

### Creating a New Project
At minimum, an project should have a Project board name and a description.  To save additional steps in the future, a Project template can also be added to configure the layout and behavior of the project board. The "Submit new issue" button saves and submits the issue.

![Create Project](/images/create_project.png)

At the time of this writing, the list of Project templates available within GitHub are shown below.

Template&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;|Description
-|-
None|Start from scratch with a completely blank project board. You can add columns and configure automation settings yourself.
Basic kanban|Basic kanban-style board with colums for "To do", "In progress", and "Done".
Automated kanban|Kanban-styule board with built-in triggers to automatically move issues and pull requests across "To do", "In progress", and "Done" columns.
Automated kanban with reviews|Everything included in the Automated kanban template with additional triggers for pull requests reviews.
Bug triage|Triage and prioritize bugs with colums for "To do", "High priority", "Low priority", and "Closed".

## Add Existing Issue to Project
Issues which have been already created can be added to an existing project using different methods.

### Method 1: From Within the Project Board
An issue can be added whilst viewing the project board by clicking on the "+ Add Cards" entry and then dragging and dropping the desired issue into a project board column.

![Add Cards 1](/images/add_cards1.png)
![Add Cards 2](/images/add_cards2.png)

### Method 2: From Within the Issue
Issues can be added directly to an existing project from within the issue itself. Clicking on the gear icon in the "Projects" section displays a list of all projects which are available for selection. 

Once a project has been selected, the issue is then assigned to that project. 

![Add Issue to Project 1](/images/add_issue_to_project1.png)

The "Awaiting triage" drop down menu further classifies the issue and placed it into the proper project column of either "To do", "In progress", or "Done".

![Add Issue to Project 2](/images/add_issue_to_project2.png)

## Creating New Issues from within a Project
New issues can be generated directly from the project board. This is a two step process and requires that a note be created which can be then converted into an issue.

### Step 1: Creating a Note
From within a column of the project board, clicking on the plus icon (+) generates a new note. This note can then be populated with text. Clicking the "Add" button saves the note.

![Add Note to Project](/images/add_note.png)

### Step 2: Converting a Note to an Issue
A note can be converted to an issue by clicking on the ellipses (...) in the upper right corner of a note and then selecting the "Convert to issue" menu entry.

![Convert Note to Issue 1](/images/convert_to_issue1.png)

A final dialog box will appear which allows for the note to be editing before it is converted to an issue.  Clicking the "Convert to Issue" button finalizes the changes and converts the note to an issue.

![Convert Note to Issue 2](/images/convert_to_issue2.png)

### Step 3: Assigning the Issue and Adding Labels
Assignees and Labels should be added to the newly created issue from within the "Issues" section of the repository.

![Add Issue](/images/add_assignee_labels_to_issue.png)

## Managing the Project Board
Each time an issue changes status, the project board should be updated accordingly. The project board can be updated manually or automatically (based on preset triggers). 

### Manually Updating the Project Board
Issues, notes, and other objects in the project board can be moved between columns by dragging and dropping them from their current location to their desired location.

### Automatically Updating the Project Board
Clicking on the elipses (...) in the upper right corner of each column and selecting the "Manage automation" menu entry allows for triggers to be set.  

![Manage Automation](/images/manage_automation.png)

Each column as preset (default) triggers which are relevant to the column itself.

#### "To do" Column Preset Triggers
Object|Action|Description
-|-|-
Issue|Newly added|Issues will automatically move here when added to this project.
Issue|Reopened|If a closed issue in this project reopens,it will automatically move here.
Pull Request|Newly added|Pull Requests will automatically move here when added to this project.
Pull Request|Reopened|If a closed pull request in this project reopens,it will automatically move here.

#### "In Progress" Column Preset Triggers
Object|Action|Description
-|-|-
Issue|Reopened|If a closed issue in this project reopens,it will automatically move here.
Pull Request|Newly added|Pull Requests will automatically move here when added to this project.
Pull Request|Reopened|If a closed pull request in this project reopens,it will automatically move here.
Pull Request|Approved by reviewer|Pull requests in this project will automatically move here when they meet the minimum number of required approving reviews. Recommended when another column has the Pending approval by reviewer automation enabled. 
Pull Request|Pending approval by reviewer|Pull requests in this project will automatically move here when a reviewer requests changes, or it no longer meets the minimum number of required approving reviews. Recommended when another column has the Approved by reviewer automation enabled.

#### "Done" Column Preset Triggers
Object|Action|Description
-|-|-
Issue|Closed|If an open issue in this project is closed, it will automatically move here. 
Pull Request|Merged|If an open pull request in this project is merged, it will automatically move here. 
Pull Request|Closed with unmerged commits|If an open pull request in this project is closed with unmerged commits, it will automatically move here.

## Working on Issues
Now that this repository has 2 open issues, work can begin on addressing these issues and ultimately resolving them.

### Performing a Git Clone
The online repository should be cloned locally to create a local repository on the PC where the issues are to be resolved.

```bash
# git clone git@github.com:codeHaiku22/testRepository.git
```

### Updating the Project Board
If automation has not been enabled via triggers, the current issue can be dragged and dropped from the "To do" to the "In progress" column.

![Move Issue to In Progress](/images/all_issues_todo_inprogress.png)

### Checking Out Code and Creating a New Branch
In order to work on the first issue, a new branch named "issue1" will be created in the local repository for the sole purpose of addressing the first issue.

```bash
# git checkout -b issue1
```

### Modifying Objects
The first issue (Issue #1) stated that: 
> "*The README.md file should be more welcoming for people who view this project.*"

So, the README.md file can be modified to be more welcoming.

```bash
# nano README.md
```

Additional text can be added to the README.md file so that it now looks like this:

> ##### testRepository
> Welcome to the testRepository.
>
>We hope that you feel welcoming here as this literally resolves our first issue: Issue #1.

### Adding the Changes for Staging
After the README.md file has been changed, the changes made should be added so that they are staged for a push to a new branch.

```bash
# git add .
```

### Commiting the Changes for Staging and Automatically Linking to the Issue
The README.file and it's respective changes are now ready to be committed to the push along with a message indicating what was changed.

```bash
# git commit -m "Made README.md more welcoming [issue 1] Closes #1"
```

***NOTE:** By adding the "Closes #1" keyword and issue number to the message of the commit, this commit and its subsequent pull request are automatically linked and poised to close Issue #1.*

*Any of the following keywords can be used to close an issue:*
- *close*
- *closes*
- *closed*
- *fix*
- *fixes*
- *fixed*
- *resolve*
- *resolves*
- *resolved* 

#### Manually Linking Issues and Pull Requests
There are a few methods of manually linking issues with pull requests.

##### Method 1: Link Issue from Pull Request
An issue can be directly linked to a pull request from within the pull request itself.

![Link Issue From Pull Request](/images/link_issue_from_pull_request.png)

##### Method 2: Link Pull Request from Issue
A pull request can be directly linked to an issue from within the issue itself.

![Link Pull Request from Issue](/images/link_pull_request_from_issue.png)

##### Method 3: Link Pull Request from Issue within Project
A pull request can be directly linked to an issue from within a project.

![Link Pull Request from Issue within Project](/images/link_pull_request_from_issue_within_project.png)

### Pushing the Changes Upstream
Finally, all changes should be pushed upstream. This will generate a new branch named "issue 1" in the online repository.  

```bash
# git push --set-upstream git@github.com:codeHaiku22/testRepository.git issue1
```

### Updating the Project Board
If automation has not been enabled via triggers, the current issue can be dragged and dropped from the "In progress" to the "Done" column.

![Move Issue to Done](/images/all_issues_todo_done.png)

***NOTE:** In addition to generating a new branch, this action also generates a pull request within the online repository.*

![Pull Request](/images/pull_request.png)

### Compare & Pull Request
The pull request that was automatically generated in the online repository with the last commit and push can now be compared by navigating to the "Pull requests" section of the repository and clicking on the "Compare & pull request" button.

![Compare and Pull Request](/images/compare_and_pull_request.png)

#### Assigning the Pull Request, Adding Labels, and Linking to a Project
Assignees and Labels should be added to the pull request. Additionally, the Projects attribute can also be used to link this pull request to the project that the issue which it seeks to resolve is associated with. Once complete, the "Create pull request" button can be clicked to complete the process.

![Edit Pull Request](/images/edit_pull_request.png)

### Merge Pull Request into Master Branch

#### Using GitHub
Once all details of the pull request have been confirmed along with the validity of the pull request, the pull request can then be merged by clicking on the "Merge pull request" button.  This also closes the pull request.

![Merge Pull Request](/images/merge_pull_request.png)

The merge will need to be confirmed by clicking on the "Confirm merge" button".

![Confirm Merge](/images/confirm_merge.png)

#### Using BASH
A merge can also be performed using the git command. First, the branch into which the merge will occur should be checked out (switched to). Then a merge can be made between the issue branch and the master branch.

```bash
# git checkout master
# git merge issue1
```

***NOTE:** This automatically closes the issue as well.*

#### Manually Closing Issues
There are a few methods of manually closing issues.

##### Method #1: Close Issue from within Project
An issue can be closed from within a project.

![Close Issue from Project](/images/close_issue_from_project_board.png)

##### Method #2: Close Issue from Issues
An issue can be closed from the "Issues" section of a repository.

![Close Issue from Issues](/images/close_issue_from_issues.png)

##### Method #3: Close Issue from within the Issue Itself
An issue can be closed from within the issue itself.

![Close Issue from within Issue](/images/close_issue_from_within_issue.png)

### Cleaning Up by Deleting the Branch

#### Using GitHub
The branch which was created to resolve Issue #1 is no longer needed and can now be deleted. After the pull request has been successfully merged and closed, the branch which generated the pull request can be delted by clicking on the "Delete branch" button.

![Delete Branch](/images/delete_branch.png)

#### Using BASH
A delete can also be performed using the git command. 

```bash
# git branch -d issue1
```
