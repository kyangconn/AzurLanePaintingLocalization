# AzurLanePaintingLocalization

> 碧蓝航线立绘本地化重命名，目前仅支持中文
>
>本项目作为碧蓝航线立绘导出工具 [AzurLanePaintingTool (下简称ALPT)](https://github.com/azurlane-doujin/AzurLanePaintingExtract-v1.0) 的附属项目。[ALPT教程点我](https://www.bigfun.cn/post/219941)

此项目为上述项目分支，采用不同更新方式，根据程序显示来翻译内容，与主项目存在差别。请注意选择。

当前为2024/9/5更新解包版本，请注意时效性。

<details>
<summary><code><strong>历史更新：</strong></code></summary>

>2023/01/13 12/22版本更新完成，剩余devil, qiabayefu_2_n, sairenboss14_jz无翻译。
>
>2023/01/18 1/18版本新增翻译完成，无新增无法翻译。
>
>2023/02/23 2/23版本新增翻译完成，修补部分之前的错误翻译。
>
>2023/03/24-03/31 3/23版本把铁血和谐名加上了，准备改变翻译顺序。3/31版本大和谐名字全改了，修了一点之前的小问题。
>>改动：把约克（铁血）改成了约克（伊冯娜），把约克（皇家）改成了约克。
>
>2023/05/06-05/25 4/27版本更新好了，之后大版本再弄release吧。5/25版本更新，把devil和tower翻译了，剧情最后有提到托瓦，大概就是tower了。
>
>2023/06/01 6/1皮肤更新，常规更新
>
>2023/07/02-07/20 6/29更新，还好很多东西都没有改。7/13更新，把前面弄错的修了一下，现在没有%了。7/20更新，把部分遗留问题修了一下，现在工具检索【无人物】应该会更准确结果更多。
>
>2023/08/03 8/3小更新，只更新了一艘船。
>
>2023/08/18 8/17大更新，增添`_front`翻译规则，塞壬hierophant有翻译了，新增kaiersheng_2bg无翻译
>>`kaiersheng_2bg`只有mesh文件没有图片，猜测是为游戏文件备份没删。
>
>2023/09/02 9/2小更新，增加 `神通(貎)·META` 的其他部分翻译，970205猜测为增添的当期立绘，忘删了应该是。
>
>2023/09/15 9/14重樱大活，有一艘瑞凤没有和谐名，也没有预告，不知道是打算什么时候出。
>
>2023/09/21-09/28 9/21小更新，更新了一些皮肤。9/28小更新，更新了一些皮肤。
>
>2023/10/19 10/19风帆小活动，更新了一艘船。
>
>2023/10/26 10/26风帆活动，更新了好多船，有个船的文件甚至有14个！我都不知道该怎么标注。还有插画名称插错的，把玛丽的插画名字插成了金鹿，笑死。
>
>2023/11/23 11/23联动闪乱神乐，更新了很多，这次的命名也是重量级，非常多后缀。
>
>2023/12/7 12/7殿堂更新，基洛夫META更新。
>
>2023/12/21-12/28 21号白鹰大活，更新了一些船。28号小更新。更新了一些皮肤。
>
>2024/1/30-2/22 30号新春更新，飞云无头立绘请注意。6号养成系统，更新了很多TB小姐的图，好在大量立绘名称都是可以重用的，工作量不大。22号小更新，更新了两个皮肤。
>
>2024/2/29 29号北联大活，更新了一些船和两个剧情人物立绘。
>
>2024/3/28 28号皇家活动，更新了一些船。
>
>2024/4/25 第三期兵装活动，新增无法翻译`μougen_pt`。
>
>2024/5/9-6/6 21号国服周年第一弹，更新了很多皮肤以及非常多之后的内容，由于这些内容，建议不要在此版本导出图片。30号周年更新第二弹，皮肤翻译完成，可以导出图片了。6号周年更新第三弹，更新了3个誓约皮肤和一个活动皮肤。
>
>2024/7/11 七期科研开启，懒病犯了，不想更新了。
>
>2024/7/25-9/5 强制更新包及之前的内容更新好了。
>
>2024/9/19 19号之前的更新完了，19号的更新还没解包。


</details>

<details>
<summary><code><strong>无法翻译项目：</strong></code></summary>
qiabayefu_2_n, sairenboss14_jz, dafeng_2_shophx, lundun_3bg, kaiersheng_2bg,

</details>

## 手动更新方法

0. **下载ALPT**（已安装请跳过）

    在 [ALPT 的下载页面](https://github.com/azurlane-doujin/AzurLanePaintingExtract-v1.0/releases)内找到`Latest release`标签，并展开其对应的`▶Assets`，下载其中无`Source Code`字样的压缩包，下载完成后解压。

1. **下载本地化文件**

    在本fork的release里点击下载，然后替换掉`ALPT/core/assets/names.json`，再次打开ALPT就可以看到翻译完成的。
    
    或，在本地新建一个.json，然后点进本项目的`names.json`，全选复制进本地文件，就完成了。

2. **应用本地化更新**

    替换法下载的在打开时已经更新好了。

    打开ALPT，依次点击 `设置`>`高级设置`>`更新本地化资源`>`加载文件` ，在弹出的文件选框中选择刚才下载的 `names.json` 文件并确认，`应用-全部` 即可。





## 命名规范分支修改版

| **文件名**             | **立绘名**                                                   | **备注**                                                                                    |
| ---------------------- | ------------------------------------------------------------ | ------------------------------------------------------------------------------------------- |
| aerjiliya_2            | 阿尔及利亚.皮肤1 白沙天堂                                    |                                                                                             |
| aerjiliya_2_n          | 阿尔及利亚.皮肤1 白沙天堂【无背景】                          | 此立绘相比`aerjiliya_2`缺少部分背景                                                         |
| aerjiliya_2_hx         | 阿尔及利亚.皮肤1 白沙天堂【和谐】                            | 此立绘相比`aerjiliya_2`有一定改动                                                           |
| aerjiliya_2_n_hx       | 阿尔及利亚.皮肤1 白沙天堂【无背景.和谐】                     | 此立绘相比`aerjiliya_2`既缺少部分背景又有一定改动 (注意先后顺序)                            |
| hemin                  | 赫敏                                                         | 本体                                                                                        |
| hemin_3                | 赫敏.皮肤1 温柔的纯白天使                                    | 此为赫敏第**1**个皮肤                                                                       |
| hemin_2                | 赫敏.皮肤2 纯白的悠闲假日                                    | 虽然一般来说后缀为"2"会排在"3"之前, 但此为赫敏时间顺序上第**2**个实装的皮肤                 |
| hemin_2_n              | 赫敏.皮肤2 纯白的悠闲假日【无背景】                          | 此立绘相比`hemin_2`缺少部分背景                                                             |
| hemin_5                | 赫敏.皮肤4 百草堂少女 背景                                   | 赫敏第4个皮肤，但缺少人物                                                                   |
| hemin_5_n              | 赫敏.皮肤4 百草堂少女【无背景】                              | 此立绘相比`hemin_5`缺少背景                                                                 |
| hemin_5_rw             | 赫敏.皮肤4 百草堂少女 人物                                   | 此立绘只能与`hemin_5`拼合成完整立绘，即只有人物                                             |
| hemin_pt               | 赫敏【插画】                                                 | 此为赫敏在活动pt兑换界面出现的立绘                                                          |
| huangjiafangzhou_alter | 皇家方舟·META                                                | 此角色名为"皇家方舟·META"，是META阵营角色                                                   |
| kelifulan              | 克利夫兰                                                     | 是克爹啊啊啊啊啊（拖走                                                                      |
| kelifulan_h            | 克利夫兰.誓约 心动一刻                                       | 克爹的誓约立绘                                                                              |
| kelifulan_idol         | 克利夫兰(μ兵装)                                              | 此角色名为"克利夫兰(μ兵装)"，是偶像系列活动角色                                             |
| kelifulan_younv        | 小克利夫兰                                                   | 此角色名为"小克利夫兰"                                                                      |
| keluoladuo             | 科罗拉多                                                     |                                                                                             |
| keluoladuo_2           | 科罗拉多.原皮                                                | 此为`keluoladuo`早期立绘                                                                    |
| weineituo_renwu        | 维托里奥·维内托【插画】                                      | 此为VV在任务中出现的立绘                                                                    |
| weineituo_renwu_hx     | 维托里奥·维内托【和谐.插画】                                 | 此立绘相比`weineituo_renwu`有一定改动 (注意先后顺序)                                        |
| xia                    | 霞(蕸)                                                       | 重樱阵营船，原名“霞”，“蕸”为游戏内和谐名                                                    |
| xia_g                  | 霞(蕸).改                                                    | "霞(蕸)"的改造形态                                                                          |
| xinzexi_2              | 新泽西(花园).皮肤1 跃动的舞台时间！背景                      | "花园"为游戏内和谐名，"新泽西"为原名                                                        |
| xinzexi_2_front        | 新泽西(花园).皮肤1 跃动的舞台时间！特效                      | 视合成情况来确定命名，完整立绘需要再次合成                                                  |
| xinzexi_2_renwu        | 新泽西(花园).皮肤1 跃动的舞台时间！人物                      | 在此皮肤中作为主体的人物部分                                                                |
| xinzexi_2_renwu_hx     | 新泽西(花园).皮肤1 跃动的舞台时间！人物【和谐】              | 此立绘相比`xinzexi_2_renwu`有一定改动                                                       |
| xunfulun_front         | 絮弗伦 前背景                                                | 这张立绘是与`xufulun`一体的背景，但被分割成了人物前部和后部，`_front`在此翻译文件中代表前面 |
| xunfulun_n_front       | 絮弗伦 前舰装                                                | 这张立绘是与`xufulun_n`一体，但被分割成了人物前部和后部                                     |
| ougen                  | 欧根亲王(萨沃伊亲王)                                         | 铁血阵营船，原名“欧根亲王”，“萨沃伊亲王”为游戏内和谐名                                      |
| i26                    | 伊26(双叶梦)                                                 | 伊系列原名均为“伊xxx”，“双叶梦”为游戏内和谐名                                               |
| u101                   | u-101(优伊欧伊)                                              | U艇系列原名均为“u-xxx”,“优伊欧伊”为游戏内和谐名                                             |
| z46                    | z46(希露)                                                    | z驱系列原名均为“zxxx”,“希露”为游戏内和谐名                                                  |
| hdn301                 | 布兰                                                         | 超次元游戏海王星联动角色                                                                    |
| hdn301_memory          | 布兰.回忆                                                    | 此为"布兰"在剧情中出现过的立绘                                                              |
| 970702                 | 皇家方舟·META【插画】                                        | 此为"皇家方舟·META"在剧情中出现的立绘                                                       |
|                        | 备注：现有解包文件无法找到此类文件，故此分支已经把97开头删除 |
| vtuber_aqua            | 湊阿库娅                                                     | Hololive联动角色                                                                            |
| vtuber_aqua_wjz        | 湊阿库娅【无舰装】                                           | 此立绘相比`vtuber_aqua`身上缺少舰装                                                         |

### Tips：

> 0. 要写吐了> <（确实，好多东西，都要一个个调）
> 1. 通常情况下，当立绘名中存在半角句号"."时，左数第一个"."左边的所有字符为该立绘对应的角色本体名称。
> 2. 通常情况下，当立绘名中存在半角句号"."时，左数第一个"."右边的字符代表该立绘之于角色本体的类型。
> 3. 塞壬阵营/指挥喵等不受前两条的约束。
> 4. 在此分支中，当一组图片相互叠加才能形成完整立绘时，视内容命名人物，舰装，可放在【】里。
> 5. 当一组图片中存在包含舰装的完整立绘时，将其中无舰装的立绘命名为【无舰装】。
> 6. 当【】内存在多个要素时，按照【黑.无背景.无人物.无舰装.和谐.插画】的顺序依次命名。
> 7. 舰名中出现的所有英文字母均转为小写。
> 8. 立绘名中出现的“ . , ? ! ”等半角特殊字符均转为其全角形式“ 。，？！”。
> 9. 进行本地化时，应以图片内容为主，原始文件名和本命名规范仅作参考。
> 10.在部分带有`_front`的文件中，代表此整体是位于人物前面（正面视角），所以，不带`_front`的同名文件应加上 后 。

## Special Thanks

@[Goodjooy](https://github.com/Goodjooy)

@[OwKali](https://github.com/OwKali)

@[OSSSY152](https://github.com/OSSSY152)

可能的issues和requests。
