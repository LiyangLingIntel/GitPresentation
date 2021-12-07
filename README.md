# Git Merge v.s. Git Rebase

1. 介绍主题
    drama的名字，学习生活，对git使用工作流的理解

2. git / github / gitlab / gitee 区别与联系

3. 一句话解释git merge & git rebase

4. git merge
    * 从学习和实习的经历介绍与git merge相遇相知
        single branch & only merge
    * 深入了解git merge --> merge 的问题

5. git rebase
    * 与rebase的相识与相爱
    * 详细解释rebase的好处

6. 理性讨论 pros and cons (重点)
   1. 工作中遇到的具体问题，导致不能正常使用 rebase

7. 可能合适的 git 工作流
    工具是既定的，开发者是灵活的

20211111 - first presenting feedback
* github 等介绍多余了，和主题无关
* slides中存在typo，中英文混合
* 对branch的remote/local描述不清，描述的时候需要加前提
* Slides 上merge rebase的优缺点混合在一块不清晰
* 演讲流程线索不清晰
* 最好更加关注 merge 和 rebase 本身的使用和解析
* 需要突出中心思想，需要一页 take off 来总结

20211203 - second group presenting
* 给具体一些case添加图例，讲清楚具体场景
  * out of sight out of mind?
  * unstable master 
* 收尾需要呼应，稍微体现 love song 的前后剧情
* Commit Hash 这一节需要讲清楚，尽量简化复杂度
* 部分文本对齐
* git push --force 需要解释，在合作时应该尽可能避免 force push