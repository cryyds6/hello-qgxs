# hello-qgxs
一个完全免费、美观实用、易于维护的静态个人主页！

# http://www.20210701.xyz

静态页面，可以在各种地方部署
1. Cloudflare Pages

2. Vercel

3. GitHub Pages

4. Netlify

页面功能介绍：

🎨 设计特点

1. 现代化视觉风格
   · 深色背景配合天蓝色主题色
   · 动态流光标题特效
   · 背景网格和发光模糊圆环
   · 简约卡片式布局
2. 响应式设计
   · 适配手机、平板和电脑
   · 自适应字体大小
   · 灵活的布局调整

✨ 核心功能

1. 个人信息展示区
   · 圆形头像
   · 动态流光标题 "Hello Qgxs"
   · 个性化欢迎语
2. 快捷导航按钮
   · 博客链接（带书本图标）
   · 100周年纪念链接（带旗帜图标）
   · "关于我" 渐变按钮
3. bing 自适应随机API

4. 加上即可强制跳转www
```
  <!-- //强制跳转www -->
<script>
if (location.hostname.slice(0, 4) !== 'www.') {
  location.href = '//www.' + location.host + location.pathname;
}
</script>
```

