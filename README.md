# kottans-frontend :cat:
### Repo for [kottans-frontend course tasks](https://github.com/kottans/frontend) :octocat:
---

## Curriculum:

**General**
- [x] **0.** [Git basics](https://github.com/kottans/frontend/blob/master/tasks/git-intro.md)
    - [Course: Version Control with Git (Udasity)](https://www.udacity.com/course/version-control-with-git--ud123)
    - [Course: Learn Git branching](https://learngitbranching.js.org/) 
- [x] **1.** [Linux CLI and Networking](https://github.com/kottans/frontend/blob/master/tasks/linux-cli-http.md)
    - [Course: Linux Survival](https://linuxsurvival.com/linux-tutorial-introduction/)
    - [Article: HTTP: The Protocol Every Web Developer Must Know - Part 1](https://code.tutsplus.com/tutorials/http-the-protocol-every-web-developer-must-know-part-1--net-31177)
    - [Article: HTTP: The Protocol Every Web Developer Must Know - Part 2](https://code.tutsplus.com/tutorials/http-the-protocol-every-web-developer-must-know-part-2--net-31155)
- [x] **2.** [VCS (hello gitty), GitHub and Collaboration](https://github.com/kottans/frontend/blob/master/tasks/git-collaboration.md)
    - [Course: GitHub & Collaboration](https://classroom.udacity.com/courses/ud456)
    - [Course: Learn Git branching (last levels)](https://learngitbranching.js.org/)

**Front-End Basics**
- [x] **3.** [Intro to HTML & CSS](https://github.com/kottans/frontend/blob/master/tasks/html-css-intro.md)
    - [Course: Intro to HTML & CSS (Udasity)](https://www.udacity.com/course/intro-to-html-and-css--ud304)
    - [Course: Learn HTML(Codeacademy)](https://www.codecademy.com/learn/learn-html)
    - [Course: Learn CSS(Codeacademy)](https://www.codecademy.com/learn/learn-css)
- [ ] **4.** [Responsive Web Design](https://github.com/kottans/frontend/blob/master/tasks/html-css-responsive.md)
- [ ] **5.** [HTML & CSS Practice](https://github.com/kottans/frontend/blob/master/tasks/html-css-popup.md)
- [ ] **6.** [JavaScript Basics](https://github.com/kottans/frontend/blob/master/tasks/js-basics.md)
- [ ] **7.** [Document Object Model](https://github.com/kottans/frontend/blob/master/tasks/js-dom.md) - practice

**Advanced Topics**
- [ ] **8.** [Building a Tiny JS World (pre-OOP)](https://github.com/kottans/frontend/blob/master/tasks/js-pre-oop.md) - practice
- [ ] **9.** [Object oriented JS](https://github.com/kottans/frontend/blob/master/tasks/js-oop.md) - practice
- [ ] **10.** [OOP exercise](https://github.com/kottans/frontend/blob/master/tasks/js-post-oop.md) - practice
- [ ] **11.** [Offline Web Applications](https://github.com/kottans/frontend/blob/master/tasks/app-design-offline.md)
- [ ] **12.** [Memory pair game](https://github.com/kottans/frontend/blob/master/tasks/memory-pair-game.md) — real project!
- [ ] **13.** [Website Performance Optimization](https://github.com/kottans/frontend/blob/master/tasks/app-design-performance.md)
- [ ] **14.** [Friends App](https://github.com/kottans/frontend/blob/master/tasks/friends-app.md) - real project!

---

# Stage 0. Self-Study

## General
---

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

---

### 0.2. Git for Team Collaboration

#### 0.2.1. [Course: GitHub & Collaboration](https://classroom.udacity.com/courses/ud456)

- The course was more like a repetition of previously used knowledge about `git remore` commands, `push`, `pull`, `fetch`. 
- Now the difference between `pull` and `fetch` seems more clear to me. (`fetch` + `merge` = `pull`)
I learned a lot of new commands for viewing repo history which are useful for collaboration. 
- I think I'll use such commands: 
  - `git shortlog` for showing all contributors of a repo.
  - `git log --grep=<someword>` search by keyword in the commit messages.
  - `git log --author=<Authorname>` search by author 
  - `git show SHA` - search commit by SHA 
  - `git remote rename <newRepoName> <oldRepoName>` to rename remote repositories (e.g. origin or upstream)
  - `git rebase -i HEAD~3` rebase last commits into 1 (interactive)
  - `git push -f` - Force Pushing

<details><summary>Screenshot</summary>
<p>

![Screenshot-image-link](task_git_collaboration/0.2.1-udacity_git_colaboration.png)

</p>
</details>


#### 0.2.2. [Course: Learn Git branching (last levels)](https://learngitbranching.js.org/)
I had passed it while doing task 0.0.Git Basics.

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

---

## Front-End Basics
---

### 0.3. Intro to HTML & CSS

#### 0.3.1. [Course: Intro to HTML & CSS (Udasity)](https://www.udacity.com/course/intro-to-html-and-css--ud304)

It's a useful course for making first steps in HTML and CSS. 
There was not new info for me.

<details><summary>Screenshot</summary>
<p>

![Screenshot-image-link](task_html_css_intro/0.3.1-udacity_intro_html_css.png)

</p>
</details>

#### 0.3.2. [Course: Learn HTML(Codeacademy)](https://www.codecademy.com/learn/learn-html)
It's a useful course for making first steps in HTML. 
New for me: 
- tag for incerting video

``` 
    <video src="myVideo.mp4" width="320" height="240" controls>
    Video not supported
    </video>
```
- tag for incerting audio

```
    <audio autoplay controls>
    <source src="AudioFile.mp3" type="audio/mp3">
    </audio>
```
- Datalist element for making input with ability to select a proposed variant (like a select input) and ability to enter user's own variant. 
``` 
    <label for="idname">Choose a flavor:</label>
    <input list="datalistid" id="idname" name="idname" />
    <datalist id="datalistid">
        <option value="Chocolate">
        <option value="Coconut">
    </datalist>
```
- tag `<embed>` for embeding media content from an external source 

```
    <embed src="download.gif"/>
```
- Validation: matching a pattern (for example pattern which checks that the user provided only numbers, min 14 digits - max 16 digits `pattern="[0-9]{14,16}`; or `[a-zA-Z0-9]+` fot letters and numbers)


<details><summary>Screenshot</summary>
<p>

![Screenshot-image-link](task_html_css_intro/0.3.2-codecademy_learn_html.png)

</p>
</details>


#### 0.3.3. [Course: Learn CSS(Codeacademy)](https://www.codecademy.com/learn/learn-css)

Flex and grid properties that were new for me: 
- Property `flex:` is short for grow, shrink, basis properties.
- Property `flex-flow:` is for flex-wrap and flex-direction properties in one line.
- `grid-template:` short for row and column sizes. For example `grid-template: 200px 300px / 20% 10% 70%;`.
- `repeat` can be used not only for one value. This line `grid-template-columns: repeat(2, 20px 50px)` is equal to 20px 50px 20px 50px.
- Minmax property should have min and max values in brackets: `grid-template-columns: 100px minmax(100px, 500px) 100px;`.
- Using word `span`. For example `grid-column: 4 / span 2;` means start at column 4 and take 2 columns of space.
- `grid-area:` is short for grid-row-start, grid-column-start, grid-row-end, grid-column-end. For example `grid-area: 2 / 3 / 4 / span 5;`
- `grid-template-areas` for giving a name for areas and maintaining their position. It's like an alternative way of specifying the position.
- `grid-auto-rows and -columns` for maintaining sizes of rows and columns which are not specified before. The first line specifies first 2 rows and 2 columns, the second line makes all other rows 50px width 
```
    grid: repeat(2, 100px) / repeat(2, 150px); 
    grid-auto-rows: 50px;
```
- `grid-auto-flow` property specifies the order in which new elements are rendered: rows(default), columns, dense (to fill holes earlier in the grid layout if smaller elements are added)
  
New transition properties for me: 
- `transition-property:` (color, size ...)
- `transition-duration:` (time: s, ms)
- `transition-delay:` (time: s, ms)
- `transition-timing-function:` (ease-in, ease-out, ease-in-out, linear)
- short rule: `transition: color 1.5s linear 0.5s;` 

Using new knowledge:
- It would be great to remember some of properties that were made for making code shorter. This will help me to understand code written by others. But maybe using such shortening can make a code more complex for understanding it from the first sight. So i'm not sure I'll use all of them.
- I'll definitely use such properties for grids as: `grid-template:`, `repeat`, `span`, `grid-area`, `grid-template-areas`


<details><summary>Screenshot</summary>
<p>

![Screenshot-image-link](task_html_css_intro/0.3.3-codecademy_learn_css.png)

</p>
</details>

---
