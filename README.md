自己写的一些签到脚本

如果论坛开启Cloudflare质询会无法签到

列表:

zodgame


## 部署自动签到---------------

### 1. 添加 Cookie 至 Secrets

- 首先通过F12抓取到Cookie，随后在项目页面，依次点击`Settings`-->`Secrets`-->`New secret`

![new-secret.png](https://i.loli.net/2020/10/28/sxTuBFtRvzSgUaA.png)

- 建立名为`COOKIE`的 secret，值为`步骤1`中复制的`Cookie`内容，最后点击`Add secret`

- secret名字必须为`COOKIE`！
- secret名字必须为`COOKIE`！
- secret名字必须为`COOKIE`！

![add-secret](https://i.loli.net/2020/10/28/sETkVdmrNcCUpgq.png)

### 2. 启用 Actions

> Actions 默认为关闭状态，Fork 之后需要手动执行一次，若成功运行其才会激活。

返回项目主页面，点击上方的`Actions`，再点击左侧的`Genshin Impact Helper`，再点击`Run workflow`
    
![run](https://i.loli.net/2020/10/28/5ylvgdYf9BDMqAH.png)

</details>

至此，部署完毕。
