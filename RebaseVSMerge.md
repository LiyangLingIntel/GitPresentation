---
presentation:
    theme: beige.css
    mouseWheel: true
---

<!-- slide -->
## Git Merge & Git Rebase 
## 爱 恨 情 仇
<br/>
##### Present by: Liyang

<!-- slide -->
@import "./assets/git.png" {width="30%"}

<!-- slide -->
@import "./assets/github.jpg" {width="40%"}
<br/>
@import "./assets/gitlab.png" {width="40%"}
<br/>
@import "./assets/gitee.png" {width="40%"}

<!-- slide -->
@import "./assets/merge.svg" {width="49%"}
@import "./assets/rebase.svg" {width="49%"}

<!-- slide -->
### 初识 Git & Git Merge

<!-- slide -->
@import "./assets/merge-options.png" 

<!-- slide -->
* 非破坏性 - 保留已有分支结构

* 污染自己的分支记录

<!-- slide -->
@import "./assets/linus.png" {width="80%"}

I really don't want to see - github creates absolutely useless garbage merges.

<!-- slide -->
@import "./assets/garbage_merge.png"

<!-- slide -->
### 如果 Merge 被滥用？

<!-- slide -->
@import "./assets/git-graph.jpg"

<!-- slide -->
@import "./assets/tuboshu.gif"

<!-- slide -->
### 眼不见心不烦？

<!-- slide -->
### 拥抱 Rebase

<!-- slide -->
**来自网上的讨论**
* Rebase 的危害？
* 不要轻易使用 Rebase
* 切记：永远用rebase!

<!-- slide -->
@import "./assets/merge.svg" {width="49%"}
@import "./assets/rebase.svg" {width="49%"}

<!-- slide -->
* 干净、线性历史记录
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
### 实际项目中的问题
<!-- slide -->
### 解决 rebase 冲突的代价

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
## Thanks


