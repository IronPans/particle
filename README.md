# 简介

这是一款基于html5 canvas的轻量级炫酷js粒子动画库插件。该js粒子动画库插件可以设置粒子的数量、鼠标触发动画，效果非常酷。


# 用法

###创建一个canvas
`<canvas id="particles"></canvas>`
注：ID可以自定义

###引入js
`<script src="particle.min.js"></script>`

###实例化
`<script>`
			`var particle = new Particle('#particles', {});`
`</script>`

###参数说明
`var particle = new Particle('#particles', {   `
  `effect: 'line',
  `point:300` 
`});`

effect：鼠标移上去触发的动画
point：粒子数量

后续会继续更新优化！
