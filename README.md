# 1.16.5个人材质整合备份  
# 资源包清单(待更新……)  
## 自制  
[隐形蝙蝠](https://github.com/Oururis/IBat)  
透明盔甲  
菜单透明(Transparent+GU菜单没有透明就自己做了一个)  
[AppleSkin2.4.0+mc1.16.5](https://minecraft.curseforge.com/projects/appleskin)完全汉化（语言文件仅汉化了设置菜单，编译版本汉化了设置界面悬浮提示）  
[Autofish0.9.2](https://minecraft.curseforge.com/projects/autofish)完全汉化（非语言文件汉化，而是编译版本）  
[BBOR2.4-1.16.3](https://www.curseforge.com/minecraft/mc-mods/bounding-box-outline-reloaded)汉化补充  
[Borderless Mining1.0.6+1.16.2](https://github.com/comp500/BorderlessMining)完全汉化  
[Color Me Outlines1.0.0](https://www.curseforge.com/minecraft/mc-mods/color-me-outlines)完全汉化  
~~[lightoverlay5.8.1](https://www.curseforge.com/minecraft/mc-mods/light-overlay)汉化~~语言文件还在，因为兼容问题放弃使用了  
[InvMove0.8.4](https://github.com/PieKing1215/InvMove)完全汉化  
[MaLiLib0.10.0-dev.21+arne.1](https://www.curseforge.com/minecraft/mc-mods/malilib)汉化补充  
[inventoryprofiles0.4.2](https://www.curseforge.com/minecraft/mc-mods/inventory-profiles)部分汉化  
[roughlyenoughitems5.9.2](https://www.curseforge.com/minecraft/mc-mods/roughly-enough-items)汉化补充  

## [vanillatweaks](https://vanillatweaks.net/picker/resource-packs/)  
平滑的羊毛|高清盾牌图案|降低紫珀块饱和度  
多样式颜料|篝火动画|燧石箭尖|更好的基岩
多样式的书架|书架连接纹理|多样式的连接书架
树苗生长可视化|低盾|闪烁的附魔
3D日月|凋零之心|ping指示颜色
彩虹XP条|船桨颜色与船身同步|合成书按钮修正
统计信息图标修正|仙人掌底部修正|烈焰人底部修正
手持物品修正|切石机动画修正|村民斗篷  
## 其他材质包  
[醉梦巅峰汉化Masa四件套](https://space.bilibili.com/13205801)（修改了一部分）
[BetterVanillaAnimals](https://www.curseforge.com/minecraft/texture-packs/better-vanilla-animals)更真实的原版动物  
[Transparent+GU](https://www.curseforge.com/minecraft/texture-packs/transparent-gui-ultimate)透明GUI  
[Xekr红显](https://www.curseforge.com/minecraft/texture-packs/xekr-redstone-display)的酿造台界面（改为透明）  
~~[blockpixel](https://www.curseforge.com/minecraft/texture-packs/blockpixel)部分材质~~  

---

# 格式化代码（Minecraft Formatting
——来自[**Minecraft Wiki**](https://minecraft.fandom.com/zh/wiki/%E6%A0%BC%E5%BC%8F%E5%8C%96%E4%BB%A3%E7%A0%81#%E9%A2%9C%E8%89%B2%E4%BB%A3%E7%A0%81)  

格式化代码（Formatting code），又称颜色代码（Color code），能使在游戏中加入含颜色和格式信息

| 代码 | 官方名称      | MOTD代码 |
| ---- | ------------- | -------- |
| §0   | 黑色          | \u00A70  |
| §1   | 深蓝色        | \u00A71  |
| §2   | 深绿色        | \u00A72  |
| §3   | 湖蓝色        | \u00A73  |
| §4   | 深红色        | \u00A74  |
| §5   | 紫色          | \u00A75  |
| §6   | 金色          | \u00A76  |
| §7   | 灰色          | \u00A77  |
| §8   | 深灰色        | \u00A78  |
| §9   | 蓝色          | \u00A79  |
| §a   | 绿色          | \u00A7a  |
| §b   | 天蓝色        | \u00A7b  |
| §c   | 红色          | \u00A7c  |
| §d   | 粉红色        | \u00A7d  |
| §e   | 黄色          | \u00A7e  |
| §f   | 白色          | \u00A7f  |
| §k   | 随机字符      | \u00A7k  |
| §l   | **粗体**      | \u00A7l  |
| §m   | ~~删除线~~    | \u00A7m  |
| §n   | <u>下划线</u> | \u00A7n  |
| §o   | *斜体*        | \u00A7o  |
| §r   | 重置文字样式  | \u00A7r  |
| \n   | 换行          | \n       |

在Minecraft中，可以以分节符号（§）产生带色文字  
于Windows中，按`Alt` + `NUMPAD0` `NUMPAD1` `NUMPAD6` `NUMPAD7`或`Alt` + `NUMPAD4` `NUMPAD1` `NUMPAD4` `NUMPAD5` `NUMPAD2`  
于macOS中，按下 `⌥ Option` + `6`  
于Linux中，按下 `Compose` + `S` + `O` 
而在基岩版中，分节符号能被输入进告示牌、世界名称、重命名栏及聊天栏而产生带色文字 且外部程序也能将其加入于其他位置

---
***颜色代码***  
Colors
不同颜色所对应的十六进制数字使用§+相应数字或字母可以得到对应的颜色例如，§e会显示为黄色

从服务器发送到客户端的消息中可以包含颜色代码，这允许不同目的的文本可以拥有颜色

分节符（§）对应的是十六进制数字，它能在客户端里显示文本时切换颜色

| 代码 | 名称         | 技术性名称    | 前景色 R | 前景色 G | 前景色 B | 前景色 Hex | 阴影色 R | 阴影色 G | 阴影色 B | 阴影色 Hex |
| ---- | ------------ | ------------- | -------- | -------- | -------- | ---------- | -------- | -------- | -------- | ---------- |
| §0   | 黑色         | black         | 0        | 0        | 0        | 000000     | 0        | 0        | 0        | 000000     |
| §1   | 深蓝色       | dark_blue     | 0        | 0        | 170      | 0000AA     | 0        | 0        | 42       | 00002A     |
| §2   | 深绿色       | dark_green    | 0        | 170      | 0        | 00AA00     | 0        | 42       | 0        | 002A00     |
| §3   | 湖蓝色       | dark_aqua     | 0        | 170      | 170      | 00AAAA     | 0        | 42       | 42       | 002A2A     |
| §4   | 深红色       | dark_red      | 170      | 0        | 0        | AA0000     | 42       | 0        | 0        | 2A0000     |
| §5   | 紫色         | dark_purple   | 170      | 0        | 170      | AA00AA     | 42       | 0        | 42       | 2A002A     |
| §6   | 金色         | gold          | 255      | 170      | 0        | FFAA00     | 63       | 42       | 0        | 3F2A00     |
| §7   | 灰色         | gray          | 170      | 170      | 170      | AAAAAA     | 42       | 42       | 42       | 2A2A2A     |
| §8   | 深灰色       | dark_gray     | 85       | 85       | 85       | 555555     | 21       | 21       | 21       | 151515     |
| §9   | 蓝色         | blue          | 85       | 85       | 255      | 5555FF     | 21       | 21       | 63       | 15153F     |
| §a   | 绿色         | green         | 85       | 255      | 85       | 55FF55     | 21       | 63       | 21       | 153F15     |
| §b   | 天蓝色       | aqua          | 85       | 255      | 255      | 55FFFF     | 21       | 63       | 63       | 153F3F     |
| §c   | 红色         | red           | 255      | 85       | 85       | FF5555     | 63       | 21       | 21       | 3F1515     |
| §d   | 粉红色       | light_purple  | 255      | 85       | 255      | FF55FF     | 63       | 21       | 63       | 3F153F     |
| §e   | 黄色         | yellow        | 255      | 255      | 85       | FFFF55     | 63       | 63       | 21       | 3F3F15     |
| §f   | 白色         | white         | 255      | 255      | 255      | FFFFFF     | 63       | 63       | 63       | 3F3F3F     |
| §g   | 硬币金[仅BE] | minecoin_gold | 221      | 214      | 5        | DDD605     | 55       | 53       | 1        | 373501     |

  
也可以通过在分节符(§)后附加字母的方式自定义文字格式分节符可以用在基岩版任何能输入文字的地方，也可以用在server.properties和pack.mcmeta文件里以及Java版的世界/服务器名称以及原始JSON文本中  

如果在格式代码后使用颜色代码，则格式代码的作用范围只能持续到颜色代码之前例如，`§cX§nY`会显示为![](https://s2.loli.net/2023/07/30/BoCRbW1jrImTiyg.png)，而`§nX§cY`会显示为![](https://s2.loli.net/2023/07/30/JlYNfvD3rFQaKR2.png)因此，当使用颜色代码与格式代码一起使用时，确保首先使用颜色代码，并在更改颜色时重用格式代码

在基岩版中，在颜色代码后面的格式代码仍然生效此外，如果用了混淆代码而没有在行尾使用重置代码，客户端GUI会继续模糊MOTD传过来的文字和版本号显示：
§r可以用于重置文字样式例如：§nXXX§rYYY会显示为![](https://s2.loli.net/2023/07/30/leKXmPT4cY8Li9s.png)

| 格式效果 | Markdown代码示例      |
| -------- | --------------------- |
| §k       | `随机字符`            |
| §l       | **粗体**              |
| §m       | ~~删除线~~[仅Java]    |
| §n       | <u>下划线</u>[仅Java] |
| §o       | *斜体*                |
| §r       | `重置文字样式`        |

