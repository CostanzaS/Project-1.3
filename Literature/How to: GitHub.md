# How to use GitHub (A basic guide)

### Key reference source links and useful links

[Original GitHub tutorial](https://www.pluralsight.com/blog/software-development/github-tutorial)

[How to write on with flavored Markdown syntax on GitHub](https://guides.github.com/features/mastering-markdown/)

[Contributing guide lines](https://github.com/OliveIsLazy/Project-1.3/blob/master/CONTRIBUTING.md)

[GitHub's keyboard shortcuts](https://help.github.com/articles/using-keyboard-shortcuts/)

[GitHub youtube video guide's (playlist)](https://www.youtube.com/user/GitHubGuides/playlists)

[Creating folders in a repo](https://stackoverflow.com/questions/18773598/creating-folders-inside-github-com-repo-without-using-git)

[Moving files into a folder](https://help.github.com/articles/moving-a-file-to-a-new-location/)

[Documentation](https://guides.github.com/features/wikis/)

[Setting up a project](https://help.github.com/articles/about-project-boards/)

[What is Git?](https://git-scm.com/documentation)




### Glossary (alphabetised)

#### You may need to refer to other definitions within the glossary to understand the keyword you're looking up

*(stub)*: shorthand to say that this piece of information is incomplete or possibly inaccurate due to lack of knowledge or experience.

Branch: A clone of the master branch in question that can be freely modified without affecting the original. *(stub)*

  - The master branch is **not** a clone but the trunk of the tree, if you will.
  
Commit: Shows all the changes made from an update with a title and label.

Documentation, updated records of a repo or a project to make it more easily accessible for the uninformed.

Fork: A copy of someone else's repo to your own repo for you to edit without affecting the source. *(stub)*

Issue: An issue can be a bug report, a request for a new feature, a request for help or even a question. 

  - Issues are created with a title and a description called a label.
  
  - Red issues are issues that have been solved (closed) and green issues need fixing still (are open).
  
Projects, specific goals set for a repo to achieve.
  
Pull Request: A notification that a contributor is pushing a commit which needs reviewing before being merged.

Pulling: The master branch taking in code from a contributor.

Pushing: A contributor putting forward code they wish to be added to the master branch of the project.

Release: This is a tricky term to define, think video games that have patches and updates.
Depending on how you want to use releases, it can be either lots of small changes over time, or large differences between releases (patches and updates vs DLC).

Repository: A central location in which data is stored and managed. Repo is shorthand.

Static Website: A website where what is shown in directly coded for that site rather than accessing a server to show information.



### Understanding the UI

#### Black Tool Bar

- Icon: GitHub's homepage, appearance differs whether you're signed in or not.

- Search bar: To find new projects by repository name. Search options can be configured on the search page.

- Pull requests: Shows all pull requests relevant to you. *(stub)*

- Issues: Shows all issues relevant to you. *(stub)*

- [Marketplace](https://help.github.com/articles/about-github-marketplace/): Apps that modify GitHub. Your apps can be viewed at settings> delevoper settings

- Explore: Search for sets of repositories that have a joining theme i.e. artificial learning.

- The bell icon: Clicking on it takes you to a page showing all notifications while hovering over it shows you recent ones.

- The + dropdown menu: for creating new or importing old content i.e. repositories, issues.

- The avatar dropdown menu: regular profile settings.


#### Signing up and your Profile Page

Your account must be verified before you can use it.
Your chosen email can be hidden from public view.
Emails are used for keeping you updated about changes made to your repos or the repos you follow.
The extent your email is used can be changed in your user settings.

Your profile essentially three sections: personal information, your repos and your contributions.
There are also 5 tabs on your profile: Overview, Repos, Stars, Followers and Following.

  - Stars: GitHub's equivelant to likes
  
  - Following and followers is similar to twitter's setup.
  
This page is mostly self explanitory. Tinker around yourself if you're that interested!


#### Searching for new projects

To quickly go to the [home search page](https://github.com/search?utf8=%E2%9C%93&q=&type=), click the search bar and press enter. Or if you already have a keyword or phrase in mind, type it in and press enter (make sure the search bar doesn't have "This repository" to the left of it). *(stub)*

If you're searching for something specific, you'll be taken the a results page with basic search configuration to the left.

You can choose which of the 6 categories you want your keyphrase to check a match against: repositories, code, commits, issues, wikis and users.
Below the six categories you can narrow down your search by selecting which coding language you want your result to show.

At the bottom of the basic search configuration are two links: Advanced search and cheat sheet.
Advance search shows up below the search bar on the search home page accompanied by prefixes, which is the cheat sheet.

Advanced search is highly customisable, allowing you narrow down results based on all parameters i.e. number of stars, code file extensions, time updated, location and even file size.

The cheat sheet allows you to use advanced search by typing shortcuts into the search bar. For example, to find repos associated with the word cat and have greater than 100 stars, you can type `cat stars:>100`.



#### Interacting with others *(stub)*

[How to interact with others on a group project](https://github.com/OliveIsLazy/Project-1.3/blob/master/CONTRIBUTING.md).

You can [mention](https://help.github.com/articles/basic-writing-and-formatting-syntax/#mentioning-people-and-teams) others in posts you make. Mentions are indicated using @. For example, to mention me you would type `@OliveIsLazy`. This will give me a notifcation that allows me to see what you mentioned me in.

Issues can also be used to interact with other people as you can have multiple comments on an issue, [as such](https://github.com/yenchenlin/DeepLearningFlappyBird/issues/8).
The same applies to [pull requests](https://github.com/yenchenlin/DeepLearningFlappyBird/pull/14), meaning messaging apps may be redundant when using GitHub as long as the contributors regularly check for new notifications and respond to them timely.




### Using GitHub

#### Project page

This page has four main sections: High bar, project information area, source code and a README.md file.

###### 1. The high bar

The high bar has 5 publically available tabs plus two more if this is your repo (the wiki and settings tabs).

  1. Code, the files and the source code associated with the repo.
  
  2. Issues, the issues associated with the repo.
  
  - Has a subcategory which shows what labels an issue can have i.e. bug. They are colour coordinated. *(stub)*
  
  - Also shows Milestones which allows for specific tasks to be set along with a deadline for their completion. *(stub)* 
  
  3. Pull Requests, pull requests that need reviewing associated with the repo.
  
  4. Projects, shows all the projects associated with the repo.
  
  5. Insights, statistics relating to the repo.
  
There are also three buttons above these tabs relevant for interacting with other people. The number next to each button is how many people have also done x with this repo.

  - Watch, allows you to follow this repo so you can be updated on its activity.
  
  - Star, allows you to favourite this repo.
  
  - Fork, allows you to create a clone of this repo.
  
###### 2. Project information area

Holds a short description or useful links for the repo and 5 counters: Commits, branches, releases, contributors and the repo's liscence.

###### 3. Source code area

When you are viewing a specific file from the repo, you will be at the source code interface:

  - Raw, shows you the text as it is written. This is relevant when you want to ignore the flavored Markdown syntax GitHub uses.
  
  - Blame, reorganises the file in question so that the right side shows you the raw file with some colour coordination and the left side shows you who modified the file, which lines and how long ago.
  In between the two sides are little tags that can show you how the file looked before a blame was made.
  
  - History, Shows you the recent commits made chronologically, along with their contributor.
  
  - Open this file in [GitHub Desktop](https://desktop.github.com/), opens the file in GitHub Desktop, an open source application made to streamline using GitHub.
  
  - Edit, allows you to modify the text. Can only be done if you're signed in as you can edit only your own repos, else GitHub will automatically fork it you one of your account's repos so you can edit the text.
  
  - Delete, allows you to delete the file. You also need to be signed in for the aforementioned reasons.

###### 4. The README.md file

A decription of the project, its main documents, how to download and use it as well as any additional information.
The extension .md denotes that the file is written with [flavored Markdown syntax](https://help.github.com/articles/about-writing-and-formatting-on-github/), a syntax GitHub uses to stylise text, and can be replaced with the .txt extension.
The file extension of a file is important so be sure to add it i.e. add .py for python code files, .java for java code files.



#### Licenses *(stub)*

A license tells other users what you can and cannot do with your software. In regards to choosing a license (from [help.GitHub](https://help.github.com/articles/licensing-a-repository/)):

> You're under no obligation to choose a license. However, without a license, the default copyright laws apply, meaning that you retain all rights to your source code and no one may reproduce, distribute, or create derivative works from your work.

GitHub help also created [this](https://choosealicense.com/) to help you choose your license.

The MIT license is a common license if you don't really know what to do and want to have a project open source.


#### Files, folders and other stuff

When you're interacting with a depo, note what branch you're looking at.

To better understand folders and moving files, think of the repo in question as the super folder, the folder that holds all folders.
If you want to create a new folder, it must not have a unique name in the current folder.

[To create a new folder](https://stackoverflow.com/questions/18773598/creating-folders-inside-github-com-repo-without-using-git), select new file, type the folder's name in the file name bar and then add a /.
A folder must have at least one file in it so create a temporary file to finalise the creation of the folder.

[To move an existing file into a different folder](https://help.github.com/articles/moving-a-file-to-a-new-location/), you follow a similar process. You edit the file and change it's name to add it to a different folder directory.

##### Branches

You can create a new branch by click on the branch dropdown menu and typing in the search bar the name of the new branch. Then click create new branch.

To configure or delete existing branches, go to the repo's main page and select the branch label below the repo description.



#### Projects

You can make a new project by creating a new repo, assigning a liscence.

Projects allow for more micromangaing than a plain old repo does.

- Kanban layout, helps track tasks use three columns: To do, in progress and done.

- Cards, tiles that have writing on them i.e. finish recursive code in the search method.
  - Can be dragged from column to column.
  - Can be turned into an issue.
  - Markdown syntax applies to cards.
  - Can have [automised](https://help.github.com/articles/about-automation-for-project-boards/) card creation and movement.
  
  When you're done with a project, you can click on the menu option on the right and click close, indicating that this project is complete or no longer in use.



#### Contributing to a repo

Contributing to a repo or a project involve forking, pull requests, cloning, commits, pushing and pulling. It's the actual  practice of all the stuff I've been explaining so far to share code via Git.

###### Git

Git is a source code control system that allows users to sync files together, like drop box, allowing multiple people to have access to the same files despite changes other people may make to them over time.
GitHub, therefore, is the community that results of people being able to share and use code from an online database, hub meaning a centre of an active network.
Git's syncing process tends to follow the same pattern:

1. (Fork and then) clone.

2. Edit.

3. Create a commit.

4. Push commit to the server.

5. Submit a pull request for your commit.


###### How to: Pull request

1. Fork your file or clone it in some way, so you may tinker around with it.

2. Test your changes and make sure your code is ready for use, or for someone else to modify.

3. Submit the file as a pull request rather than committing to the master branch.

4. Title and comment the request so other have an easier time reviewing it.

You may hear terms like head of the fork or base of the fork.
Take the head to mean the file you're pushing and the base to be the place you want it to be added to.




### Documentation and Communication *(stub)*

[GitHub Pages](https://pages.github.com/), hosted directly from a GitHub repo for documentation.

[Wiki](https://guides.github.com/features/wikis/), for documentation.

[Jekyll](https://jekyllrb.com/), a free static site generator that allows for easy blogging from the creators of GitHub.

[Slack](https://slack.com/features), communication app.

  - If This Then That [(IFTTT)](https://ifttt.com/), an app for slack that does x when y happens, making message sending and notifcations automatic.
  
  - [Glitter](https://gitter.im/) is an alternate to Slack.
  
[Trello](https://trello.com/), for keeping things (projects) organised.
