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
### 初识 Git & Git Merge

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
### 眼不见心不烦？

<!-- slide -->
### 拥抱 Rebase

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
* 干净、线性历史记录
<p></p>
#### Cons
* `> git push --force`
  *  改动丢失风险
  *  冲突解决成本

<!-- slide -->
<p> -- 《Pro Git》 </p>
@import "./assets/golden_rule.png" {width="100%"}

<!-- slide -->
* imdependent task branch
* task owner finish task independently
* rebase lastest master before merge
* merge branch into master

<!-- slide -->
@import "./assets/clean-graph.png" {width="80%"}

<!-- slide -->
### Problems in Actual Projects
<!-- slide -->
#### The price of resolving conflicts

<!-- slide -->
### commit hash & CI

<!-- slide -->
* Imdependent task branch
* Task owner finish task independently
* Rebase lastest master before submit for review 
  **in develop stage**
* **Merge lastest master before merge**
* Merge branch into master

<!-- slide -->
### Any other choices?

<!-- slide -->
#### **A good develop process**
* Good tool and machanism
* Developer's consensus and strict compliance

<!-- slide -->
## Thanks


