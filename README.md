# HEU - Analytics

该仓库基于开源项目[Han-Analytics](https://github.com/uxiaohan/HanAnalytics)，用于生成哈尔滨工程大学课程攻略共享计划统计分析面板，并托管在 Cloudflare Pages 上。

访问面板：[https://analytics.heu.us.kg/](https://analytics.heu.us.kg/)

### 集成使用

```js
<!-- 在网站底部插入以下代码即可集成网站分析仪表板 -->
<script defer src="https://analytics.heu.us.kg/tracker.min.js" data-website-id="自定义网站唯一标识"></script>
```

**ps:目前仅限白名单内网站可统计。统计分析面板，如要添加，请联系管理员sky9464@qq.com**

**白名单变量：CLOUDFLARE_WEBSITE_WHITELIST=heu.us.kg,哈尔滨工程大学课程攻略共享计划|analytics.heu.us.kg,统计分析面板**
