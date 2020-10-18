# kottans-frontend :cat:
### Repo for [kottans-frontend course tasks](https://github.com/kottans/frontend) :octocat:
---

## Curriculum:

**General**
- [x] **0.** [Git basics](https://github.com/kottans/frontend/blob/master/tasks/git-intro.md)
    - [Course: Version Control with Git (Udasity)](https://www.udacity.com/course/version-control-with-git--ud123)
    - [Course: Learn Git branching](https://learngitbranching.js.org/) 
- [x] **1.** Linux CLI and Networking
    - [Course: Linux Survival](https://linuxsurvival.com/linux-tutorial-introduction/)
    - [Article: HTTP: The Protocol Every Web Developer Must Know - Part 1](https://code.tutsplus.com/tutorials/http-the-protocol-every-web-developer-must-know-part-1--net-31177)
    - [Article: HTTP: The Protocol Every Web Developer Must Know - Part 2](https://code.tutsplus.com/tutorials/http-the-protocol-every-web-developer-must-know-part-2--net-31155)
- [ ] **2.** VCS (hello gitty), GitHub and Collaboration

**Front-End Basics**
- [ ] **3.** [Intro to HTML & CSS](tasks/html-css-intro.md)
- [ ] **4.** [Responsive Web Design](tasks/html-css-responsive.md)
- [ ] **5.** [HTML & CSS Practice](tasks/html-css-popup.md)
- [ ] **6.** [JavaScript Basics](tasks/js-basics.md)
- [ ] **7.** [Document Object Model](tasks/js-dom.md) - practice

**Advanced Topics**
- [ ] **8.** [Building a Tiny JS World (pre-OOP)](tasks/js-pre-oop.md) - practice
- [ ] **9.** [Object oriented JS](tasks/js-oop.md) - practice
- [ ] **10.** [OOP exercise](tasks/js-post-oop.md) - practice
- [ ] **11.** [Offline Web Applications](tasks/app-design-offline.md)
- [ ] **12.** [Memory pair game](tasks/memory-pair-game.md) — real project!
- [ ] **13.** [Website Performance Optimization](tasks/app-design-performance.md)
- [ ] **14.** [Friends App](tasks/friends-app.md) - real project!
---

# Stage 0. Self-Study
---

## General

### 0.0. Git Basics
#### 0.0.1. [Version Control with Git](https://www.udacity.com/course/version-control-with-git--ud123)

- This Udacity course was more like updating knowledge to me.
But I also learned about **tagging** and some commands that are going with it (git log --decorate, git describe).
The course also reminded me of the commands `git log -p (--patch)` and `git log -p --stat`
- Thing that surprised me is that I don't know how I lived without `git log --oneline --decorate --graph --all` command before :flushed:
- I'll definitely use this commands every day!

I certainly would recommend the course for all newbies. It's easy for understanding 

<details><summary>Screenshot</summary>
<p>

![Screenshot-image-link](task_git_basics/0.0.1-udacity.png)

</p>
</details>

#### 0.0.2. [Learn Git branching interactive course](https://learngitbranching.js.org/)
- I practiced on this course before, but passed only half of the levels. A few months ago it seemed to me much more complex. 
This time I've finished all tasks. But it was still hard for me to pass the last level. I definitely should try to pass it one more time after having some practice.
New for me: difference between rebasing and merging (Rebasing is ok to use when you do not care about the commit history, but the tree readability is important for you. But it's better to use merging if the commit history is very important.
- thing that surprised me is that cherry-picking is not so complex as it seemed to me before
- thing I intend to use in the future: cherry-picking :) 

<details><summary>Screenshot1</summary>
<p>

![Screenshot-image-link](task_git_basics/0.0.2-learngitbranching_1.png)

</p>
</details>

<details><summary>Screenshot2</summary>
<p>

![Screenshot-image-link](task_git_basics/0.0.2-learngitbranching_2.png)

</p>
</details>

##### Additional:
- added some new git cheatsheets to bookmarks 
- finished markdown tutorial on Github 
- finished short course about Shell on udacity while learning Version Control with Git
---

### 0.1. Linux CLI, and HTTP

#### 0.1.1 [Linux Survival Course](https://linuxsurvival.com/linux-tutorial-introduction/)

- While I was passing [Course: Version Control with Git (Udasity)](https://www.udacity.com/course/version-control-with-git--ud123) I also finished the [Shell Workshop](https://www.udacity.com/course/shell-workshop--ud206) on Udacity, so some commands were not new for me on this stage. 
New info for me: security modes (`r` for reading, `w` for writing, `x` for executing) and `chmod` command for changing modes. 
Some more new commands: `finger` - for showing user info; `cat` - for concatenating (adding).
Command `ps aux` for listing processes (`ps aux |grep <someword>` for listing processes with this word) may be also useful.
- Surprised me: managing printer queue from the command line.
- I'm sure I'll use such commands as `ls -l`. And some tips as using * and ? for simplified search. 
Maybe I'll use `df` command to watch free disk space. 
Commands like `rmdir` for deleting empty dir; `rm -r <dirname>` for deleting dir with such name.
Also, I'm sure I will not manage print queue from the command line :grinning:


<details><summary>Screenshot 1</summary>
<p>

![Screenshot-image-link](./task_linux_cli/0.1.1-linux_survival_1.png)

</p>
</details>

<details><summary>Screenshot 2</summary>
<p>

![Screenshot-image-link](./task_linux_cli/0.1.1-linux_survival_2.png)

</p>
</details>

<details><summary>Screenshot 3</summary>
<p>

![Screenshot-image-link](./task_linux_cli/0.1.1-linux_survival_3.png)

</p>
</details>

<details><summary>Screenshot 4</summary>
<p>

![Screenshot-image-link](./task_linux_cli/0.1.1-linux_survival_4.png)

</p>
</details>

#### 0.1.2. [HTTP: The Protocol Every Web Developer Must Know - Part 1](https://code.tutsplus.com/tutorials/http-the-protocol-every-web-developer-must-know-part-1--net-31177)
and
#### 0.1.3. [HTTP: The Protocol Every Web Developer Must Know - Part 2](https://code.tutsplus.com/tutorials/http-the-protocol-every-web-developer-must-know-part-2--net-31155)

- New for me: 
Status codes (1xx: Informational Messages, 2xx: Successful, 3xx: Redirection, 4xx: Client Error, 5xx: Server Error).
The request verbs (methods) **GET** for getting an existing resource, **POST** - with data for new resource, **PUT** updating resource, **DELETE** . 
Finaly I understood what means S in https :)
It was interesting to read about persistent and parallel connections and caching (Document Expiration part was the most interesting for me). 
- It was a little surprise for me how much other info is transferred between the client and the server, in addition to the information that the user requests.
- The article is very rich for new information. So it worth re-reading it in the future for deeper understanding.

