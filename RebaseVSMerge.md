---
presentation:
    theme: beige.css
    mouseWheel: true
    slideNumber: false
    progress: true
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
@import "./assets/merge-options.png" {width="70%"}

<!-- slide -->
#### Pros
* Preserve commits history .
<p></p>

#### Cons
* Pollute local branch &emsp;&emsp;&ensp;.

<!-- slide -->
@import "./assets/linus.png" {width="80%"}
<div style="text-align: left; margin: auto; width: 80%; padding: 10px;">
<p>I really don't want to see - github creates absolutely useless garbage merges.</p>
</div>

<!-- slide -->
@import "./assets/garbage_merge.png"

<!-- slide -->
### What if Merge is abused？

<!-- slide -->
@import "./assets/git-graph.jpg"

<!-- slide -->
@import "./assets/tuboshu.gif"

<!-- slide -->
### Out of sight out of mind？

<!-- slide -->
Example - switch base branch
@import "./assets/switch_base.png"

<!-- slide -->
### Embrace Rebase

<!-- slide -->
**Some discussion topics from the Internet**
* The Danger of Rebase？
* Do not adopt Rebase easily!
* Remember：always adopt rebase!

<!-- slide -->
#### Git Rebase
@import "./assets/rebase.svg" {width="80%"}

<!-- slide -->
#### Pros
* Clean and beautiful graph &emsp;&emsp;&emsp;&ensp;.
<p></p>

#### Cons
* Risk: `> git push --force`
* Expensive conflict resolution price
* Unstable master(used on master)


<!-- slide -->
@import "./assets/golden_rule.png" {width="100%"}
<p align="right"> --《Pro Git》 </p>

<!-- slide -->
#### Task branch
* **Comes** from **master** and **Goes** into **master**
* Finish independently
* Rebase lastest master before PR merge

<!-- slide -->
@import "./assets/clean-graph.png" {width="80%"}

<!-- slide -->
### Problems in Actual Projects

<!-- slide -->
### The price of resolving conflicts

<!-- slide -->
#### Unstable master
Before rebase
@import "./assets/unstable_master_0.png" {width="60%"}

<!-- slide -->
#### Unstable master
After rebase
@import "./assets/unstable_master_1.png" {width="60%"}

<!-- slide -->
### commit hash & CI

<!-- slide -->
#### Task branch
* Comes from **master** and goes into **master**
* Finished independently
* Rebase lastest master **in develop stage**
* **Merge** lastest master before PR merge

<!-- slide -->
### Any other choices?

<!-- slide -->
#### **A good develop process**
* Good tool and machanism
* Developer's consensus and strict compliance
* No discipline but good habits

<!-- slide -->
## Thanks


