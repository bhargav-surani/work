

#### What is git ?
   Git is a distributed version control system. 
   
#### What’s a version control system?
A version control system, or VCS, tracks the history of modify as people and teams collaborate on projects together. As the project evolves, run tests, fix bugs, and contribute new code with the confidence that any version can be recovered at any time. Developers can open project history to find out:

  * Which changes were made?
  * Who made the changes?
  * When were the changes made?
  * Why were changes needed?

#### What’s a distributed version control system?
Git is an example of a distributed version control system (DVCS). DVCSs allow access to every file and branch of a project, and allows every user access to a full and self-contained history of all changes. Unlike once popular centralized version control systems, DVCSs like Git don’t need a constant connection to a central repository. Developers can work anywhere and contribute from any time.

Without version control, team members facing problems like redundant tasks, slower timelines, and multiple copies of a single project. To reduce unnecessary work, Git and other VCSs give each contributor a unified and consistent view of a project, surfacing work that’s already in progress. Seeing history of changes, who made changes, and how they contribute to the development of a project helps team members stay aligned while working independently.

#### Why Git?
Now days, more than 70 percent of developers use Git, making git the most-used VCS in the world. Git is commonly used for both open source and commercial software development, with significant benefits for individuals, teams and businesses.

  * Git lets developers see the entire timeline of their changes, decisions, and progression of any project in one place. From the moment they access the history of a project, the developer has all the context they need to understand it and start contributing.

  * Developers work in every time zone. With Git, collaboration can happen any time while change or adding source code integrity. Using branches, developers can safely make offer to changes in production code.

  * Businesses using Git can break down communication barriers between teams and keep them focused on doing their best work. Plus, Git makes it possible to align experts across a business to collaborate on major projects.
  
#### What’s a repository?
A repository, or Git project, is collection of files and folders associated with a project, along with each file’s revision history. The file history appears as snapshots in time called commits, and the commits exist as a linked-list relationship, and can be organized into multiple lines of development called branches. Because Git is a DVCS, repositories are self-contained units and anyone who owns a copy of the repository can access the entire codebase and its history. Using the command line or interfaces, a git repository also allows for: interaction with the history, cloning, creating branches, committing, merging, comparing changes across versions of code, and more.

Working in repositories keeps development projects organized and protected. Developers are encouraged to fix bugs, or create fresh features, without fear of derailing mainline development efforts. Git facilitates this through the use of topic branches: lightweight pointers to commits in history that can be easily created and deprecated when no longer needed.

Through platforms like GitHub, Git also provides more opportunities for project transparency and collaboration. Public repositories help teams work together to build the best possible final product.

#### Basic Git commands
* `git init` initializes a brand new Git repository and begins tracking an existing directory. It adds a hidden subfolder within the existing directory that houses the internal data structure required for version control
* `git remote`  creates a local copy of a project that already exists remotely. The clone includes all the project’s files, history, and branches.
* `git add` stages a change. Git tracks changes to a developer’s codebase, but it’s necessary to stage and take a snapshot of the changes to include them in the project’s history. This command performs staging, the first part of that two-step process. Any changes that are staged will become a part of the next snapshot and a part of the project’s history. Staging and committing separately gives developers complete control over the history of their project without changing how they code and work.
* `git commit` saves the snapshot to the project history and completes the change-tracking process. In short, a commit functions like taking a photo. Anything that’s been staged with git add will become a part of the snapshot with git commit.
* `git status` shows the status of changes as untracked, modified, or staged.
* `git pull` updates the local line of development with updates from its remote counterpart. Developers use this command if a teammate has made commits to a branch on a remote, and they would like to reflect those changes in their local environment.
* `git push` updates the remote repository with any commits made locally to a branch.
* `git branch` shows the branches being worked on locally.
* `git merge` merges lines of development together. This command is typically used to combine changes made on two distinct branches. For example, a developer would merge when they want to combine changes from a feature branch into the master branch for deployment. 
  

