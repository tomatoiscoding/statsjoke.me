---
layout: post
title: 一点点想法和澄清
date: 2017-04-04
comments: true

---
最近在某大神云集的小群里总被莫名其妙的表扬一番，让本媛媛不知所措，受宠若惊，遂决定上来说点什么压压惊。本人毕业9个月，莫名其妙入了跟软件有关的行当（原本以为是做统计分析，为基因组科学做一丢丢贡献），谁知道我做的第一件事是开发了个R包（工程量浩大，写算法的，被性能坑死），两眼发懵，感觉要挂。为避免过早失业没饭吃，只好变成了睡的比狗晚起的比鸡早的什么什么狗。我接触R快4年了，最早就是做回归分析，ggplot2用过一点点（不知道为什么，我不喜欢用它画图），再后来我混入统计专业开始做simulation，准备发论文。直到去年大概九十月份的样子，我才知道原来写R包的算是软件工程师的范畴。现在细细回想这九个月的经历，可谓是传奇。后来我用shiny写过app，稍微接触了点可视化的东西，遂入JavaScript的坑。再后来我折腾过公司的API，明白了点OAuth第三方app授权的技术，又写了个shiny app，这东西虽小，但着实让我从前后端架构层面理解网站，写完我还部署到服务器上了。我被培训过docker容器的知识，也看过php的代码，我比较受不了以`刀辣`符号开头的语言，但也不排斥。我因为不写python经常被嫌弃，遂在举国上下欢度春节之时，抱着python的某个tutorial从头看到尾，感叹其简洁大方。以争分夺秒的速度，我不得不承认，我取得了一点点进步。尤其擅长看到不同语言不同软件之间的共性，然后火速上手。由于我的包在做纯的统计计算，我不得不全方位了解关于R的性能优化的问题，真的是全方位看文档。由于我的shiny app需要用户授权，填写表单并提交，我不得不学会OAuth2.0的那套东西，也不得不学会让shiny如何与后端mysql连接。由于为了让用户点完提交按钮感觉到自己真的是提交了，我不得不优化shiny的前端体验，然后接触了shinyjs这个东西，觉得非常有意思，遂对shiny的开发种下一根草，默默学了下jquery和ajax这些看似老掉牙的东西。后来我看了如何给shiny写新的组件的文档（只是现在真的没空去弄）。当然，shiny最让我不能忍的是它不支持多页面路由，它只能靠js来控制页面，你如果非要多页面，有个办法是在shiny server下放多个app，代表多个页面，只能帮你到这里了。