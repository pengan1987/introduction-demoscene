# PC演示
今天是演示场景概论的第五课，这一节课的主要会围绕IBM PC兼容机展开，着重讨论90年代至今PC硬件的发展对演示程序的影响以及“new skool”演示程序在创作理念上与上节课讨论的“old skool”的不同。除了演示场景，在舞曲、说唱、嘻哈等流行文化场景里“school”也时常被拼写为“skool”，在《Let's settle this… Is it 'Old School' or 'Old Skool' ?》一文指出这种写法至少在流行文化的背景下“可以追溯到1984年ZX Spectrum和Commodore 64上的一款畅销的游戏——Skool Daze。”

Let’s settle this… Is it ‘Old School’ or ‘Old Skool’?
​909originals.com/2018/01/17/lets-settle-this-is-it-old-school-or-old-skool/

为什么单独讨论IBM PC兼容机？
我们在上一节课里介绍了许多不同类型的老式电脑上的演示程序，包括ZX Spectrum、Commodore 64、Amiga还有Atari ST等等在内的一系列老电脑，但为什么同样在80年代就已经出现的IBM PC及兼容机平台要专门开一节课来讲呢？这是因为IBM PC是90年代中期之后唯一仍被商业界广泛生产和持续发展的电脑平台。直到现在，每年仍然有新款的PC硬件被开发出来，并为PC平台带来更强的性能或更丰富的功能。

那么可能有人会好奇Macintosh是什么情况，从1984年初代Macintosh至今，其硬件平台经历过几次重大的更新，从最初的Motorola 68000升级到PowerPC，再由PowerPC升级到X86，再到今天的ARM，而每一次硬件架构的转换，其开发工具、软件API和硬件特性往往都发生了重大的变化。而这种变化足以让之后的Macintosh成为与以往型号完全不同的平台。


IBM PC兼容机是40年来从未断代的计算机平台
而在诸多的电脑平台中，只有IBM PC这个线索是连续的，从1981年至今，所有的IBM PC及其兼容机都使用x86的架构，BIOS调用也基本保持不变，PC硬件接口、输入输出设备及操作习惯，都保持了非常好的延续性。而PC硬件性能的持续提升也让为PC制作的演示程序很少遇到像Commodore 64那样硬性的性能限制：如果今年的硬件无法流畅运行某种效果，可能明年的新硬件就可以运行了。

因此我们去观看或比较PC demo时，就不能像讨论C64或ZX Spectrum演示程序那样假设所有的程序都是为相对一致的硬件开发的，而要考虑到开发者使用的是什么时期、何种规格的PC硬件。同时由于PC硬件性能的快速增长，在PC演示场景中，针对底层开发技巧的炫技的部分被削弱，而以可执行程序产生影音效果进行创造性表达的成分增加了。

除了硬件上有着40年的时间跨度，PC平台的软件环境跨度也极大，除了操作系统的不同外，高级开发环境，比如Java VM这类执行托管代码的虚拟机（Virtual Machine），和Flash Player这样的运行环境（Runtime）也创造了许多在IBM PC上执行，但有着各自不同创作限制和表达特点的子类别。

另外，由于PC演示场景起步较晚，所以与志愿盗版（warez）的联系较C64、Amiga等发展较早的类别更弱。即使许多参与演示场景的爱好者仍然会同时参与志愿盗版，但PC演示程序更多是为参加演示聚会及比赛制作，作为盗版软件“片头”（intro）的情况已经明显变少了。1993年3月Usenet中针对成立comp.sys.ibm.pc.demos 新闻组的投票征集帖子中，可以看到演示小组试图和盗版“划清界限”：

Please do not confuse these demo groups with pirate groups. These groups exist for the sole purpose of creating demos (and games) and do not engage in piracy. Pirate group do occasionally create an occasional small demo (a loader), but these are almost always of extremely inferior quality.

请不要将这些演示团体与盗版团体混淆。这些团体存在的唯一目的是制作演示（和游戏），并不从事盗版。盗版团体偶尔也会制作一些小型演示（加载器），但几乎都是质量极差的。
https://groups.google.com/g/comp.os.msdos.programmer/c/YzH9rdbKl6c/m/802iSxXo55AJ
由于场景的合法化，PC演示场景还得到了一些商业合作的机会，比如afri-demo就是由德国饮料品牌afri-cola开发的演示程序形式的广告。

德国饮料afri-cola的广告demo_哔哩哔哩_bilibili
​www.bilibili.com/video/bv1zS4y1p7cs

Amiga：曾经的多媒体之王
在1990年代之前，IBM PC并未被Demoscene社群广泛采用。作为倾向于商业用途的个人电脑，IBM PC缺少声音芯片和针对动画功能的优化。针对办公用途的PC兼容机往往选用大力神（Hercules，HGC）黑白显卡，牺牲彩色显示功能换取更高的显示分辨率。这其中一个重要的原因是彩色显示需要比单色显示大得多的显存：在黑白显卡上，一个像素只需要一个bit，即一个0或1就可以表示黑或白，而要实现16色显示，则需要4个bit。也就是说，在相同分辨率下，16色显示需要的显存容量是黑白的四倍，这在内存仍然昂贵的80年代是一笔不小的开销。


笔者的Mac Classic（左）和Mac SE（右）都是黑白机型
基于类似的原因，80年代大多数Macintosh也都只有黑白显示，包括80年代中期到90年代初流行的Macintosh Plus、Macintosh SE、Macintosh Classic等机型，支持彩色显示的Macintosh II价格昂贵，通常是前面几款Mac的两倍，因此极少有个人用户采用。

80年代流行的几款家用电脑的多媒体规格：

声音	图像
Apple II	单计时器（蜂鸣器）	16色,低分辨率，双视频页面8色,高分辨率，双视频页面
Apple IIGS	15通道数字音频（立体声）	低分辨率16色, 2页面切换, 40*40外加4行文本高分辨率4色（8色，但有重复）双视频页面双倍高分辨率：16色双视频页面超高分辨率（仅适用于IIGS）：每个扫描线4096色中选取16色
IBM PC	单计时器（蜂鸣器）	16/64色,低分辨率, 双视频页面16/64色,高分辨率，单视频页面
C64	三合音合成器	16色,低分辨率, 多视频页面
Mac	四合音数字音频（单声道）	黑白，高分辨率，单视频页面
Amiga	四合音数字音频（立体声）	4096色中选取32色，低分辨率，多视频页面
对于国内的电脑用户来说HGC显卡也并不陌生，在80年代末到90年代初国内使用的8088、80286级别的IBM PC兼容机往往都装有HGC显卡或其兼容型号，大陆常用的CCDOS和台湾常用的倚天中文系统都利用了HGC的高分辨率（640x408）图形功能来显示汉字，在HGC显卡的图形模式下，软件汉字系统可以使用16点阵字库显示25行40列汉字（或80列英文），能够兼容大多数英文DOS程序。但在重视视听效果的演示场景社群，Amiga电脑才是最受欢迎的“多媒体之王”，这种情况直到80年代末IBM PC‍‍平台上一系列新硬件的出现才得已转变。

PC的多媒体化
80年代后期，一系列新型PC硬件的推出促进了IBM PC兼容机的多媒体化，1987年IBM在PS/2电脑上推出的VGA显卡加入了“Mode 13h”，支持在320x200分辨率下同屏幕显示256色，这让PC兼容机在图像功能上具备了与Amiga竞争的实力。

今年早些时候Custom PC杂志《记忆中的VGA图形卡》（Remembering VGA Graphics）中描述了支持更多颜色的VGA显卡对软件开发者的影响：

Remembering VGA Graphics — Custom PC magazine
​custompc.raspberrypi.com/articles/retro-tech-vga

Luckily, those colours alone had a huge impact. The ZSoft Corporation’s PC Paintbrush and Electronic Arts’ Deluxe Paint II revolutionised professional graphics and computer art on the PC, thanks to 256-colour support. VGA also made CorelDRAW, launched in January 1989, a realistic alternative to the digital design packages appearing on Apple’s computers.
Meanwhile, for PC games, VGA was nothing short of transformative. Sure, the 64,000 pixels on your monitor looked a little chunky; however, with 256 colours, the artists working at leading developers, such as LucasArts, Sierra Online, Microprose, Electronic Arts and Origin Systems, were able to produce sprites that looked more like recognisably human (or inhuman) characters, and background scenery that could bring their game worlds to life.

幸运的是，（VGA显卡）仅靠支持的颜色就产生了巨大的影响。ZSoft公司的PC Paintbrush和Electronic Arts的Deluxe Paint II彻底改变了PC上的专业图形和计算机艺术，这要归功于256色的支持。VGA还使1989年1月推出的CorelDRAW成为苹果电脑上出现的数字设计包的真正可用的替代品。
同时，对于个人电脑游戏来说，VGA是不折不扣的变革。当然，显示器上仅有64,000像素看起来有点笨拙；然而，有了256色，在领先的开发商，如LucasArts、Sierra Online、Microprose、Electronic Arts和Origin Systems工作的艺术家们能够制作出看起来更像可识别的人类（或非人类）角色的精灵，以及能够使他们的游戏世界变得生动的背景景象。
同时PC的开放架构和充满竞争的第三方显卡市场，让VGA兼容型显卡的价格随着激烈的市场竞争而更加便宜，也更加强大：

By mid-1988 to 1989, the likes of Tseng Labs, Cirrus Logic, Chips and Technologies and ATi were entering the fray, and not only were they driving prices down to $339 US, but they were also adding new capabilities. These enhanced VGA cards added features to accelerate video, or increased the RAM to 512KB, and tinkered with the BIOS to cover more advanced resolutions, such as 800 x 600 in 16 colours or 640 x 480 with 256 colours.

到1988年中期至1989年，曾氏实验室（Tseng Labs）、Cirrus Logic、Chips and Technologies和ATi等公司加入了这场竞争，他们不仅将价格降低到339美元，而且还增加了新的功能。这些增强型显卡增加了加速视频的功能，或将RAM增加到512KB，并对BIOS进行了修补，以涵盖更先进的分辨率，如800 x 600的16色或640 x 480的256色。
在1992~1993年前后，欧洲市场上IBM PC的竞争力逐渐超过Atari ST和Amiga等电脑，这一时期的PC兼容机通常以1000英镑左右的售价销售。虽然同时期Atari ST和Amiga售价普遍在500英镑以内，但PC兼容机几乎都配置有独立的显示器和硬盘，而这些配置对于那些不仅仅由于游戏的用途而购买电脑的用户来说显然是更加重要的配置。

Stack Exchange上的文章回顾了90年代初PC和Amiga等家用电脑平台的价格 https://retrocomputing.stackexchange.com/questions/22387/cost-of-pc-vs-amiga-500-in-europe


1993年，PC兼容机已经成为价格上有竞争力的游戏设备
而利用PC播放声音的外设也开始出现，比如1987年底上市的Covox Speech Thing是一个电阻梯（Resistor ladder）数模转换器，可以连接在PC打印机接口上播放数字音频，Covox结构简单，爱好者自制的仿制品也非常流行，《The Covox years》一文中提到1992年的demo程序Crystal Dream的自述文件中，就附带了简化版的Covox电路图，而制作这样一个设备的成本只需要几美元。

[covox]怀旧并口声卡lptdac焊接制作测试_哔哩哔哩_bilibili
​www.bilibili.com/video/BV1JD4y1Q7cC

1987年上市的还有AdLib声卡，它的主要功能是为PC提供一颗Yamaha YM3812 FM合成器芯片，而1989年的Sound Blaster“声霸卡”则在兼容AdLib的同时提供了完整的数字音频录制和回放功能，并在90年代逐渐成为PC声卡的事实标准。

【8-Bit Guy】两款老声卡以及SID芯片的复刻品评测（AdLib、Innovation SSI-2001和SwinSID Ultimate）_哔哩哔哩_bilibili
​www.bilibili.com/video/BV1Js411J7wp

90年代初，一些为IBM PC兼容机开发的演示程序在声音效果上开始向Amiga看齐，Future Crew在1990年发布了Slideshow I被认为是历史上第一个带有“Amiga Sound”（即四通道音频）的PC演示。它除了支持Sound Blaster声卡之外，还支持Covox和PC喇叭。

FutureCrew Slideshow I 演示_哔哩哔哩_bilibili
​www.bilibili.com/video/bv1ZG411s7S1

同时在Amiga电脑上流行的音轨序列（Tracker）式音乐制作软件也出现在PC兼容机上，并随着PC性能的改进，功能逐渐超越Amiga平台。在芬兰赫尔辛基大学《音乐》（Musiikki）期刊上，Markku Reunanen曾发表论文《Trackerit: paradigman synty, kukoistus ja myöhemmät vaiheet》（Tracker：范式的诞生、繁荣和后续），其中这样描述PC Tracker的发展：

Ensimmäiset PC-pohjaiset trackerit, kuten Scream Tracker 2.2 (1990), ModEdit (1991) ja Whacker Tracker (1992) jäivät vielä esikuvistaan jälkeen niin käyttöliittymän, toiminnallisuuden kuin äänenlaadunkin osalta. Vuosikymmenen puoliväliin tultaessa tilanne kuitenkin muuttui, kun vuonna 1994 julkaistiin demoskenen piirissä sekä Scream Tracker 3 (ST3) sekä Fasttracker II (FT2). Näistä Fasttracker II on selvästi läheisempää sukua Amigan ohjelmille: raidat, soittojärjestys ja komennot muistuttavat läheisesti edelleen esimerkiksi ProTrackerin eri versioita (kuva 6). Tietokoneiden kasvanut laskentateho, muistin määrä ja uudet PC-äänikortit mahdollistivat kuitenkin muun muassa kanavamäärän kasvattamisen 32:een, 16-bittisen tarkkuuden, vapaan panoroinnin ja instrumenttien verhokäyrät. FT2:n ilmeisimpiä seuraajia PC-trackerien saralla ovat Skale Tracker (2005) ja monella alustalla toimiva avoin MilkyTracker, sekin vuodelta 2005.

第一批基于PC的Tracker，如Scream Tracker 2.2（1990年）、ModEdit（1991年）和Whacker Tracker（1992年），在用户界面、功能和声音质量方面仍然落后于其（Amiga电脑上的）前辈。然而，随着1994年Scream Tracker 3（ST3）和Fasttracker II（FT2）的发布，让情况在（90）年代中期发生了变化，这两款产品都出现在演示场景中。其中，Fasttracker II显然与Amiga程序的关系更为密切：轨道、振铃顺序和命令仍然与ProTracker的各种版本密切相关，例如（图6）。然而，计算机计算能力的提高，内存量的增加，以及新的PC声卡的出现，使得通道数量增加到32个，16位精度，自由平移和乐器曲线等成为可能。在PC追踪器领域，对FT2最明显的继承者是Skale Tracker（2005年）和多平台开源的MilkyTracker，也是在2005年。
充满争议的PC平台
正如在PC Tracker软件中所体现出来的那样，在90年代中PC硬件性能的快速增长带来PC兼容机的大流行，并逐渐取代了这些‍‍Amiga和其他一些硬件在面向家用及游戏电脑市场上的地位，形成了今天常被游戏行业拿来与家用游戏机做对比的，以Intel + Windows组合为中心的“PC游戏”市场。

演示场景中使用PC作为制作平台的参与者也逐渐增加，1993年4月，Usenet新闻组comp.sys.ibm.pc.demos开通，记录下了许多PC演示场景中的早期讨论，其中争论最为激烈的话题有两个：分别是硬件性能和软件优化之争、以及是否接受Windows为代表的，面向硬件底层与面向系统开发之争，这种争议的结果，是PC演示场景最终分化为专注于老式电脑和底层开发技巧的“老学校”（old skool）和积极利用新式硬件和软件的“新学校”（new skool），直到今天，演示场景社群中较大型的聚会仍然会分别进行这两种类别的比赛。

性能与优化之争
PC硬件性能的快速增加挑战了演示场景长期以来以通过底层的软件优化来挑战硬件性能限制的传统。也引起了一些参与者的批评：

Where does it stop then? If it goes on like this, the future demos will support pentium only (or run decently on a pentium)! I think the limit MUST be drawn by a 486DX33 for now and in the near future. If your demo runs smooth on a 486DX2-66 and not on a 486DX33 i advise you to quit coding and learn to optimize (or learn assembly ;) ). (Scout/Success, comp.sys.ibm.pc.demos, 1994)

那么它在哪里停止呢？如果继续这样下去，未来的演示将只支持奔腾（或只能在奔腾上才运行良好）！我认为必须划定界限。我认为现在和不久的将来，必须以486DX33来划定限制。如果你的演示在486DX2-66上运行顺利，而在486DX33上却不能，我建议你停止编码并学习如何优化（或者学习汇编语言）。
(Scout/Success, comp.sys.ibm.pc.demos, 1994)
https://groups.google.com/g/comp.sys.ibm.pc.demos/c/nUJZBbiWISo/m/bP55Qfbn9D8J
Windows之争
而微软Windows也触发了爱好者的反商业化情节，论文《计算机演示——是什么让它们运转起来？》（Computer Demos - What Makes Them Tick?，Markku Reunanen，2010）中引用了Usenet新闻组中爱好者们的反应：

And I can't believe how the PC owners always do that what some companies (intel, microsoft) want: pay pay pay and get no adequate power. (FREAK, alt.sys.amiga.demos, 1994)

而且我无法相信PC机的拥有者总是按照某些公司（英特尔、微软）的要求去做：付钱付钱，却没有得到足够的权力。(FREAK, alt.sys.amiga.demos, 1994)

The demo scene is a totally different world than all the microsoft business windows crap. (R. Eijkelhof, comp.sys.ibm.pc.demos, 1994)

演示场景是一个完全不同的世界，完全不是微软商业窗口的垃圾。(R. Eijkelhof, comp.sys.ibm.pc.demos, 1994)

If someone starts to make Win95 demos, I dont have anything against it... But – please – don’t call it ’demoscene’. It would dishonourable. (Markus Aurala, comp.sys.ibm.pc.demos, 1996)

如果有人开始制作Win95的演示，我并不反对...... 但是-请-不要把它叫做 "demoscene"。那是不光彩的。(Markus Aurala, comp.sys.ibm.pc.demos, 1996)
也有爱好者从技术角度出发，认为Windows及微软当时提供的WinG、Direct 3D等图形API是一个围墙花园，让开发者们无法得到他们希望的对硬件底层的控制：

Coders want to be able to control their machines. Without an OS like DOS, they can't accomplish this, which would piss off a LOT of developers. Even Microsoft wouldn't be able to take the wrath of millions of power users should they kill DOS, without giving us a replacement with the same performance ability. WinG, for all its gains, just won't cut it.

程序员们希望能够控制他们的机器。如果没有像DOS这样的操作系统，他们就无法实现这一目标，这将会激怒很多开发者。即使是微软也无法承受数以百万计的高级用户的愤怒，如果他们杀了DOS而不给我们一个具有同样性能的替代品的话。WinG，就其所有的收益而言，根本无法实现。
(Chris Hargrove, comp.sys.ibm.pc.demos, 1994)
https://groups.google.com/g/comp.sys.ibm.pc.demos/c/KigmvEEB94U/m/-P6YxmWXVmcJ

Nothing that Windows95 does can't be done (much better) with dos, and what is more important, I get the complete control over the machine (with no overhead even): a thing that Windows' Direct-xxx will never really give.(Fabio Bizzetti,comp.sys.ibm.pc.demos, 1996)

Windows95所做的一切都可以用dos来做（做得更好），更重要的是，我得到了对机器的完全控制（甚至没有开销）：这是Windows的Direct-xxx永远不会真正给予的东西。
(Fabio Bizzetti,comp.sys.ibm.pc.demos, 1996)
https://groups.google.com/g/comp.sys.ibm.pc.demos/c/AEK--sZOZOc/m/UFWb7bNy3LsJ
这种对机器完全控制的追求和对大企业的不信任可以从70年代的大型主机黑客和电话飞客社群中找到，而更早的根源还可以追溯到嬉皮士运动队建制化的反抗，当这种反抗的精神和不同的技术社群结合时，就产生了不同的技术文化，对于通信爱好者来说，是电话飞客（phreaking）；对于网络爱好者来说，是网络黑客；对于编程爱好者来说，是开源软件；对于软件破解者来说，是志愿盗版（warez）；对于数字艺术爱好者来说，就是演示场景（demoscene）。

但这种反抗往往又有着许多自相矛盾之处，许多时候这种反抗往往表现为支持市场中较弱势的一方，却未必关心品牌的企业文化是否与其有着相同的意识形态。比如演示场景对Amiga和Atari ST的偏爱，开源软件社群90年代对Sun以及2000年代对苹果的偏爱等等，让整个场景中的意识形态呈现一种驳杂的状态。

尝鲜者还是守旧派？传播学上的理解
演示场景对新技术的态度在外界看来是充满矛盾的，演示场景的参与者看起来并不像大众理解中的守旧派：他们往往自身就是年轻的技术专家，同时演示场景社群自己也发展出一系列新的软件和硬件。那是什么原因让他们对场景之外的，特别是商业化的新产品保持怀疑乃至拒绝的态度呢？《计算机演示——是什么让它们运转起来？》一文在章节3.7中提到这一点，并将其总结为一种自我反思性（Self-Reflectivity）：

Self-consciousness of the demoscene is revealed by the high amount of reflection that takes place in its discussions (see Section 4.6.2). The community is clearly aware of its own existence, borders and dynamics. It has also taken a name for itself, the scene, to emphasize its uniqueness. External factors, such as changing society and technologies, constantly impose new challenges on the demoscene, which must react in a way or another. Numerous debates on diskmags, web forums and newsgroups have been dedicated to the future of the scene in a changing world. Such discussions already feature a meta level: the scene is referring to itself as a high-order entity instead of only its concrete manifestations such as productions and parties.

演示场景的自我意识体现在其讨论中所发生的大量反思上（见第4.6.2节）。这个社区清楚地意识到自己的存在、边界和动态。它还为自己取了一个名字——场景，以强调其独特性。外部因素，如不断变化的社会和技术，不断给Demoscene带来新的挑战，它必须以某种方式作出反应。在磁盘杂志、网络论坛和新闻组中的许多辩论都致力于讨论在一个不断变化的世界中场景的未来。这样的讨论已经有了一个元层面的特点：场景是把自己作为一个高阶的实体，而不仅仅是其具体的表现形式，如制作和聚会。
这显示出演示场景作为一个整体具有的一种身份认同，另外该文章也指出演示场景参与者与机器之间的关系不再止于实用的价值，更建立了一种情感联系，在《计算机演示》文中5.5.1章节中提到：

As suggested by Turkle (1984, 1997) throughout her work, computers involve people on an intimate and personal level, serving as mirrors of the human spirit. Several discussions observed in the course of this study were marked by their highly emotional tone. Mere resistance to change is not a sufficient explanation to why new, seemingly beneficial innovations have been so fiercely opposed. After all, we are dealing with young proficient computer users that have few problems when learning to use new technology. It would seem that computers indeed operate beyond an instrumental level, and that an emotional bond is cre- 100 ated between the user and the machine. Suggesting that a platform should be abandoned directly violates the bond and calls for counteraction.

正如Turkle(1984, 1997)在她的工作中所提出的，计算机在一个亲密的个人层面上涉及到人们，作为人类精神的镜子。在本研究过程中观察到的一些讨论，其特点是具有高度的情感色彩。仅仅是对变化的抵制并不能充分解释为什么新的、看似有益的创新会遭到如此激烈的反对。毕竟，我们面对的是年轻熟练的计算机用户，他们在学习使用新技术时几乎没有问题。看来，计算机的运作确实超越了工具层面，用户和机器之间建立了一种情感纽带。建议放弃一个平台的做法直接违反了这种纽带，需要采取反击行动。
文中还提到创新扩散理论（diffusion of innovations theory）可以用来解释演示场景对某种新技术的接受过程：

The general concepts of the diffusion of innovations theory (Rogers, 2003) can be applied to the demoscene’s adoption processes. When a new hardware or software platform appears, the innovators try them out and release experimental productions, but the majority needs more time to adopt, as can be observed for example in the production catalog of pouet.net. It is only after the opinion leaders adapt that the new innovations start to gain momentum. High-profile productions, made by famous groups (early adopters) for a new platform, awaken the interest of the community, and when critical mass is achieved the majority will eventually follow.

创新扩散理论（Rogers, 2003）的一般概念可以应用于Demoscene的采用过程。当一个新的硬件或软件平台出现时，创新者会尝试它们并发布实验性产品，但大多数人需要更多的时间来采用，例如在http://pouet.net的生产目录中可以看到。只有在意见领袖适应之后，新的创新才开始获得动力。由著名团体（早期采用者）为一个新平台制作引人注目的作品，并唤起社区的兴趣，当达到临界质量时，大多数人最终会跟进。
对于IBM PC平台来说，Future Crew开发的Second Reality就是下文中所提到的“引人注目的作品”，它的出现推动了更多参与者从其他家用电脑转移到IBM PC平台。而对于Windows平台来说，Elitegroup或者farbrausch起到了类似的作用，这两个小组联系密切，相当一部分Farbrausch成员来自Elitegroup。

注：“幽灵古堡”是国内爱好者在对演示场景一知半解的情况下给Farbrausch团队2000年的作品 fr-08: .the .product 起的中文译名，在2021年竟然还能在B站上有百万点击量，论标题党的重要性( ╯□╰ )

《计算机演示》一文还转述Margrethe Aune的观点认为演示场景内围绕新技术的讨论体现的是社群参驯化技术的过程：

Aune (1996) discusses the adoption process from a domestication standpoint: how do new technologies such as computers become parts of everyday life? Aune’s third definition of domestication contains an interesting connection to the demoscene activities: ”To tame or bring under control”. The striving for control over the machine is a common theme in the scene discourse. The arrival of a new platform means loss of control and increased uncertainty, which can only be conquered by mastering the new tool. Another relevant observation made by Aune is that domestication happens on many levels (individual, household and society). Likewise, a demoscene member is part of a group and the community as a whole when making his personal decisions. The individual does not operate in a void, but constructs his relationship to new technology through negotiation with others.

Aune（1996）从驯化的角度讨论了采用过程：计算机等新技术如何成为日常生活的一部分？Aune对驯化的第三个定义包含了与Demoscene活动的有趣联系：“驯服或控制”。争取对机器的控制是现场话语中的一个共同主题。一个新平台的到来意味着控制权的丧失和不确定性的增加，只有通过掌握新工具才能征服它。Aune提出的另一个相关意见是，驯化发生在许多层面（个人、家庭和社会）。同样地，一个Demoscene成员在做出个人决定时，是群体和整个社区的一部分。个人并不是在空虚中运作，而是通过与他人的协商来构建他与新技术的关系。
演示场景是观察人们接受并采用某项技术的好场域，相信海外学者们对演示场景的研究，也会对其他技术社群的讨论产生启发。

3D加速
即使Demoscene对于Windows、高性能硬件和高级API有一系列争议和抗拒的过程，‍但最终还是演示场景还是接受了这些逐渐成为主流的技术。这其中的一个契机是3D加速卡带来的图像表现力的飞跃：仅靠CPU难以实现的快速运动的、真彩色的3D场景。

由于3D加速卡并不像x86处理器那样有着统一而公开的汇编指令集和详尽的技术手册，演示场景中的开发者们不得不通过更高级的API，比如Glide、OpenGL或Direct 3D来调用3D加速卡，这也促成了演示场景中开发实践的转变：从强调贴近硬件规格的底层编程技巧转向系统级编程。相比采用新或旧的电脑硬件平台，这种开发实践的不同才是“new skool”和“old skool”演示最大的区别。

3D演示程序中的许多效果与3D加速卡的性能密切相关，比如3D演示中时常出现一类被称作“飞跃”（fly-by）的效果，通常展示穿越隧道的场景，这些场景运行的帧率就与显卡的填充率（fill-rate）密切相关。这也让3D演示程序有了实用的功能：作为显卡的基准测试（benchmark）程序。

经典老软件：3dmark99demo模式，感谢名单里的厂商消失一半了吧_哔哩哔哩_bilibili
​www.bilibili.com/video/BV1LX4y1A7nn?share_source=copy_web

一些来自Future Crew演示小组的成员在1995年成立了游戏公司绿美迪娱乐（Remedy Entertainment），并在1997年制作了演示程序Final Reality作为评测3D加速卡性能的基准测试程序，随后这一业务被从绿美迪分离，成为专注于开发基准测试软件的Futuremark，而Final Reality的续作就是最为流行的显卡测试工具3DMark系列。

演示制作工具
而伴随着“new skool”演示向系统级编程的转向而来的，是演示制作方式的变化，许多游戏行业的制作的工具和流程进开始进入到Demo制作当中，同时也出现了一类专门用于制作演示程序的工具软件，即Demotool。

曾经参加过Elitegroup和Farbrausch小组的Dirk Jagdmann（Dr. Detroit/doj）在2008年的幻灯片里介绍了Kasparov和fr-08等1999~2000年间巨大影响的PC demo的制作流程，其中就介绍到制作Kasparov演示程序时开发小组曾利用SoftImage 3D‍‍进行建模、用Photoshop制作纹理贴图、用FastTracker II制作音乐。而在另一个演示程序fr-08（也就是国内流传的《幽灵古堡》）中，则使用了基于MIDI和Logic Audio（Logic Pro的前身）的音乐制作流程、和自行开发的V2软件合成器。

delivering superior consumer technology since 2004
​www.1337haxorz.de/products.html

从上面的例子我们看到，在素材准备的过程中“new skool”演示小组与游戏开发团队所作的事情已经非常接近了。而“Demotool”则可以理解为专门为演示程序设计的“游戏引擎”，在Jagdmann的幻灯片里，以Farbrausch小组的第一款制作工具Generator为例介绍了演示合成（demo composition）工具的基本功能，即图形化的演示脚本编辑器，它提供图形界面的编辑器用来组织演示引擎所支持的命令，包括生成纹理和对模型的几何操作。


制作fr-08所使用的Generator工具
fr-08，即《幽灵古堡》的主页：a demo in 63.5 kb

Farbrausch小组开源了他们更多演示的资料：https://github.com/farbrausch/fr_public

脚本引擎和图形化脚本编辑器的出现大大降低了制作PC演示程序的门槛。2004年6月，Farbrausch公开了Generator的后续产品，最成功的演示制作工具之一：.werkkzeug1，这也是唯一被2000年代中期国内demo爱好者所了解的演示制作工具。但值得注意的是.werkkzeug1在海外并不是第一个被演示场景社群广泛使用的图形化演示合成类Demotool，名为moppi的演示小组早在2000年就公开发布了图形化的制作工具Demopaja，爱好者几乎无需编码即可制作出可以运行的演示程序。

moppi demopaja
​moppi.inside.org/demopaja/

由于演示制作工具的流行，到2000年代中期，演示场景中至少“new skool”的部分正在发生这样一种转变：编程技巧的炫技被削弱，而为对内容视听表现力的关注则被增强了。更多Demotool的资料，可以在这里找到：

https://github.com/psykon/awesome-demoscene

https://peisik.untergrund.net/engines/

Linux和Mac
目前演示场景中大多数PC demo程序都是为Windows开发的，但正如前面所说的，出自Warez社群的演示场景天生带着反商业化的情节，并不会特别的偏爱微软的产品。那么在演示场景中Linux和Mac到哪里去了呢？当然，一些演示场景的参与者确实开发过非Windows平台的作品，比如Faemiyah演示小组就制作了许多可以在Linux和BSD操作系统上运行的demo，但相比Windows上数量庞大的作品而言，这些非Windows平台的作品显然是太少了。

GitHub - faemiyah/faemiyah-demoscene: Meta-repository, productions included as submodules
​github.com/faemiyah/faemiyah-demoscene

一个原因是大多数的Demo是闭源的，而只有Windows对旧软件保持着很好的二进制兼容型。Linux发行版更碎片化，也更容易产生软件库的依赖冲突。在http://pouet.net中爱好者们曾对使用Linux其进行过多次讨论，许多参与者认为Linux版本的碎片化和依赖的不确定性是导致演示制作者和比赛组织者更倾向Windows平台的重要原因：

If you try running older (especially closed source) Linux productions, you'll soon realize that you'll be in a world of pain when trying to scavenge the libraries that are linked but not included in the binary distribution. It's sucking slowly the life out of you when it takes more time to get the production running than the production's actual play time.
If cross compiling production to multiple systems is an easy thing to do with the demo making platform X then why not release it in less used desktop operation systems as well. Otherwise than that targeting productions to the most popular operating systems is much more fun since more people can see the actual production.

如果你尝试运行旧的（尤其是封闭源码的）Linux作品，你很快就会意识到，当你试图搜集那些被链接但不包括在二进制发行中的库时，你会陷入痛苦的世界。当让作品运行的时间超过制作的实际播放时间时，它正在慢慢吸走你的生命。
如果交叉编译作品到多个系统是一件很容易的事情，那么为什么不把它发布到不太常用的桌面操作系统上。否则，将作品定位在最流行的操作系统上会更有趣，因为更多的人可以看到实际的作品。（Waffle）

The problem is that desktop GNU/Linux is barely a suitable platform because it lacks binary compatibility. Too many distros and too many configurations (even for different processors) and, of course, a hell of libraries that are not the same among all "popular" distros and can change in the next update.
Has anyone tried to execute a linux demo from 2004 in 2014?

问题是，桌面GNU/Linux几乎不是一个合适的平台，因为它缺乏二进制兼容性。太多的发行版和太多的配置（甚至针对不同的处理器），当然，还有大量的库，这些库在所有“流行”的发行版中都是不一样的，而且可能在下一次更新中改变。
有没有人尝试过在2014年执行2004年的Linux演示？（Ham）

Linux has been (and is) a pain in the ass from the view of a compo organizer.
Even if there are the required libs available on the system, you often have to introduce symlinks and other dirty hacks to make it work (e.g. the guys who did the intro linked it to a certain version of a lib under a certain distribution and you have a more current version of that lib on a different distribution, which is hopefully compatible).
Under windows you have a total DLL hell but it's still more painless most of the time.
Instead of writing a linux port, even writing code that runs with Wine seems more reliable regarding long term compatibility (as long you use OpenGL, iirc DX9 stuff also worked to a certain level).

从比赛组织者的角度来看，Linux一直是（现在也是）一个麻烦的地方。
即使系统上有所需的库，你也经常要引入符号链接和其他肮脏的黑客式修改来使其工作（例如，做片头的人将其与某个发行版下的某个库的某个版本相连接，而你在另一个发行版上有该库的最新版本，然后希望它们能兼容）。
在windows下，你确实会面对DLL地狱，但在大多数时候还是比较省事的。
与其写一个linux一直，甚至写一些能在Wine上运行的代码，在长期兼容性方面都似乎更可靠（只要你使用OpenGL，我想DX9的东西也能在一定程度上发挥作用）。（las）
https://www.pouet.net/topic.php?which=9923&page=1
而且，即使是那些公开承认自己不喜欢Windows的爱好者，也承认Windows是更适合demo的平台

Personally, I use Linux almost exclusively, but I can certainly understand why Windows is the preferred platform of many:
Pros:
- more stable library ABIs (APIs change on both worlds)
- thus easier to make size-restricted stuff such as 4k/64k intros that usually work from OS version to other
- some tools related to size-restricted stuff (Crinkler) available on Windows
- some advantages in the "I just want to open a window and draw stuff in it", under Linux you almost certainly need some 3rd party lib (SDL, glfw) unless you want to lose your sanity. SDL is pretty standard nowadays, but some people might start bikeshedding/arguing about 4ks/64ks depending on whatnot 3rd party libs.
- OpenGL vs DirectX .. maybe not an issue in some ways, but possibly in others. creating a context can be pain without 3rd party lib again.
- the rather sad state of GL support in Linux (Mesa does not yet support recent OpenGL versions), so either you target only proprietary NVidia drivers or just forget about it practically :P
Cons:
- it's Windows
Just my personal view, and this from a guy who can't stand using Windows as a desktop OS :D

就个人而言，我几乎只使用Linux，但我当然可以理解为什么Windows是许多人的首选平台。
优点。
- 更稳定的库ABI（两个世界的API都在变化）
- 因此更容易制作尺寸受限的东西，如4k/64k的介绍，通常可以在不同的操作系统版本中使用。
- 一些与尺寸限制有关的工具（Crinkler）在Windows上可用。
- 在 "我只想打开一个窗口并在里面画东西 "方面有一些优势，在Linux下你几乎肯定需要一些第三方lib（SDL，glfw），除非你想失去你的理智。SDL现在是相当标准的，但有些人可能会开始骑自行车/争论4ks/64ks的问题，这取决于第三方lib的情况。
- OpenGL与DirectX......也许在某些方面不是问题，但在其他方面可能是问题。如果没有第三方lib，创建一个上下文是很痛苦的。
- 在Linux中支持GL的状况相当糟糕（Mesa还不支持最近的OpenGL版本），所以你要么只针对NVidia的专有驱动程序，要么就干脆忘掉它吧。
缺点。
- 它是Windows
这只是我的个人观点，而且是一个无法忍受使用Windows作为桌面操作系统的人说的 :D（ccr）
这一回应也提到了演示制作者们偏向Windows一些其他的理由，比如Windows有对开发者来说更易用的DirectX API和更加完善的硬件驱动支持。Windows的这些优势不仅仅相对于Linux，相对于任何时期的Mac也是存在的。对于演示场景甚少使用Mac的情况，爱好者们也曾经进行过讨论：

This is certainly one of the biggest reasons why I haven't made a Mac demo yet.. I got all my stuff on the PC, and I really, really, really dislike XCode and I can't be arsed to actually write makefiles and whatever to make my demos on Mac, while I can just boot up the PC and work on that. I'm not especially fond of Microsoft products but Visual Studio is the one thing they got absolutely right.
Not to mention DirectX. OpenGL on Mac is better than it's on PC (a lot less hardware and drivers to worry about), but it's still OpenGL..

这当然是我还没有制作Mac演示的最大原因之一。我所有的东西都在PC上，而且我真的、真的、真的不喜欢XCode，我没有精力去写makefiles之类的东西来在Mac上制作我的演示，而我可以直接启动PC并在上面工作。我不是特别喜欢微软的产品，但Visual Studio是他们完全正确的一件事。
更不用说DirectX了。Mac上的OpenGL比PC上的好（要担心的硬件和驱动少很多），但它仍然是OpenGL。（ Preacher）

What everyone else said, plus from experience of making mac demos:
Some parties support mac as a platform, some don't. For breakpoint I was told a mac demo would have to go in the wild compo :/
The hardware is either what you want or not.. macs are actually not usually more expensive, but the choice is very limited. ...
xcode: well, I've not used visual studio much, and I'm a bad coder anyway, but I've been pretty impressed with it. Besides that, there's a LOT of goodness in the mac sdk that isn't available on windows. Core image gives you GPU accelerated 2d image processing (basically pixel shaders, with a few limitations and a few very nice bonuses. There's quartz composer, which is basically a demo tool (I did the 'numbers' demo in that for sundown). There's audio units (not tried them, but they sound good for demo making) and other stuff.

正如其他人所说的，加上制作mac演示的经验。
有些人支持mac这个平台，有些人不支持。就Breakpoint（德国的著名demoparty）而言，我被告知mac的演示必须放在“野生”类别的比赛里。
硬件要么是你想要的，要么不是。实际上，Mac通常不会更贵，但选择非常有限。……
xcode: 好吧，我没怎么用过visual studio，反正我是个糟糕的程序员，但我对它印象很好。除此之外，在mac的SDK中还有很多windows上没有的好东西。核心图像为你提供了GPU加速的2D图像处理（基本上是像素着色器，有一些限制和一些非常好的奖励。还有quartz composer，它基本上是一个演示工具（我为英国Sundown聚会做了 "数字 "演示）。还有音频单元（没有试过，但它们听起来很适合做演示）和其他东西。（psonice）
https://www.pouet.net/topic.php?which=5660&page=1
虽然针对Mac电脑的作品较少，但场景中的爱好者仍然有一段积极尝试在Mac上制作demo的时期，在2001年到2011年间，http://macscene.org和http://mac.scene.org成为演示场景中Mac爱好者聚集的主要网站，其中大多数作品都是为OpenGL API开发的。

硬件中立的跨平台Demo
在演示场景里，许多最为重要的争议是围绕着硬件展开的，比如前面提到的是坚守Amiga还是转移到PC、坚守486还是接受Pentium、Windows PC还是Mac等等。对硬件特性的探索和展示，特别是对老式电脑平台硬件特性创造性的利用，也时常成为演示程序的核心内容，但是硬件特性是否在场景中就有着某种至高无上的地位呢？

我想场景中的爱好者们真正关心的并非是硬件，而是平台，即程序运行的环境，其中包括了硬件规格和软件环境。编程是演示场景中主要的创作手段，无论是由人工编写代码还是通过可视化工具完成的编程，都会受到平台功能的限制。而对于比赛的组织者来说，指定比赛的平台即包含了大量未被明文写入比赛章程中的规则。

正如在《平台研究：常见问题解答》所指出的“平台研究是完全关于硬件的”是一个误解、Java和Flash这类运行环境（Runtime）同样也已被视作平台那样。对于演示场景中来说，为Java、Flash等硬件中立的平台制作的Demo作品也同样存在。这其中即包含了Flash这样广泛流行的平台，也包含了Alambik这样从未广泛流行的平台。爱好者们使用这些平台的一个重要原因，是通过网络传播的便利性：为这些平台开发的演示程序往往无需下载，可以直接在浏览器中观看。

一个使用Alambik技术的demo（需要老式浏览器和插件）：http://medcg.free.fr/woodsenders

一个使用Adobe Shockwave技术的demo（需要老式浏览器和插件）：https://web.archive.org/web/20120201070827/http://www.i-arts.com/darkzone/dz_awakv1.htm

而近年来，HTML5/Javascript网页技术也被广泛用于制作演示程序，这其中既有使用WebGL、three.js等开发的，接近现代PC演示程序的作品，也有效果上模仿老式电脑演示程序的作品。

CreativeJS网站介绍了一些Javascript demo：

Demoscene | CreativeJS
​creativejs.com/category/demoscene-2/index.html

WAB（We are back）网站展示了许多使用CODEF（Canvas Oldshool Demo Effect Framework） 框架制作的demo程序：https://wab.com/

CODEF框架官网：http://codef.santo.fr/

https://flashtro.com/ 则展示了许多使用不同网页开发技术制作的demo。

艺术形式还是数字工艺品？
演示作品是一新的艺术形式还是数字工艺品一直存在着争议。Demo作品中涵盖了多种表现形式：动画、音乐甚至还有诗歌，比如some bookprint and a broken heart（一些书页和一颗破碎的心，国内流传的名称为“爱之记忆”）和Heaven Seven（第七天堂）就包含了诗歌或歌词式的文本内容。但为什么主流的新媒体艺术展览和论文中却甚少提及Demoscene及Demo作品呢？《计算机演示——是什么让它们运转起来？》在其3.3.2节中尝试去解读新媒体艺术和演示场景的关系，文中写道：

By definition, demos are new media art: creative multimedia made with digital tools. However, there exists a gap between the demo community and the different genres of media art. Even a quick glance at media art publications (Grau, 2007; Tribe & Jana, 2007; Wands, 2006) reveals that demos are not part of the same discourse.

根据定义，演示是新媒体艺术：用数字工具制作的创造性多媒体。然而，在演示社区和不同类型的媒体艺术之间存在着差距。即使快速浏览一下媒体艺术出版物（Grau, 2007; Tribe & Jana, 2007; Wands, 2006），也会发现Demo不属于同一话语。
《计算机演示》一文认为让演示场景有别于主流新媒体艺术的原因有下面几个方面：

其一是源流的不同：演示场景起源于电脑游戏和青少年，是作为一种青年文化出现的；而其他类型的新媒体艺术往往有其传统艺术的根源：如装置、录像艺术、雕塑和表演等传统艺术在新媒体艺术中皆有其对应的数字化实践。
其二是形式的不同：演示场景对作品有着繁复的规则和平台限制：观众对内容、可接受的帧率和风格也有明确的期望。同时演示作品也几乎没有互动性，这限制了演示作品的表现形式和范围。
第三是主题的不同：演示社区是明显的非政治性的：参与者更专注于炫耀性地展示视听效果，而不是当代艺术中时常被强调的行动主义。
精英主义的褪去
演示场景来自于早期的黑客社群和志愿盗版（warez）社群，它们与许多技术社群一样，是相当精英主义的：它有点像西方大学里普遍存在的兄弟会，一个新加入者往往需要跨过相当高的门槛才会被完全接受，内部存在着繁复的规则，并对场景之外的人持有一定程度的排斥。在早期黑客、飞客（hacking/freaking，在一些场合统称为“hp”）BBS社群中，经过“考验”的熟练用户被称作“精英”（Elite），而新手或场景之外的人被称作“瘸子”（Lamer）。

随着商业互联网的普及，许多早期的电脑发烧友社群都受到了冲击，其中的一个标志就是在Usenet新闻组用户中，被称作“eternal september”（永恒九月）的事件：1993年九月，AOL美国在线开始向其用户提供Usenet服务，商业ISP用户往往并不熟悉在之前以大学师生为主体的Usenet社群的网络礼仪，这些用户的不断涌入明显打乱了Usenet社群既有的规则和秩序。

而对于Demoscene社群来说，在这一时期则面临着开发方式和观赏体验带来的双重冲击下参与者的流失：

对于开发者来说，高级开发工具，包括demotool和游戏引擎的运用在加速创造新的演示效果的同时显著削弱了底层开发者的优势。存储容量和网络传输速度的提升也让面向容量（size-coding）的编程技巧早已不再具有实际价值，反而成为对创作“不必要的”约束。
对于观赏者来说，传统意义上的演示程序内容空洞、表现力也较为局限，许多效果需要相应的技术背景才可以理解，存在着较高的观看门槛。
蓬岸 Dr.Quest：Demoscene漫谈：是什么让Demo变得无聊
65 赞同 · 10 评论文章

2010年，研究者Ville-Matias Heikkilä发表了《演示艺术的未来。2010年代的Demoscene》（The Future of Demo Art: The Demoscene in the 2010s）一文对演示场景在进入90年代之后的变化进行了总结：

The Future of Demo Art: The Demoscene in the 2010s
​viznut.fi/texts-en/future_of_demo_art.html
首先是硬件和多媒体软件的进步让观看演示程序的体验不再独特，90年代初，演示曾经是最有表现力的计算机艺术形式，但在90年代末，已经有了大量可以在计算机上创作影音内容的现成的软件。
其次是科技行业的发展创造了大量编程的工作岗位，但工业界的编程工作往往不强调创意、独立性、试验性和底层技巧。
然后则是主流技术哲学的变迁，80年代大多数家用电脑预置编程环境，鼓励用户DIY编写程序。但90年代主流的技术哲学已经从“自己动手”退化为被动的消费主义，预先包装好的技术黑盒不断地挤压DIY活动的空间。
而文章认为接下来会对演示场景感兴趣的，是电脑发烧友之外的人群：

While demos have less and less appeal to the mainstream industry where the "hardcore" niches are gradually disappearing, they are becoming increasingly interesting to all kinds starving artists, grassroots hippies, radical do-it-yourself guys and other "countercultural" people. And if you want your creative work to make any larger-scale sense in the future world, I guess it might be worthwhile to start hang around with these guys as well.

虽然Demo对主流行业的吸引力越来越小，其中的 "硬核 "利基正在逐渐消失，但它们对于各种饥饿的艺术家、草根嬉皮士、激进的DIY爱好者和其他 "反文化 "人群越来越现得有趣。如果你想让你的创造性工作在未来的世界里有任何更大规模的意义，我想可能也值得开始和这些人混在一起。
《演示艺术的未来》一文在爱好者中引发了热烈的讨论，其中的一些说法展现出演示场景社群在1980年代中期到2010年之间的25多年里少见的危机感：

Sadly, the demoscene is bleeding and getting old. The influx of new blood is limited and the last thing we'd want is to drive whatever new blood is being injected to the "gene pool" away, by submitting it to a seemingly boring path.

可悲的是，Demoscene正在流血和变老。新鲜血液的涌入是有限的，而我们最不希望的就是把注入“基因库”的任何新鲜血液赶走，让它走上一条看似无聊的道路。（aMUSiC）
https://www.pouet.net/topic.php?which=7614&page=2
在《演示艺术的未来》一文的总结部分，提出对演示场景在2010年代发展趋势两大设想，即个人化和开放性：作品类型更加多元、表达更加个性化，而竞争性将被削弱；同时更多跨界的合作将更多地发生，场景内的演示作者将在场景之外活动，而“圈外人”也会有机会体验场景相关的文化。在现在看来，这种预判基本上是准确的。

2010：“后新派”演示
“后新派”（Post new skool）是我自己创造的概念，用来总结2010年代演示场景中一系列随着“造血自救”而出现的一系列新实践和新类别。

首先，继承老式电脑“old skool”时代演示场景的精神，关注底层开发和size-coding的成员将实践拓展到非家用电脑的新的平台上：如单片机、FPGA、开源硬件、幻想游戏机（fantasy console）等。这最终成为“野生”（wild）演示中一个颇为常见的类别，我们将在下一节课中详细讨论。

同时，那些专注于创造视听效果的参与者逐渐淡化以往对作品容量的关注，一些参与者较少的小型聚会以“综合图像”比赛合并了以程序容量划分的的4K、64K、Megademo（数MB容量的大型演示）等类别。高阶的开发工具也被广泛接受，Unreal，Unity，Notch等游戏引擎以及Processing，OpenFramkwork，ShaderToy等创意编程工具都出现在演示场景的作品中。

此外，现场编程（Live coding）项目被加入进Demo比赛中，为演示聚会提供了更具参与性和观赏性的内容。其中最常见的比赛项目是着色器对决（Shader showdown），最早出现在2013年波兰WeCan聚会中，并在2014年德国Revision聚会中得到广泛传播。

最后，2010年代的演示场景积极尝试降低其进入的门槛，为新入门的爱好者提供更多学习和上手的资源，从2013年起，芬兰阿尔托大学（Aalto University）数字媒体俱乐部开始举办一年一度的“图像松”（Graffathon），以Processing为主要开发工具向初学者介绍演示开发的技巧和特点。芬兰最大的演示聚会Assembly也开设了“单一效果竞赛”（One effect compo）单元接纳初学者参赛。

组织者为“图像松”准备的快速入门资源包：

GitHub - anttihirvonen/demoscene-starter-kits: Want to start making demos but don't know where to begin? Look no further!
​github.com/anttihirvonen/demoscene-starter-kits

正因为这些自我反思和改进，让演示场景并没有走向消亡，而是获得了持续的生命力。在下一节中，我们将介绍演示场景中的“野生”部分，那些由场景中的爱好者制作的不受平台规格限制的，更接近一般意义上的新媒体艺术的作品。