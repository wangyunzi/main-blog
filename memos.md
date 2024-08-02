---
layout: page
title: 瞬间
# layout: memos
date: 2024-04-21
permalink: /memos/
order: 4
---


<div id="bber"></div>
<script>
  // 以下信息改掉
  var bbMemo = {
    memos : 'https://s.dusays.com/', //填入memos网站域名，末尾需带斜杠
    limit : '20', //填入需要展示的memos数量
    creatorId:'9' , //自己部署的话默认为1，不用修改
    domId: '#bber', //可以不修改
    username:"王云子", //修改为你自己的昵称
    useravatar:"https://blog.wangyunzi.com/avatar.png", //修改为自己的头像链接
    userlink:"https://wangyunzi.com", //修改为你的域名
    tags:"",
    commentsShow:false, //没有评论功能可修改为false
    commentsUrl:"https://s.dusays.com/m/", //修改为你的Memos域名，但保留包含m的尾巴部分
    commentsTitle:"评论" //可以不修改
  }
  var artalkInit = {
  el: '#Comments',                // 绑定元素的 Selector
  site: "长街短梦", //填入前面artalk设置中的站点名，没有评论功能可以不管
  server:'' //填入前面artalk的网站域名，没有评论功能可以不管
  // server:'https://artalk.wangyunzi.com' //填入前面artalk的网站域名，没有评论功能可以不管
}
</script>
<!-- js引用路径自己改好 -->
<link rel="stylesheet" href="https://cdn.staticfile.org/artalk/2.8.3/Artalk.css">
<script type="text/javascript" src="https://cdn.staticfile.org/artalk/2.8.3/Artalk.js"></script>
<script src="https://npm.elemecdn.com/marked/marked.min.js"></script>
<script src="https://jsd.onmicrosoft.cn/gh/Tokinx/ViewImage/view-image.min.js"></script>
<script src="https://jsd.onmicrosoft.cn/gh/Tokinx/Lately/lately.min.js"></script>
<script src="{{ "/assets/js/memos.js"}}"></script>


