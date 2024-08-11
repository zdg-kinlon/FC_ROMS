# FC_ROMS

## FAQ

### 这个仓库的创建原因

我在寻找一款小时候玩过的游戏，由于中国大陆的游戏名翻译的很离谱，也有很多第三方修改后的版本，寻找的过程很缓慢，然后就发现了一本书《红白机完全档案》（ISBN：978-7-5139-2813-7，著：山崎功[日]），我的童年回忆被唤醒，在当时的中国大陆对于游戏的引进审核很严，只能玩到一些学习机和仿制机（小霸王）的游戏，无法体验真正的原版游戏，为了弥补这个遗憾，于是开通了这个仓库，把我能收集到的官方原作游戏，存放到这里，让所有人都可以很方便的获取，一起玩游戏。

PS. 最后我也没有找到要找的那个游戏，可能真的是中国内地的原创游戏，也可能是我真的老了，记忆不可靠了。

### 收集的游戏版本类型

根据《红白机终极档案》收录的游戏，包括NES（カセット，Nintendo Entertainment System）、FDS（ディスク，Famicom Disk System）官方发售的ROM文件。在此基础上还会收集一些后续还在发布的游戏（冒险岛4之后的游戏），比如《闪耀星夜DX（Kira Kira Star Night DX (J)）》，这是曾经的一线游戏开发者们献上的官方作品。

暂时不考虑收集官方发售版之外的其余版本，因为这些渠道太多了，而且还受到模拟器的影响可能无法运行。

### 关于游戏的附加文件资源

游戏的声音文件（播放器）暂时不考虑收集，主流的音乐播放器有高音质的音乐文件可以听。

游戏的电影文件（录像）暂时不考虑收集，这是做TAS或TPS游戏视频使用的文件，主流的视频网站即可观看。比如我关注的一些UP主（[HappyLee](https://space.bilibili.com/1497270)、[82电玩大叔](https://space.bilibili.com/24505689)、[一条小神棍](https://space.bilibili.com/94360081)），感谢他们的创作。

游戏的截图会考虑收集，会在时间富裕的情况下，在创建游戏目录清单文件时进行，不仅是游戏画面，连游戏介质图片一起收集。

### 游戏名的命名

由于个别游戏的名字有很多别名，尤其是中文，受到港澳台的游戏名和仿制机的干扰，为了尽可能统一，以日语的游戏名为准进行检索，其他地区（英语）的游戏名以从日语翻译后最相近的为准，中文游戏名以能从互联网直接便捷的检索到为准，尽量排除仿制机的错误游戏名，以游戏主界面和游戏介质的标签中出现的文字信息为游戏名的参照。

虽然以前有`T.O.S.E.C.`的命名规则，全名为“守旧派模拟游戏中心”（The Old School Emulation Centre），我会尽量不修改这些名称，选择`[!]`标记的版本（如果存在），使用归档文件的方式封装原始的文件名，然后修改归档文件的游戏名。

由于部分系统无法加载本地化系统语言以外的字符，文件名会使用英文，并且存放在有编号的文件夹中，通过一个目录文件，以发售时间对游戏进行排序，对应文件夹的编号，游戏的日文名、英文名、中文名、中文别名，然后利用系统的文件夹搜索功能进行定位游戏文件。以后会考虑做个脚本一键重命名为指定的语言游戏名，并且配上游戏截图，这要看我的空闲时间了。

PS. 如果出现类似于“西游记”翻译为“一个男人和八十一个女人的故事”这种情况，还请谅解。如果错的实在太离谱，我会及时更正，这个过程好比将好莱坞的电影名字直接翻译为中国内地上映的影视剧的名字那样更有挑战性。

### 归档文件的类型

归档文件不限于`zip`格式，也可能会使用`rar5`、`7z`，`Nestopia`模拟器提供了读取归档文件的扩展支持。未经压缩的游戏文件体积也很可观，即使那个年代开发游戏的内存是寸土寸金的情况下，开发者已经很努力的优化过，现如今存储设备的内存很庞大，但是考虑到网络传输的场景，会选择压缩比更好的归档格式，到时会说明使用什么版本的程序释放归档文件。

### 关于授权。

这个仓库是我顺手收集的仓库，游戏资源均来源于各大游戏论坛和社区，我是一名资源的搬运工和收集者，因此我使用了无授权的授权方式，任何人都可以自由的复制、修改、发布、使用、甚至再次封装并出售的商业形式分发，我也不会有任何收益，即使有收益也会进入公共领域。我会按网上获取的这些“原样”游戏资源进行提供，对此无法保证是否为正版，如果发现游戏资源的校验值与您手中确定为正版的文件校验值有差异，可以通过`Issues`纠正，最好附上正确的文件和证明，感激！

最后我不会在任何情况下，对任何索赔、损害或其他责任负责，因为我能免费获取到这些资源，并且没有明确在获取源被告知有版权的情况下。

对于仓库中使用的游戏模拟器的版权，归模拟器作者所有，可在软件的`Help -> About`中查看。

## 模拟器

我选择的模拟器为`Nestopia UE`，由于`Nestopia`模拟器兼容性是目前最好的选择，而且不同的系统平台也有支持，可惜在v1.40版本停止更新，感谢`Nestopia UE`模拟器在`Nestopia`基础上继续维护着，我在收集游戏时，会优先保证能在这个模拟器正常运行，至于其他模拟器，我无法保证，还请自行测试。

官方主页：http://0ldsk00l.ca/nestopia/

Github：https://github.com/0ldsk00l/nestopia

`VirtuaNES`也是个不错的模拟器，尤其是运行一些汉化的游戏，对于日语不好的玩家，使用这个模拟器是最好的选择，但是由于我暂时不会考虑收集汉化版和第三方修改版，想要体验游戏还是尽可能学习一门外语吧，这样也能很好的去找攻略，有的游戏会因为语言和文化环境的不同，对游戏的流程进行调整，毕竟以前的游戏不挣钱，挣钱的是杂志，想要能刊登在杂志中，内容必须入乡随俗，正所谓“卖攻略送游戏”的赚钱思路。

## 归档文件的版本

### UnRAR

UnRAR.dll: 用于从rar5归档中提取文件的库。

https://www.rarlab.com/rar/unrardll-701.exe

###  7z.Libs

7zxa.dll: 7z.dll库的紧凑版本，用于从7z归档中提取文件。

https://www.nuget.org/api/v2/package/7z.Libs/24.7.0 （nupkg:`bin -> x86 -> 7zxa.dll`）

## 磁碟机的BIOS

### disksys.rom

https://github.com/archtaurus/RetroPieBIOS/blob/master/BIOS/disksys.rom
