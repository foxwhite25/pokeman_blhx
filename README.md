[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">

  <h3 align="center">Hoshino碧蓝航线<del>戳一戳</del>集卡小游戏</h3>

  <p align="center">
    魔改自poke_man_blhx
    <br />
    <a href="https://github.com/GWYOG/GWYOG-Hoshino-plugins">查看原版</a>
    ·
    <a href="https://github.com/foxwhite25/pokeman_blhx/issues">回报BUG</a>
    ·
    <a href="https://github.com/foxwhite25/pokeman_blhx/issues">请求功能</a>
  </p>
</p>



<!-- 目录 -->
<details open="open">
  <summary><h2 style="display: inline-block">目录</h2></summary>
  <ol>
    <li>
      <a href="#关于这个插件">关于这个插件</a>
      <ul>
        <li><a href="#特点">特点</a></li>
      </ul>
    </li>
    <li>
      <a href="#如何下载并且安装">如何下载并且安装</a>
      <ul>
        <li><a href="#必備條件">必備條件</a></li>
        <li><a href="#安装">安装</a></li>
      </ul>
    </li>
    <li><a href="#使用方法">使用方法</a></li>
    <li><a href="#未来规划">未来规划</a></li>
    <li><a href="#贡献">贡献</a></li>
    <li><a href="#协议">协议</a></li>
    <li><a href="#联系">联系</a></li>
    <li><a href="#致谢">致谢</a></li>
  </ol>
</details>



<!-- 关于这个插件 -->
## 关于这个插件
本插件魔改自<a href="https://github.com/GWYOG/GWYOG-Hoshino-plugins">Poke_man_pcr</a>
### 特点

* []()新增了个群排行榜指令
* []()因为我两个插件同时启用，所以这个插件移除了戳一戳的部分<del>(失去了灵魂)</del>
* []()也因上述原因，所有指令都有碧蓝航线这个前置（例如碧蓝航线查看仓库）



<!-- 如何安装 -->
## 如何下载并且安装

要得到一份本地副本，你只需要做以下这些简单的东西

### 必備條件

这个是一个<a href="https://github.com/Ice-Cirno/HoshinoBot/">Hoshino</a>插件，你必须要要有一个设置好的Hoshino。
* Hoshino
  ```sh
  git clone https://github.com/Ice-Cirno/HoshinoBot.git
  ```
### 安装

1. 克隆这个仓库
   ```sh
   git clone https://github.com/foxwhite25/pokeman_blhx.git
   ```
2. 移动到modules文件夹
3. 安装必要的Python库
4. 修改你要修改的东西(_bot.py etc)


<!-- USAGE EXAMPLES -->
## 使用方法

res/img/blhx/tools/文件夹中的是爬虫脚本，有需要可以自行研究

|指令|说明|
|-----|-----|
|碧蓝航线查看仓库 |查看自己的仓库、卡片收集情况和排名|
|碧蓝航线查看仓库 [@某人]|查看指定群友的仓库、卡片收集情况和排名|
|碧蓝航线合成 [卡片1昵称] [卡片2昵称]|消耗两张卡片以获得一张新的卡片。如是稀有或超稀有卡片请在卡片昵称前加上"稀有"或''超稀有"，如"稀有黑猫"|
|碧蓝航线一键合成 [稀有度1] [稀有度2] [合成轮数(可不填)]|一键进行若干轮"稀有度1"和"稀有度2"的卡片合成(每张卡片会自动保留1张)。若不填合成轮数，则合成尽可能多的轮次。稀有度指"普通","稀有"或"超稀有"|
|碧蓝航线赠送 [@某人] [赠送的卡片名]|将自己的卡片赠予别人|
|碧蓝航线交换 [卡片1昵称] [@某人] [卡片2昵称] |向某人发起卡片交换请求，用自己的卡片1交换他的卡片2。同样，如是稀有卡片请在卡片昵称前加上"稀有"二字。|
|碧蓝航线确认交换 |收到换卡请求后一定时间内输入这个指令可完成换卡|
|碧蓝航线群排行榜 |查看当前群里的前20的排名|
|碧蓝航线一键抽卡 |一键把当天次数全部抽完，避免刷屏|


<!-- 未来规划 -->
## 未来规划
* 咕咕咕
* 有什么要的功能可以去issue说，也欢迎pr。

<!-- 做出你的贡献 -->
## 做出你的贡献

贡献使开源社区成为了一个令人赞叹的学习，启发和创造场所。**非常感谢你所做的任何贡献**。

1. Fork 这个项目
2. 创建你的分支 (`git checkout -b feature/AmazingFeature`)
3. 提交你的改变 (`git commit -m '加入了超棒的功能'`)
4. Push到分支 (`git push origin feature/AmazingFeature`)
5. 打开一个PR



<!-- LICENSE -->
## 协议

根据MIT许可证分发。有关更多信息，请参见`LICENSE`。



<!-- CONTACT -->
## 联系

狐白白 - 1725036102 

项目地址: [https://github.com/foxwhite25/pokeman_blhx](https://github.com/foxwhite25/pokeman_blhx)



<!-- ACKNOWLEDGEMENTS -->
## 致谢

* []()<a href="https://github.com/Ice-Cirno/HoshinoBot/">Hoshino</a>
* []()<a href="https://github.com/GWYOG/GWYOG-Hoshino-plugins">GWYOG-Hoshino-plugins</a>





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/foxwhite25/pokeman_blhx.svg?style=for-the-badge
[contributors-url]: https://github.com/foxwhite25/pokeman_blhx/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/foxwhite25/pokeman_blhx.svg?style=for-the-badge
[forks-url]: https://github.com/foxwhite25/pokeman_blhx/network/members
[stars-shield]: https://img.shields.io/github/stars/foxwhite25/pokeman_blhx.svg?style=for-the-badge
[stars-url]: https://github.com/foxwhite25/pokeman_blhx/stargazers
[issues-shield]: https://img.shields.io/github/issues/foxwhite25/pokeman_blhx.svg?style=for-the-badge
[issues-url]: https://github.com/foxwhite25/pokeman_blhx/issues
[license-shield]: https://img.shields.io/github/license/foxwhite25/pokeman_blhx.svg?style=for-the-badge
[license-url]: https://github.com/foxwhite25/pokeman_blhx/blob/master/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/foxwhite25
