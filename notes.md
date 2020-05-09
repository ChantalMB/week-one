# Week 1: Notes

### Readings
  * Many groups discuss how the internet would be the dawn of democratization/open access to academic resources --> very few groups actually adopted this mentality
    * In my academic life, for computer science I have neverhad to purchase a textbook, they have all been open source --> in history I have either had to by textbooks, books, or had access to readings that would normally be blocked by a paywall, which prevents me from referencing them in the future
  * Open access can act as a solution for marginalized voices


### Github
  * As someone who studies computer science, I am familiar with github and its use
  * I can work with the github UI fine, but I’ve never really used it through the terminal
  * For this course I have decided to avoid the drag/drop feature of github and try to perform all repository creation and updates from the command line
    * Learning to use command line allows meto understand how to use git on *all* operating systems rather than just my own
  * Merging local folder with existing github repository
      * ```git init```
      * ```git remote add origin https://github.com/ChantalMB/week-one```
      * ```git pull origin master```
      * ```git add —all```
      * ```git commit -m “a message”```
      * ```git push -u origin master```
  * Updating said github repository
      * ```git status```
      * ```git pull origin master```
      * ```git add \<file\> OR -a```
      * ```git commit -m “a message”```
      * ```git push -u origin master```
  * .DS_Store files
    - When I first added all files from my local directory into my repository, files titled .DS_Store popped up
    - Seems to be a macOS specific file, so I don't want it in my repository
    - How can I stop them from appearing when I add or update a repository?
  * .gitignore
    * Solution to the .DS_Store problem
    * By creating a .gitignore file, I can make git ignore files I don't want added to my repository hence they'll never be uploaded
    * Creating/adding to .gitignore
      * ```git commit```
      * ```touch .gitignore```
      * ```vim .gitignore```
      * Write to this file which files you want to exclude
      * ```git add .gitignore```
      * ```git push -u origin master```


### Hypothes.is
  * Never heard of this, seems like very useful tecnology --> would like to trry and integrate this into my essay writing process
  * Does not seem to be compatible with mobile devices
    * Will have to experiment in using it with my iPad so I can read assigned texts better
    * Software appears to be open source, perhaps there is public contributions to developing a mobile interface that I could look into


### Zotero
  * Zotero notes presented via github slides --> I have NEVER seen a github slide show, definitely a technology I’d like to try in the future
  * Will use this application to separate my reading into folders containing what's assigned in class and what other readings pique my interest


### Discord
  * Discord is one of my favourite messaging platforms --> have used it both with friends and for other classes
  * Enjoy the "community" and casual feel of it --> less intimidating to ask for help


### Creating a static site for my journal entries
  * Opportunity to practice my skills
  * Easier to reference back to previous posts
  * I like github, but not for storing and writing larger texts
  * Still trying to think of a catchier title for the blog
  * Jekyll seems like the best option because of its legacy and integration with GitHub Pages
