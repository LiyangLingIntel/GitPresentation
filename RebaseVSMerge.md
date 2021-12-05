---
presentation:
    theme: beige.css
    mouseWheel: true
---

<!-- slide -->
## Love Song
#### of
### Git Merge & Git Rebase 
<br/>
##### Present by: Liyang

<!-- slide -->
@import "./assets/git.png" {width="30%"}

<!-- slide -->
### Branching Strategy

<!-- slide -->
@import "./assets/merge.svg" {width="49%"}
@import "./assets/rebase.svg" {width="49%"}

<!-- slide -->
### Encounter Git & Git Merge

<!-- slide -->
#### Git Merge
@import "./assets/merge.svg" {width="80%"}

<!-- slide -->
@import "./assets/merge-options.png" 

<!-- slide -->

#### Pros
* Keep existing commits history
<p></p>
#### Cons
* Pollute local branch

<!-- slide -->
@import "./assets/linus.png" {width="80%"}

I really don't want to see - github creates absolutely useless garbage merges.

<!-- slide -->
@import "./assets/garbage_merge.png"

<!-- slide -->
### If Merge is abused？

<!-- slide -->
@import "./assets/git-graph.jpg"

<!-- slide -->
@import "./assets/tuboshu.gif"

<!-- slide -->
### Out of sight out of mind？

<!-- slide -->
### Embrace Rebase

<!-- slide -->
**Some discussion topic from the Internet**
* The Danger of Rebase？
* Do not adopt Rebase easily!
* Remember：always adopt rebase!

<!-- slide -->
#### Git Rebase
@import "./assets/rebase.svg" {width="80%"}

<!-- slide -->
#### Pros
* Clean and beautiful graph
<p></p>
#### Cons
* `> git push --force`
  *  Loss changes
* High resolving conflict price
* Unstable master(used on master)


<!-- slide -->
<p> -- 《Pro Git》 </p>
@import "./assets/golden_rule.png" {width="100%"}

<!-- slide -->
**Task branch** 
* **comes** from **master** and go into **master**
* finished independently
* rebase lastest master before merge

<!-- slide -->
@import "./assets/clean-graph.png" {width="80%"}

<!-- slide -->
### Problems in Actual Projects

<!-- slide -->
#### The price of resolving conflicts

<!-- slide -->
### Unstable master
Before rebase
```
  A3  B2
  |   |
  A2  B1 -- has not run CI (may not build at all)
  |---+
  A1
```

<!-- slide -->
### Unstable master
After rebase
```
B2'
|
B1' -- broken commit on master(!)
| 
A3
| 
A2
|
A1
```

<!-- slide -->
### commit hash & CI

<!-- slide -->
Task branch 
* Comes from **master** and go into **master**
* Finished independently
* Rebase lastest master before submit for review 
  **in develop stage**
* **Merge lastest master before merge**

<!-- slide -->
### Any other choices?

<!-- slide -->
#### **A good develop process**
* Good tool and machanism
* Developer's consensus and strict compliance

<!-- slide -->
## Thanks


