# VCB-Studio 整理组成品规范

此规范作为通常情况下的准则，但是具体情况请具体讨论并灵活应对，一定不要生搬硬套。遇到需要特别对待的情况或者不太确定好的处理办法，尽管在群里讨论。

遇到不适应具体情况的条目请立即提出修改意见。

## 总则

1. 整理环节包括 **分配** -> **整理** -> **复查**

2. **分配**

    1. 新的任务会反映在 Trello 上，整理组管理会做通知，可以主动接锅或者被分配
    2. 确认自己最近有时间可以接锅，质量优先，但是耗时也不能太久
    3. 在压制已经完工或者即将完工的时候，才能约定/预定任务

3. **整理**: 检查压制成品 -> 收集相关音乐和扫图 -> 组织目录结构和制种 -> 上传整理成品

    1. 每个项目的整理环节只由一名整理人员负责
    2. 原则上同一系列的番剧都由同一整理人员负责
    3. 整理完成时整理人员必须在整理组通知该消息并在度盘分享链接中附上 ATI 和 MP 截图
    4. `整理成品` 是按照规范进行组织的视频音乐扫图合集

4. **复查**: 检查整理成品 -> 指导错误修正 -> 确认项目成品

    1. 每个项目番剧的复查环节由项目总监和至少一名整理组复查人员负责
    2. 复查通过时复查人员必须在整理组通知该消息并贴出项目成品的链接

***

## 项目根目录

1. 类型

    如果项目包括分离的多季，则 `项目根目录` 是一个 `系列主目录`，每季度在其下对应一个 `季度主目录` \
    如果项目包括单季度或分割放送的多期，则 `项目根目录` 是一个 `季度主目录`

    **预料有后续季度时，命名上注意为后续季度留出空间以便日后做合集时减少重命名*

2. 命名

    `系列主目录`：[`TAG`] `SERIES` \
    `季度主目录`：[`TAG`] `SEASON` [`LEVEL`]

    `TAG` 是 **组名**，默认 `VCB-Studio`，有合作组的时候会在 Trello 卡片上标出，用 `&` 将各组连起来，原则上合作组组名前置，具体表示方式请参考 Trello 卡片 \
    `SERIES` 是 **系列共有名**，罗马音优先，不标 S1+S2+OVA 等季度标识，其后不标注画质级别 \
    `SEASON` 是 **季度专有名**，罗马音优先，注意官方大小写，不标 S1/S2 等季度标识 \
    `LEVEL` 是 **编码级别**，如下所示：

    项目类型| 画质级别
    --- | ---
    现标准版 HEVC Main 10 Profile | Ma10p_4K_HDR, Ma10p_1080p, Ma10p_720p …（根据正片分辨率）
    旧标准版 AVC High 10 Profile | Hi10p_1080p, Hi10p_720p …（根据正片分辨率）
    移动版 任何编码 | 1080p, 720p …（根据正片分辨率)

    **名称中避免出现基本拉丁字母和半角符号之外的字符，同时不要出现 `\/:*?"<>|` 中的字符。

    **遇到特殊情况在群里确认**

***

## 整体目录结构

`季度主目录` 下的文件目录结构：

内容 | 位置| 下属文件
--- | --- | ---
正片目录 | ~/|
正片视频 | ~/xxxx.ext | 视频文件和外挂音轨 .mkv/mka/mp4
字体包 | ~/xxxx.ext | .zip/rar/7z
特典目录 | ~/SPs/ |
特典视频 | ~/SPs/xxxx.ext | CM, IV, PV/Trailer, Menu, NCOP/NCED, SP, (Web) Preview
字幕文件 | 随对应视频放在同一目录 | .ass
扫图目录 | ~/Scans/ |
扫图文件 | ~/Scans/xxxx.ext <br> ~/Scans/xxxx/xxxx.ext | 蓝光扫图和其它相关扫图 <br> .webp/jpg
CD目录 | ~/CDs/ |
CD专辑 | ~/CDs/`CD`/ |
CD文件 | ~/CDs/`CD`/xxxx.ext <br> ~/CDs/`CD`/`CATALOG`/xxxx.ext | 音频文件 分轨信息 抓取日志 封面图 <br> .flac/tak/alac .cue .log .jpg/png
CD特典 | ~/CDs/`CD`/`CATALOG`.ext <br> ~/CDs/`CD`/`CATALOG`/xxxx.ext | 专辑特典视频（罕见） <br> .mkv
CD扫图目录 | ~/CDs/`CD`/Scans/ |
CD扫图文件 | ~/CDs/`CD`/Scans/xxxx.ext <br> ~/CDs/`CD`/Scans/`CATALOG`/xxxx.ext | 专辑扫图 <br> .webp/jpg

***

## 压制成品和字幕

1. `压制成品` 是从源 BD/DVD 抽取->预处理->重编码 得到的 视频/图片/音轨/章节/图形字幕 等文件

    1. 整理人员必须确认取得的压制成品与压制人员的本地文件一致
    2. 标准版成品必须携带原盘中所有有效内容，移动版只带正片和 NCOP/ED
    3. 整理人员必须使用成品对照组来检查压制成品，对照组通常只用于检测文件缺漏、音轨与章节错误 \
        成品对照组可选：[jsum 的 BDRip](https://u2.dmhy.org/userdetails.php?id=29940)

2. 压制成品和字幕检查标准，另见《VCB-Studio 制作规格》

    1. 视频

        内容：视频的内容和原盘一致，没有画面瑕疵，时长和原盘相等 或 帧率一样时总帧数相同。 \
        帧率：逐行扫描；原盘隔行扫描的视频，压制成品应正确地反交错并有正确的帧率，画面没有反交错出错瑕疵。常见帧率有 CFR 23.976 (24000/1001) 29.997 (30000/1001) 59.994 (60000/1001) FPS。MP 可以根据帧率将其以不同颜色表示。 \
        分辨率：除非 黑边切割 或 降采样 (低原生分辨率的 BD 降分辨率制作 / 移动版本采取低分辨率) 或 升采样 (480p/576p 的 DVD 做成 720p) 时，否则成品分辨率应和原盘一致。 \
        其它：保留有完整的编码参数信息，色彩矩阵参数 (BT601/709/2020)。

        **若视频长度小于 30 秒且 Mediainfo 检测到 23.976 (23976/1000) 等分母为 1000 的帧率，可以视为正确*

        视频特性 | 格式和编码
        --- | ---
        标准版本动态视频 | MKV @ [HEVC Ma10p](https://en.wikipedia.org/wiki/High_Efficiency_Video_Coding#Profiles)
        标准版本静态视频带BGM | MKV @ [AVC Hi444pp](https://en.wikipedia.org/wiki/H.264/MPEG-4_AVC#Profiles) 或 [HEVC Ma10p](https://en.wikipedia.org/wiki/High_Efficiency_Video_Coding#Profiles)
        标准版本静态视频无BGM | PNG
        移动版本动态视频 | MP4 @ [HEVC Ma/Ma10p](https://en.wikipedia.org/wiki/High_Efficiency_Video_Coding#Profiles) or [AVC Hi](https://en.wikipedia.org/wiki/H.264/MPEG-4_AVC#Profiles)

        **注意拓展名应该与实际容器一致，如 MKV/MKA = Matroska MP4/M4A = MPEG-4。MP 可以检测出此拓展名和实际格式不符的问题，并标以<span style="background: red">红色底色</span>。

        **当收到的视频不符合以上标准时，在整理群汇报，等待压制修正**

    2. 音轨

        要求音画对应，音画同步，数量齐全，时长完整，声道数/位深/采样率正确，音轨语言有标注且标注正确，AAC 音轨不能存在转码导致的偏移，内容没有损坏，空音轨应该删除。具体 转码/保留/封装规则 参见下表：

        源音轨 | 成品编码 | 封装位置
        --- | --- | ---
        **标准版本正片** | |
        主音轨 无损 2.0CH | FLAC | 内封 MKV
        主音轨 无损 >2.0CH | FLAC | 外挂 MKA
        主音轨 有损 | --- | 丢弃*
        主音轨 特殊 | 具体讨论* | 外挂 MKA
        评论轨 无损 2.0/2.1CH  | AAC CVBR 192kbps | 内封 MKV（如已有 MKA 则外挂）
        评论轨 无损 >2.1CH  | AAC CVBR 320kbps | 内封 MKV（如已有 MKA 则外挂）
        评论轨 有损 <512kbps  | 保持原样 | 内封 MKV（如已有 MKA 则外挂）
        评论轨 有损 >=512kbps  | AAC CVBR 320kbps | 内封 MKV（如已有 MKA 则外挂）
        **标准版本特典** | |
        动画 无损 | FLAC | 内封
        非动画 无损 2.0/2.1CH | AAC CVBR 192kbps | 内封 MKV
        非动画 无损 >2.1CH | AAC CVBR 320kbps | 内封 MKV
        非动画 有损 <512kbps | 保持原样 | 内封 MKV
        非动画 有损 >=512kbps | AAC CVBR 320kbps | 内封 MKV
        **移动版本*** | |
        主音轨 2.0CH | AAC CVBR 192kbps | 内封 MP4
        其它 | --- | 丢弃

        **同一视频的所有外挂音轨均封装在同一个 MKA 文件里，注意保持一致的轨道顺序* \
        **片源只有有损主音轨或 >2.0CH 无损主音轨的时候同样内封* \
        **特殊音轨：DTS Headphone X 转 FLAC，视障音轨规格按主音轨处理* \
        **对于部分特殊 MKV 移动版本/先行版本，具体情况具体讨论*

        **当收到的音轨出错时，在整理群汇报，联系压制返工。仅当确定对照组的视频与本组成品无偏移且处理正确时，才能使用对照组修正**

    3. 章节

        任何正片视频应该带有章节 \
        任何存在有意义章节的特典视频需要带有章节 (所有 CM/PV 集，多数 IV，许多 SP) \
        章节文件均内封于 MKV/MP4 文件

        **章节文本** 一般为 `Chapter XX`，顺序从 01 开始，也可以是具体意义的内容。对有章节的视频，如果缺少片头章节，应当补齐；如果存在片尾章节，应当移除；位置不正确的章节点，应当修正。章节语言标志根据章节文本内容决定 (例如只有英文则为 en)。如果章节文本使用了任何非 ASCII 字符，应当在 MKVToolNix 封装时为其选择合适的字符集。章节文字不要求还原 BD 菜单，如要手工输入请确保输入正确。常见语言缩写：英文 en，日文 ja，中文 zh。

        **当收到的成品中章节出错时，在整理群汇报，仅当确定对照组的视频与本组成品无偏移且处理正确时，才能使用对照组修正**

    4. 字幕

        原盘字幕：如有必带，内封于对应的 MKV 文件，MP4 带不了。 \
        合作字幕：标准版本，外挂 ASS 且带有字体包；移动版本，硬嵌。 \
        原则上尽量避免须使用 VSFilterMod 才能正确显示的特效字幕，并使用 ATI 检查字幕是否带有此类特效。 \
        字体包应带且仅带有合作字幕中所包含的所有字体。字体包推荐使用兼容性较好 zip 压缩，压缩时请使用 WinRAR。

        **当收到的合作组字幕出错时，在整理群汇报，等待字幕组修正**

3. 压制成品和外挂字幕命名

    1. 视频和外挂音轨

        正片：[`TAG`] `SEASON` [`NUM`][`LEVEL`][`FORMAT`]    *所有外挂音轨复制其对应视频的命名 \
        特典：[`TAG`] `SEASON` [`TYPENUM`][`LEVEL`][`FORMAT`]

        `TITLE` 一般与 `季度主目录` 一致，但应注意并入的特别话需要使用其本身的名字 \
        `NUM` 是 编号，但对于剧场版或音乐会没有编号

        `TYPENUM` 是 特典类别 和 编号，如果某一类特典视频只有一个，那么可以不写编号

        特典类别 | `TYPE`
        --- | ---
        预告 Preview <br> 预告下一话内容 注意编号表示其预告的是第几话的内容而不是跟在哪一话后面 | Preview <br> Web Preview
        菜单 Menu <br> BD/DVD 播放选择菜单 | Menu
        广告 Commercial Message <br> 电视放送广告，时长一般在 7s/15s/30s/45s/... 左右 | CM
        宣传片/预告片  Promotion Video / Trailer <br> 一般时长在 1~2min 命名参考原盘和 jsum | PV Trailer
        无字 OP/ED  Non-Credit Opening/Ending | NCOP  NCED
        音乐视频 Music Video | MV
        真人特典 Interview/Talk/Stage... <br> 目前我们对于节目、采访、舞台活动、制作等三次元画面的长视频，一概怼成 IV。 | IV
        特典 Special <br> 剩下的各种类型可以全部命名成 SP，对于较特殊意义的特典也可以自定义命名 | SP 或自定义

        `LEVEL` 是编码和分辨率，代表了画质定位：

        编码 | `LEVEL`
        --- | ---
        HEVC Main 10 Profile  | Ma10p_1080p, Ma10p_720p ...（根据分辨率）
        AVC High 4:4:4 Predictive Profile | Hi444pp_1080p ...（...）
        AVC High 10 Profile  | Hi10p_1080p, Hi10p_720p ...（...）
        HEVC Main Profile 或 AVC High Profile | 1080p, 720p ...（...）

        **全季度都是 480/576p DVD 源制作的 720p 的标注为 576p (nyaa 发布要求)*

        `FORMAT` 是视频轨音轨格式，形式为 **视频格式_音频格式**，相同的格式的合并为前缀数字，具体见例子

    2. 字幕

        封有原盘图形字幕的视频不加任何标注

        外挂字幕在视频命名的末端加注语言标志，按如下命名： \
        字幕：[`TAG`] `SEASON` [NUM][`LEVEL`][`FORMAT`].`LANG`.ext \
        字体：[`TAG`] `SEASON` [Fonts].ext \
        `LANG` = sc, tc, chs, cht ... 不接受 gb, big5 \
        请优先使用字幕组的表述方式

        硬嵌字幕的视频，在文件名最后加标注: \
        视频：[`TAG`] `SEASON` [`NUM`][`LEVEL`][`FORMAT`][`LANG`].ext \
        `LANG` = chs、cht、sc、tc ...

        **字幕文件务必和视频对应，简繁都要检查**

***

## 相关音乐

1. 相关音乐是项目番剧相关的音乐专辑，包括且不限于以下内容类型：

    内容 | 英文 | 日文
    --- | --- | ---
    片头曲 | Opening | オープニング テーマ
    片尾曲 | Ending | エンディング テーマ
    歌集 | Song Collection | ソング コレクション
    角色歌 | Character (Image) Song | キャラクター イメージソング
    原声音乐 | (Original) Soundtrack | オリジナル サウンドトラック
    声剧 | (Original) (Audio) Drama | ドラマ
    广播 | Radio | ラジオ

    *可能的来源：BD/DVD 特典 CD；实体单行 CD；数字单行 CD；网络配信 等

2. 收录规范

    1. 寻找所有找到的与番剧相关的 CD，这包括上面提到的所有内容 \
        **找不到某张的放流时尽管在整理群提出询问，会有大佬帮你找*
    2. 所有收录的 CD，整理完成时必须说明资源出处（在群里说一下或者带个文本）
    3. 具有多版本的 CD（Hi-Res/通常盘/动画盘/期限盘/初回盘/限定AB …），去冗规则:

        1. 最高质量的 Hi-Res 版本无论如何都保留；
        2. 某一版本有其它版本都没有的曲目时，保留这个版本，否则移除 \
            **将被移除的版本的扫图合并至保留了的版本* \
            **不要挑取某版本 HR/CD 中部分曲目来补齐其它版本 HR/CD 未发行或未完全放流的曲目*
            **Hi-Res 覆盖 CD 版本全部曲目时，最好删除 CD 版本来节约体积，但也可以保留

    4. 不收录的情况或内容:

        1. 有损编码 (除非仅存有损发行可收 mora/iTunes AAC 和 Web MP3 配信)
        2. 禁止转载 或 保持原样/禁止重编码转载
        3. 假冒无损 (=无损格式承载有损音频内容的文件)
        4. 非完整专辑 (=不收没买全的 Hi-Res 或不完整的放流)
        5. 另一季度或剧场版的音乐 (=不跨季收录)
        6. 歌手个人专辑 (除非主题歌仅存于个人专辑)
        7. 衍生游戏、真人影剧、漫画特典、杂志特典、同人创作的 CD (=降低体积)
        8. 以 PDM 编码的 DSD 等格式的专辑
        9. 32bit Hi-Res 音频资源

        **当遇到 未授权禁转 时，允许联系放流者取得授权，但必须约定好以下形式中的一种，并在资源出处中说明：*

        1. *允许 VCB-Studio 转载且发布时标注来源，并注明禁止第三方将专辑拆离 BDRip 再行转载*
        2. *允许 VCB-Studio 转载且发布时标注来源，并注明第三方再行转载时必须注明原始来源*
        3. *允许 VCB-Studio 转载且发布时标注来源，但对第三方转载不做限制*

3. 文件规范

    1. 音频文件

        1. 允许的无损编码：FLAC；有损编码：MP3 和 AAC(.M4A) \
            *其它无损格式如 WAV 均转码为 FLAC
        2. FLAC 一律使用最高等级压缩率 (Level 8) 重编码一次，即使已充分压缩
        3. 注意验证文件完整性

    2. CUE 文件 (当且仅当专辑是整轨形式)

        1. 以 UTF-8 BOM 编码
        2. CUE 的 FILE 行正确指向同目录下的音频文件
        3. 不出现乱码或编程语法错误，曲目信息和分轨时间点确保正确

    3. LOG 文件（即 EAC 产生的抓取报告，原档如有则必带，但当且仅当物理专辑）
    4. 可选文件 (扫图 / 封面):

        1. CD 扫图文件规范见 扫图 部分
        2. 封面图是该 CD 封面或蓝光对应卷的封面，JPG 格式 \
           封面图为播放器播放使用，因此体积不宜超过 1MB，尺寸不宜超过 1000x1000 像素 \
           请统一命名为 `Cover.jpg` \
            *允许不带封面图和扫图，但原则上原档有的时候尽量保留
            *若 Hi-Res 资源已内嵌封面图，则不要另外添加封面图文件

    5. CD 的特典 MV BDRip/DVDRip (当且仅当压了的时候)
    6. 禁止携带的文件，包括且不限于：\
        文件校验信息；专辑信息文本；其它抓碟文件；放流者的问候；CD 的特典 BD/DVD 原盘

4. 目录结构

    内容 | 位置和命名 | 命名规则和补充说明
    --- | --- | ---
    主目录 | \~/**CDs** | 就算只有一张 CD 也叫做 CDs
    专辑 | ~/CDs/`CD` | `CD` 是专辑名，命名规范见下 <br> **同一 CD 的所有 CD 音质版本都放在同一专辑目录** <br> **Hi-Res 版本单独建立文件夹**
    音频 | 单碟/多碟整轨: <br> \~/CDs/CD/`CATALOG`.ext <br> 单碟分轨: <br> \~/CDs/CD/`TRNUM`. `TRTITLE`.ext <br> 多碟分轨: <br> \~/CDs/CD/`CATALOG`/`TRNUM`. `TRTITLE`.ext | `CATALOG` 是品番，可以从 VGMDB.NET 或官网找到 <br> `TRNUM` 是编号，`TRTITLE` 是曲名 <br> `TRNUM` 与 `TRTITLE` 之间用 点+空格 分开 <br> foobar2000 命名模板：`%tracknumber%. %title%`
    CUE | ~/CDs/CD/`CATALOG`.cue  | 随对应音频放在同一目录
    LOG | ~/CDs/CD/`CATALOG`.log  | 随对应音频放在同一目录
    封面 | ~/CDs/`CD`/Cover.jpg | 随对应音频放在同一目录 <br> 多个版本时用 1、2 等区分，和音轨对应的优先放置
    MV Rip | ~/CDs/CD/`CATALOG`.mkv  | 随对应音频放在同一目录 <br> **注意特典碟 `CATALOG` 与 CD 碟不一样**
    扫图 | 唯一版本: \~/CDs/CD/Scans/`PICNUM`.ext <br> 多版本方式一：\~/CDs/CD/Scans/`CATALOG_PICNUM`.ext <br> 多版本方式二: \~/CDs/CD/Scans/`CATALOG`/`PICNUM`.ext | `PIC_NUM` 是图片序号 如 01, 02, 03... <br> 有多版本扫图时，命名可以添加 `CATALOG` 作区分 (用 – 或 _ 作分隔都可以)，也可以以 `CATALOG` 建立子目录 <br> 注意有特典碟的 CD 其 CATALOG 此时形如 SECL-2209~10

5. `CD` = **专辑名** 命名规则

    类型 | 命名
    --- | ---
    **BD/DVD 特典随卷专辑** |
    可能是任何内容 <br> **原则上在任何时候都 <br> 不要在命名里添加番剧名称** | [`YYMMDD`] SPCD／`ARTISTS` (`FORMAT`) <br> [`YYMMDD`] SPCD `NUM`／`ARTISTS` (`FORMAT`) <br> [`YYMMDD`] SPCD `CONTENT`／`ARTISTS` (`FORMAT`) <br> [`YYMMDD`] SPCD `NUM` `CONTENT`／`ARTISTS` (`FORMAT`)
    **CD 音质实体或数字单行专辑** |
    主题歌 SINGLE (OP/ED 等) <br> 歌名就是专辑名 | [`YYMMDD`] ｢`TITLE`｣／`ARTISTS` (`FORMAT`) <br> [`YYMMDD`] `CONTENT`／`ARTISTS` (`FORMAT`) |
    原声/角色歌/广播/声剧等 <br> 形如“内容类型+独有专辑名” <br> 自订是否使用 ｢｣ | [`YYMMDD`] `CONTENT`／`ARTISTS` (`FORMAT`) <br> [`YYMMDD`] `CONTENT` `TITLE`／`ARTISTS` (`FORMAT`) <br> [`YYMMDD`] `CONTENT` ｢`TITLE`｣／`ARTISTS` (`FORMAT`)
    **Hi-Res 实体或数字单行专辑** |
    增加位深和频率的标识 | [`YYMMDD`] ｢`TITLE`｣／`ARTISTS` [`DEPTH`\_`FREQ`] (`FORMAT`) <br> [`YYMMDD`] `CONTENT`／`ARTISTS` [`DEPTH`\_`FREQ`] (`FORMAT`)

    `YYMMDD` 是 发售日期 \
    `NUM` 是对应的 BD/DVD 卷号，只有一个时可以不写 \
    `CONTENT` 是专辑内容 \
    `FORMAT` 是 **音频编码格式+扫图格式**，具体见例子 \
    `TITLE` 是专辑名称 \
    `ARTISTS` 是艺术家/歌手 \
    `DEPTH` = 16bit / 24bit … \
    `FREQ` = 48kHz / 96kHz / 192kHz …

    **注意所有的日文括号都使用 `｢｣` 而不再使用全角 `「」`
    **所有专辑都可以不写歌手* \
    **如果 ARTISTS 太多即 VA，一律不写* \
    **角色歌时只写角色名即可，不用写 CV，或者直接不写* \
    **命名中注意空格的地方*

***

## 相关扫图

1. 相关扫图（Scans）是项目番剧相关的实体商品扫图
2. 收录规范

    1. 压制源 版本BD/DVD 扫图如有必带
    2. 美版/意版/英版等其它版本 BD/DVD 扫图可选
    3. 设定集、台本、官方画册可选
    4. CDs 扫图可选，但原则上尽量带
    5. 原图是 WebP 和 JPG 以外任何有损格式的，不予收录

3. 文件规范

    1. 原图是 BMP/PNG/TIFF 等任何无损格式的，转换为 90% 质量的 WEBP 格式有损扫图
    2. 若原图扫描精度大于 600DPI 且长于 16383px，重新采样到最长边 16383px
    3. 原图是 JPG 格式的，保持原样 \
        **我们原则上不修图*

4. 目录结构

    1. BD/DVD 扫图、设定集、台本、官方画册等：

        内容 | 位置和命名 | 命名规则和补充说明
        --- | --- | ---
        主目录 | ~/Scans | 就算只有一张扫图也叫做 Scans
        分卷 <br> 目录 | ~/Scans/Vol.`NUM` <br> ~/Scans/Box.`NUM` <br> ~/Scans/BDBOX `NUM` <br> ~/Scans/`SEPCIAL` <br> ~/Scans/`CUSTOM` | (Vol.0) Vol.1, Vol.2, Vol.3 ... <br>  Box.1, Box.2, Box.3 ... <br> BDBOX I, BDBOX II ... <br> Early Purchase Bonus, Amazon Limited Bonus ... <br> US BDBOX, ITA Vol.x, UKBD, SPA Blu-ray ...
        设定 | ~/Scans/`ArtbookTitle` | `ArtbookTitle` 尽可能用英文
        台本 | ~/Scans/`PlayScriptTitle` | `PlayScriptTitle` 尽可能用英文
        画册 | ~/Scans/`GalleryTitle` | `GalleryTitle` 尽可能用英文
        图片 | ~/Scans/`AnyTitle`/`PICNAME`.ext <br> ~/Scans/`AnyTitle`/booklet/`PICNAME`.ext | 如果原档是没意义的 imgXXX 之类 <br> 最好以 01, 02, 03 … 重排一下

    2. 相关音乐扫图的部分见第 13 条

***

## 制种和上传

1. 制作种子

    1. 必须使用 uTorrent 制作种子
    2. 制作种子时勾选 `保留文件顺序 Preserve File Order`，**不**勾选 `私有种子 Private Torrent`，如图所示：

        ![uTorrent](https://img.2222.moe/images/2018/07/31/uTorrent.png "Logo Title Text 1")

    3. 制作种子时使用以下 tracker，注意每个 tracker 之间空一行：

        ```text
        http://208.67.16.113:8000/annonuce

        udp://208.67.16.113:8000/annonuce

        udp://tracker.openbittorrent.com:80/announce

        http://t.acg.rip:6699/announce

        http://nyaa.tracker.wf:7777/announce

        https://tr.bangumi.moe:9696/announce

        http://tr.bangumi.moe:6969/announce

        udp://tr.bangumi.moe:6969/announce

        http://open.acgnxtracker.com/announce

        https://open.acgnxtracker.com/announce
        ```

    4. 种子末端添加版本号，如 `[VCB-Studio] Sword Art Online.v2.torrent`。每次重新制种，版本号+1。
    5. 制作完成的种子务必再使用 Auto Torrent Inspection 检查 tracker 列表正确。

2. 一般情况下通过 度盘/GD 将整理成品传递给复查。如果遇到分享失败的情况，使用 `HashRenamer` 重新命名并上传。如果遇到特定被彻底拉黑的文件，将该文件使用 WinRAR 打包并加密文件名，同时带上 5% 的恢复记录。复查修订后，记得同步修改度盘链接中的文件和种子。\
   如果你与复查/总监的网络状况都较好，也可以直接做种传递成品。

