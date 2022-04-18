# VCB-Studio 整理组成品规范

此规范作为通常情况下的准则，但是具体情况请具体讨论并灵活应对，一定不要生搬硬套。\
遇到需要特别对待的情况或者不太确定好的处理办法时，**一定**在群里讨论。\
遇到不适应具体情况的条目请立即提出修改意见。

- [VCB-Studio 整理组成品规范](#vcb-studio-整理组成品规范)
  - [流程](#流程)
  - [项目根目录](#项目根目录)
  - [整体目录结构](#整体目录结构)
  - [压制成品和字幕](#压制成品和字幕)
  - [相关音乐](#相关音乐)
  - [相关扫图](#相关扫图)
  - [制种和上传](#制种和上传)
  - [附录](#附录)
  - [Changelog](#changelog)

## 流程

1. 整理环节依序包括*分配* → *整理* → *复查*：

   - **分配**

     - 新任务会反映在 Trello 上，一般总监会做通知，可以主动关注或等待分配
     - 三次元正事优先，确认自己一定有时间再接任务，保证质量同时也不要耗时太久
     - 因为三次元事务无法完成任务时请及时将任务转交给其它成员

   - **整理**：检查*压制成品* → (可选)收集相关音乐和扫图 → 组织目录结构和制种 → 上传*整理成品*

     - 一般每个项目的整理环节只由一名整理成员负责，且未来同一系列的番剧都由同一成员负责
     - 整理完成时整理成员须在群内通知并在度盘分享链接中附上 ATI 和 MP 截图

     **压制成品*：按照《VCB-Studio制作规格》由原盘压制得到完整视频合集 \
     **整理成品*：按照本规范进行组织的视频音乐扫图合集

   - **复查**：检查*整理成品* → 指导错误修正 → 确认项目成品

     - 每个项目的复查环节由一名整理组复查成员负责主要检查，并由总监做最后审核确认
     - 复查成员复查通过后须在群内通知总监进行终审并转交复查成品文件链接
     - 总监终审通过后由总监将复查成品文件转交至发布组继续后续工作
     - 原则上，在复查和终审中发现的错误应该由发现错误者的上一级进行修正
       - 复查通过=整理已完成任务，若总监终审又发现错误，则应由复查修正处理且整理不再负责
       - 虽然复查发现的错误应由整理修正处理，但为了减少文件反复传递的内耗，请整理如需更新或增删文件前与复查提前沟通，避免复查检查至一半时被突然通知成品需要重新下载
       - 压制错误除外，应回炉至压制组

     > 根据整理组 2022-04-02 会议决定，至 2022 年秋季招新完成为止，调整复查环节工作流如下：

     - 有能力进行整理环节的总监，原则上要求尽量负责本人项目的整理或复查
       - 优先负责复查，因为要留出更多机会让新手整理练习
       - 总监如负责整理，则复查环节允许并优先由 2021 年或更早加入的**整理**负责
       - 总监如负责复查，则总监独自负责复查和终审，整理组复查不再负责
       - 总监如都不负责，则继续按原先整理-复查-终审三人流程执行
       - 请总监开新任务时通知按哪种流程执行
     - 其它总监，继续按原先整理-复查-终审三人流程执行

2. **自 2021 年 12 月起 VCB-Studio 不再保证以最大努力收录相关音乐和扫图。**

   - 规范上允许不进行任何相关音乐和扫图的收集。
   - 相关内容由总监、整理、复查本着自愿原则在精力容许范围内寻找和收录。
   - 不再保证不等于摆烂，请相关人员明白每增加完善一份相关资源就可以提高一分成品的质量。
   - 对于任何收录的内容，请依旧遵守本规范要求进行处理。

---

## 项目根目录

1. 类型
   - 如果项目为分离的多季度，则`项目根目录`是一个`系列主目录`，每季度在其下对应一个`季度主目录`
   - 如果项目为单季度或分割放送的多期，则 `项目根目录` 是一个 `季度主目录`
     - 预料有后续季度时，命名上注意为后续季度留出空间以便日后做合集时减少重命名
     - 如果`系列主目录`导致路径过长，可放弃`系列主目录`而将项目视作多个`季度主目录`分拆处理和制种

2. 命名

   `系列主目录`：[`TAG`] `SERIES` \
   `季度主目录`：[`TAG`] `SEASON` [`LEVEL`]

   - `TAG` 是*组名*，默认 `VCB-Studio`
     - 有合作组的时候会在 Trello 卡片上标出，用 `&` 将各组连起来
     - 原则上合作组组名前置，具体表示方法询问总监或具体字幕合作联络人
   - `SERIES` 是*系列共有名*，不标 S1+S2+OVA 等季度标识
   - `SEASON` 是*季度专有名*，不标 S1/S2 等季度标识
     - 系列和季度名原则上只使用基本拉丁字母和半角符号，避免使用 `\/:*?"<>|` 或其它特殊字符
     - 原作/企划标题为日文的优先使用罗马音且注意官方拼法，其余情况优先使用官方英文拼法
     - 一定需要时存在正斜线 `⁄` 和冒号 `꞉` 两个非常规符号可用于文件名，如要使用请在群内说明
     - **遇到特殊情况一定在群里确认**
   - `LEVEL` 是*编码级别*，如下所示：
     项目类型|编码级别（根据正片分辨率和编码）
     --- | ---
     现标准版 HEVC Main 10 Profile | Ma10p_4K_HDR, Ma444-10p_1080p, Ma10p_1080p, Ma10p_720p …
     旧标准版 AVC High 10 Profile | Hi10p_1080p, Hi10p_720p …
     移动版 任何编码 | 1080p, 720p …
   - 带字幕的移动版，在最后加上如 [SC]、[TC]、[CHS]、[CHT] 等字幕语言标识，大小写均可
     - 如 `[Nekomoe kissaten&VCB-Studio] Fruits Basket 2nd Season [1080p][sc]`

---

## 整体目录结构

`季度主目录`下的文件目录结构：

内容 | 位置| 下属文件
--- | --- | ---
正片目录 | ~ |
正片视频 | ~/xxx.ext | 视频文件和外挂音轨 mkv/mka/mp4
字幕文件 | 随对应视频放在同一目录 | ass
字幕字体 | ~/xxx.ext | 压缩包 7z/zip
特典目录 | ~/SPs |
特典视频 | ~/SPs/xxx.ext | 视频文件和图片 mkv/png <br> Menu, NCOP/ED, IV, SP <br> CM/SPOT, PV/Teaser/Trailer, (Web) Preview
扫图目录 | ~/Scans |
扫图文件 | ~/Scans/xxx.ext <br> ~/Scans/xxx/xxx.ext | BD/DVD 扫图和其它相关扫图 webp/jpg
专辑总目录 | ~/CDs |
专辑目录 | ~/CDs/`CD`/ |
专辑文件 | ~/CDs/`CD`/xxx.ext <br> ~/CDs/`CD`/`CATALOG`/xxx.ext | 音频文件、分轨信息、抓取日志、封面图 <br> flac/cue/log/jpg
专辑视频特典 | ~/CDs/`CD`/`CATALOG`.ext <br> ~/CDs/`CD`/`CATALOG`/xxx.ext | （罕见）视频文件 mkv
专辑扫图目录 | ~/CDs/`CD`/Scans |
专辑扫图文件 | ~/CDs/`CD`/Scans/xxx.ext <br> ~/CDs/`CD`/Scans/`CATALOG`/xxx.ext | 专辑扫图 webp/jpg

---

## 压制成品和字幕

1. `压制成品` 是从源 BD/DVD 抽取→预处理→重编码得到的视频、图片、音轨、章节、图形字幕等文件

   - 整理人员必须确认取得的压制成品与压制人员的本地文件一致
   - 标准版成品必须携带原盘中所有有效内容，移动版只带正片和 NCOP/ED
   - 整理人员必须使用成品对照组来检查压制成品
     - 对照组只用于检查视频缺漏、音轨错误、章节错误等基础问题，不关心画质问题和视频编码出错
     - 标准成品对照组：[jsum 的 BDRip](https://u2.dmhy.org/userdetails.php?id=29940)

2. 压制成品和字幕检查标准，另见《VCB-Studio 制作规格》

   1. 视频

      - 内容：逐帧内容一致，时长相等，总帧数正确
         - 应确保没有预处理出错和视频编码出错如花屏漏帧，但原则上不需要整理组检查这部分内容
      - 帧率：逐行扫描，帧率正确
         - 原盘为隔行扫描的，压制应正确反交错且得到正确帧率
         - 常见帧率有 CFR 23.976 (24000/1001) 29.997 (30000/1001) 59.994 (60000/1001) FPS
           - MP 可以根据帧率将其以不同颜色表示
           - **当若视频短于 30 秒且 Mediainfo 检测到 23.976 (23976/1000) 等分母为 1000 的帧率，可以视为正确**
      - 分辨率：除移动版外分辨率通常与源 BD/DVD 相同，但可能存在如下情况：
         - 黑边切割：常见于剧场版
         - 降采样：片源分辨率整体低于 1080p 而采取降采样压制
         - 升采样：常见于 480p/576p 的 DVD 片源做成 720p
      - 其它：保留有完整的编码参数信息，色彩矩阵参数 (BT601/709/2020)。
      - 编码：
        视频特性 | 容器和编码
        --- | ---
        标准版本动态视频 | MKV / [HEVC Ma10p](https://en.wikipedia.org/wiki/High_Efficiency_Video_Coding#Profiles)
        标准版本静态视频带 BGM | MKV / [AVC Hi444pp](https://en.wikipedia.org/wiki/H.264/MPEG-4_AVC#Profiles) or [HEVC Ma10p](https://en.wikipedia.org/wiki/High_Efficiency_Video_Coding#Profiles)
        标准版本静态视频无 BGM | PNG
        移动版本动态视频 | MP4 / [HEVC Ma/Ma10p](https://en.wikipedia.org/wiki/High_Efficiency_Video_Coding#Profiles) or [AVC Hi](https://en.wikipedia.org/wiki/H.264/MPEG-4_AVC#Profiles)
      - 格式：拓展名应该与实际容器一致
        - MKV/MKA = Matroska MP4/M4A = MPEG-4
        - MP 可以检测出此拓展名和实际格式不符的问题，并标以<span style="background: red">红色底色</span>。

      > **当收到的视频不符合以上标准时，在整理群汇报，等待压制修正**

   2. 音轨

      音画对应，音画同步，数量齐全，时长一致，声道数/位深/采样率正确，音轨语言有标注且标注正确，AAC 音轨不存在转码导致的偏移，音频内容无损坏，空音轨删除。具体转码、保留、封装规则参见下表：

      源音轨 | 成品编码 | 封装位置
      --- | --- | ---
      **标准版本正片** | |
      主音轨 无损 2.0CH | FLAC | 内封 MKV
      主音轨 无损 >2.0CH | FLAC | 外挂 MKA (见a)
      主音轨 有损 | | 丢弃 (见b)
      主音轨 特殊 | 具体讨论 (见c) | 外挂 MKA (见a)
      评论轨 无损 2.0/2.1CH | AAC CVBR 192kbps | 内封 MKV（如已有 MKA 则外挂）
      评论轨 无损 5.1/7.1CH | AAC CVBR 320kbps | 内封 MKV（如已有 MKA 则外挂）
      评论轨 有损 <512kbps | 保持原样 | 内封 MKV（如已有 MKA 则外挂）
      评论轨 有损 >=512kbps 2.0/2.1CH | AAC CVBR 192kbps | 内封 MKV（如已有 MKA 则外挂）
      评论轨 有损 >=512kbps 5.1/7.1CH | AAC CVBR 320kbps | 内封 MKV（如已有 MKA 则外挂）
      **标准版本特典** | |
      动画 无损 | FLAC | 内封
      非动画 无损 2.0/2.1CH | AAC CVBR 192kbps | 内封 MKV
      非动画 无损 5.1/7.1CH | AAC CVBR 320kbps | 内封 MKV
      非动画 有损 <512kbps | 保持原样 | 内封 MKV
      非动画 有损 >=512kbps 2.0/2.1CH | AAC CVBR 192kbps | 内封 MKV
      非动画 有损 >=512kbps 5.1/7.1CH | AAC CVBR 320kbps | 内封 MKV
      **移动版本**(见d) | |
      主音轨 2.0CH | AAC CVBR 192kbps | 内封 MP4
      其它 | | 丢弃

      - (a) 同一视频的所有外挂音轨均封装在同一个 MKA 文件里，注意保持一致的轨道顺序
      - (b) 片源只有有损主音轨或 >2.0CH 无损主音轨的时候同样内封
      - (c) 特殊音轨：DTS Headphone X 转 FLAC，视障音轨规格按主音轨处理
      - (d) 对于部分特殊 MKV 移动版本/先行版本，具体情况具体讨论

      > **当收到的音轨出错时，在整理群汇报，联系压制返工**

   3. 章节

      - 任何正片视频应该带有章节
      - 任何存在有意义章节的特典视频需要带有章节 (所有 CM/PV 集，多数 IV，许多 SP)
        - 章节文件均内封于 MKV/MP4 文件
        - 片头章节缺少应补齐；片尾章节多余应移除；章节时间错误应修正
        - **章节文本**：
          - 一般为 `Chapter XX`，顺序从 01 开始，也可以是具体意义的内容
            - 文本不要求还原 BD 菜单，如要手工输入请确保输入正确
          - 章节语言标志根据章节文本内容决定，如只有英文则为 `en`
            - 常见语言缩写：英文 en，日文 ja，中文 zh
          - 如使用了任何非 ASCII 字符，应在封装时为其选择合适的字符集

      > **当收到的成品中章节出错时，在整理群汇报，等待压制返工或协商修正**

   4. 字幕

      - 原盘图形字幕 (PGS): 如有必带，内封于对应的 MKV 文件 (MP4 带不了)
      - 合作字幕: 标准版本，外挂 ASS 且带有字体包；移动版本，硬嵌
          - 原则上尽量避免使用 VSFilterMod 才能正确显示的特效字幕
            - ATI 可以检查字幕是否带有此类特效
          - 字体包应带且仅带有合作字幕中所包含的所有字体，并打包为压缩包
            - 压缩包优先使用 7z 格式；如果使用 zip 格式，最好避免使用 WinRAR 压缩；不使用 rar4/5 格式。

      > **当收到的合作组字幕出错时，在整理群汇报，等待字幕组修正**

3. 压制成品和外挂字幕命名

   1. 视频和外挂音轨

       正片：[`TAG`] `SEASON` [`NUM`][`LEVEL`][`FORMAT`] \
       特典：[`TAG`] `SEASON` [`TYPENUM`][`LEVEL`][`FORMAT`]
       - 所有外挂音轨复制其对应视频的命名
       - `SEASON` 一般与 `季度主目录` 一致，但应注意并入的特别话需要使用其本身的名字
       - `NUM` 是*编号*，如果是剧场版或音乐则没有编号
       - `TYPENUM` 是*特典类别*和*编号*，如果某类特典视频只有一个则可以不写编号
         - `TYPE` 定义如下：
            特典类别 | `TYPE`
            --- | ---
            预告 Preview <br> 预告下一话内容 注意编号表示其预告的是第几话的内容而不是跟在哪一话后面 | Preview <br> Web Preview
            菜单 Menu <br> BD/DVD 播放选择菜单 | Menu
            广告 Commercial Message <br> 电视放送广告，时长一般在 7s/15s/30s/45s/... 左右 | CM SPOT
            宣传片/预告片  Promotion Video / Trailer <br> 一般时长在 1~2min 命名参考原盘和 jsum | PV Trailer
            无字 OP/ED  Non-Credit Opening/Ending | NCOP NCED
            音乐视频 Music Video | MV
            真人特典 Interview/Talk/Stage... <br> 目前我们对于节目、采访、舞台活动、制作等三次元画面的长视频，一概怼成 IV。 | IV
            特典 Special <br> 剩下的各种类型可以全部命名成 SP，对于较特殊意义的特典也可以自定义命名 | SP 或自定义
         - `NUM` 总是使用至少两位数，从 `01` 开始编号
       - `LEVEL` 是编码和分辨率，代表了画质定位
         编码 | `LEVEL`（根据分辨率）
         --- | ---
         HEVC Main 10 Profile  | Ma444-10p_1080p, Ma10p_1080p, Ma10p_720p ...
         AVC High 4:4:4 Predictive Profile | Hi444pp_1080p ...
         AVC High 10 Profile  | Hi10p_1080p, Hi10p_720p ...
         HEVC Main Profile 或 AVC High Profile | 1080p, 720p ...
         - **全季度都是 480/576p DVD 源制作的 720p 的标注为 576p (nyaa 发布要求)**

       - `FORMAT` 是视频轨和音轨格式，形式为 `视频格式_音频格式`，相同的格式的合并为前缀数字如 `视频格式_2音频格式` (具体见《命名示例》)
       - 带字幕的移动版，在最后加上如 [SC]、[TC]、[CHS]、[CHT] 等字幕语言标识，大小写均可

   2. 字幕

      封有原盘图形字幕的视频不加任何标注

      外挂字幕在视频命名的末端加注语言标志，按如下命名：
      - 字幕：[`TAG`] `SEASON` [`NUM`][`LEVEL`][`FORMAT`].`LANG`.ext
      - 字体：[`TAG`] `SEASON` [Fonts].ext
        - `LANG` = sc, tc, chs, cht ... 不使用 gb, big5
        - 请优先使用字幕组的表述方式

      硬嵌字幕的视频，在文件名最后加标注:
      - 视频：[`TAG`] `SEASON` [`NUM`][`LEVEL`][`FORMAT`][`LANG`].ext
        - `LANG` = chs、cht、sc、tc ...
        - 请优先使用字幕组的表述方式

      > **字幕文件务必和视频对应，简繁都要检查**

---

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

   可能的来源：BD/DVD 特典 CD；实体单行 CD；数字单行 CD；网络配信 等

2. 收录规范

   1. 尝试寻找所有找到的与番剧相关的 CD，这包括上面提到的所有内容
      - *找不到某张的放流时尽管在整理群提出询问，会有大佬帮你找*

   2. 具有多版本的 CD（Hi-Res/通常盘/动画盘/期限盘/初回盘/限定AB…），去冗规则:
      1. 最高质量的 Hi-Res 版本无论如何都保留
         - 本处 *最高质量的 Hi-Res* 指最高 24-bit 192kHz 的常规 PCM Hi-Res 音频
         - 32-bit 或 384-kHz 的 PCM Hi-Res 只在找不到其它任何放流时收录
      2. 某一版本有其它版本都没有的曲目时，保留这个版本，否则移除
         - 将被移除的版本的扫图合并至保留了的版本
         - 不要挑取某版本 HR/CD 中部分曲目来补齐其它版本 HR/CD 未发行或未完全放流的曲目
         - Hi-Res 覆盖 CD 版本全部曲目时，最好删除 CD 版本来节约体积，但也可以保留

   3. 不收录符合以下任何一个条件的专辑放流:
      1. 禁止转载
         - 通常只要放流者没有注明禁转，默认视为可以转载
         - **注意检查资源发布页、放流者个人页、来源平台要求三个地方**
         - 要求通知的要去联系，要求授权可以去联系，禁止转载的不要去问
      2. 转载要求中存在与本规范产生冲突的描述，如：
         - *保持原样*：不得改变目录/文件名、目录结构、删除附带文件、重订元数据、改变编码器版本等
         - *禁止重编码转载*：不得重新编码不兼容的原始编码如 wav 为本规范要求的 flac/wv
      3. 非完整专辑，如：
         - 未完整购买并放流所有曲目的的网络数字专辑
         - 未完整放流所有曲目的实体专辑
      4. 所有曲目均存在官方无损发行的任何无损编码发行，但：
         - 如果存在曲目有且只有官方有损发行，完整收录该有损专辑
      5. 从有损编码转码为无损编码的假冒无损专辑
      6. 从 SACD/Hi-Res 降采样转码得到的 CD/Hi-Res 规格专辑
      7. 任何 SACD (DSD/DXD) 格式资源
      8. 包含相关曲目的其它专辑 (如歌手个人专辑)，但：
         - 如果存在曲目只收录于该专辑，完整收录该专辑
      9. 同系列但属于另一季度或剧场版的专辑 (不跨季收录)
      10. 衍生游戏、真人影剧、漫画特典、杂志特典、同人创作的专辑 (降低体积)

   4. 转载规范：
      1. 所有找到的专辑，收录时必须记录资源出处
      2. (通用规则) 当找到任何放流的专辑，首先根据该平台和该放流者的转载要求执行。如没有任何说明，视作可以直接转载。如遇到类似于*未授权禁转*时，可以联系放流者转载授权 (不强求)，但需要与放流者约定好转载规则，具体包括以下两点：
         1. 来源标注：
            - 在种子发布页注明来源和放流者ID，且在种子内添加`转载声明` (也是TSDM默认)
            - 在种子发布页注明来源和放流者ID，不在种子内添加标注 (默认)
            - 不进行任何标注
         2. 第三方转载限制：
            - 禁止第三方将专辑拆离 BDRip 再行转载 (也是TSDM默认)
            - 允许第三放转载，再行转载时必须注明原始来源 (默认)
            - 允许第三方转载，且不做任何限制
      3. (TSDM单独规则部分) 转载来自 [TSDM论坛](https://www.tsdm39.net/forum.php?gid=451) 的专辑，根据我们已达成的转载协议执行，具体如下：
            - 由 TSDM 出资或论坛项目或以部分特殊名目放流的专辑，如分享者谢礼、合购、首发、偷跑等，典型分区包括且不限于[合购区](https://www.tsdm39.net/forum.php?mod=forumdisplay&fid=503)和[首发偷跑区](https://www.tsdm39.net/forum.php?mod=forumdisplay&fid=356)，默认允许转载。转载时需在对应专辑目录下增加 `TSDM论坛放流转载声明`。
            - 由个人自购自抓在 TSDM 放流的专辑，典型分区包括且不限于[自购区](https://www.tsdm39.net/forum.php?mod=forumdisplay&fid=417)、[Hi-Res自购区](https://www.tsdm39.net/forum.php?mod=forumdisplay&fid=419)、[动漫音乐大区](https://www.tsdm39.net/forum.php?mod=forumdisplay&fid=247)、[JPOP大区](https://www.tsdm39.net/forum.php?mod=forumdisplay&fid=452):
              - 如放流者自订转载规则，按其规则执行。
              - 如放流者未指定转载规则，转载时在对应专辑目录下增加`TSDM个人放流转载声明`。
                - 如果已经存在 `TSDM论坛放流转载声明`，文本内容与之合并。

3. 文件规范

   1. 音频文件
      - 允许的有损编码：MP3 和 AAC(.M4A)
      - 允许的无损编码：FLAC
         - 其它无损格式如 WAV 均转码为 FLAC
         - FLAC 一律使用最高压缩等级 (Level 8) 重编码一次 (可以确认文件完整性)
   2. 曲目信息 CUE 文件
      - **只在音频为整轨形式时携带**
      - 以 UTF-8 BOM 编码
      - CUE 的 FILE 行正确指向同目录下的音频文件
      - 不出现乱码或编程语法错误，曲目信息和分轨时间点确保正确
   3. 抓碟报告 EAC/XLD LOG 文件
      - 原档如有则必带
      - **文件内容严格保持原样**，不改变编码格式
   4. 转载声明文本，**处理流程参见附录**，分为三种：
      1. 通用`转载声明`模板，适用于转载 TSDM 之外资源的情况：
         - 文件编码：UTF-8 BOM
         - 文件名和内容：
           - 单个放流者：\
             `{放流者}@{放流平台}.txt` 如 `Amefs@U2.txt` \
             `{放流平台}@{放流者}.txt` 如 `U2@dennis1011.txt` \
             `{放流者}.txt` 如 `七条天空.txt`

             ```txt
             {原贴链接，如果没有就不写}
             ```

             如

             ```txt
             https://u2.dmhy.org/details.php?id=46496&hit=1
             ```

           - 单个或多个放流者：`转载声明.txt`

             ```txt
             Thanks to {放流者}@{放流平台} 或 {放流平台}@{放流者} 或 {放流者}
             {原贴链接，如果没有就不写}

             Thanks to {放流者}@{放流平台} 或 {放流平台}@{放流者} 或 {放流者}
             {原贴链接，如果没有就不写}

             ...
             ```

             如

             ```txt
             Thanks to Amefs@U2
             https://u2.dmhy.org/details.php?id=29973&hit=1

             Thanks to U2@dennis1011
             https://u2.dmhy.org/details.php?id=42836&hit=1

             Thanks to 七条天空
             ```

      2. `TSDM论坛放流转载声明`模板：
         - 文件编码：UTF-8 BOM
         - 文件名和内容：`天使动漫自购转载声明.txt`

            ```txt
            天使动漫授权 VCB-Studio 转载声明
            TSDM's authorization of redistribution for VCB-Studio

            本音乐仅供 VCB-Studio 发布使用，请勿单独转载。本文件由放流者要求加入，转载时请原样保留。
            The music files here are for VCB-Studio's release only. Please do not re-post them separately. The source provider requires this file to be included as is when re-posting the BDRip release.

            动漫音乐微博，最新自购无损音乐更新情况：
            TSDM's Weibo with latest information of self-purchased lossless music:
            https://weibo.com/dmmusic
            https://weibo.com/acgtsdm

            天使动漫自购音乐区链接：
            Link to TSDM's self-purchased music forum:
            https://www.tsdm39.net/forum.php?mod=forumdisplay&fid=247

            自购支援规则（无损音质 + BK 扫图，新老 CD 皆可）：
            Rules of joining self-purchased music forum:
            https://www.tsdm39.net/forum.php?mod=viewthread&tid=841501
            ```

      3. `TSDM个人放流转载声明`模板：
         - 文件编码：UTF-8 BOM
         - 文件名和内容：
           - 单一放流者：`天使动漫@{会员ID}.txt` 如 `天使动漫@小岩井吉乃.txt`

            ```txt
            天使动漫授权 VCB-Studio 转载声明
            TSDM's authorization of redistribution for VCB-Studio

            本音乐仅供 VCB-Studio 发布使用，请勿单独转载。本文件由放流者要求加入，转载时请原样保留。
            The music files here are for VCB-Studio's release only. Please do not re-post them separately. The source provider requires this file to be included as is when re-posting the BDRip release.

            动漫音乐微博，最新自购无损音乐更新情况：
            TSDM's Weibo with latest information of self-purchased lossless music:
            https://weibo.com/dmmusic
            https://weibo.com/acgtsdm

            天使动漫自购音乐区链接：
            Link to TSDM's self-purchased music forum:
            https://www.tsdm39.net/forum.php?mod=forumdisplay&fid=247

            自购支援规则（无损音质 + BK 扫图，新老 CD 皆可）：
            Rules of joining self-purchased music forum:
            https://www.tsdm39.net/forum.php?mod=viewthread&tid=841501

            [原贴链接，可选]
            ```

           - 无论几个放流者：`天使动漫自购转载声明.txt` (与上节 `TSDM论坛放流转载声明` 模板合并为同一文件)

            ```txt
            天使动漫授权 VCB-Studio 转载声明
            TSDM's authorization of redistribution for VCB-Studio

            本音乐仅供 VCB-Studio 发布使用，请勿单独转载。本文件由放流者要求加入，转载时请原样保留。
            The music files here are for VCB-Studio's release only. Please do not re-post them separately. The source provider requires this file to be included as is when re-posting the BDRip release.

            动漫音乐微博，最新自购无损音乐更新情况：
            TSDM's Weibo with latest information of self-purchased lossless music:
            https://weibo.com/dmmusic
            https://weibo.com/acgtsdm

            天使动漫自购音乐区链接：
            Link to TSDM's self-purchased music forum:
            https://www.tsdm39.net/forum.php?mod=forumdisplay&fid=247

            自购支援规则（无损音质 + BK 扫图，新老 CD 皆可）：
            Rules of joining self-purchased music forum:
            https://www.tsdm39.net/forum.php?mod=viewthread&tid=841501

            Thanks to {放流者}
            [原贴链接，可选]

            Thanks to {放流者}
            [原贴链接，可选]

            ...
            ```

   5. 封面 / 扫图 (可选文件):
      1. 封面图是该 CD 封面或蓝光对应卷的封面
         - 一律采用 JPG 格式，体积不宜超过 1MB，尺寸不宜超过 1600x1600 像素
         - 只当音频为整轨时使用独立封面图文件，文件名一律使用 `Cover.jpg`
         - 当音频为分轨时不使用独立封面图文件，封面图一律内嵌入音频文件
         - 无论何时封面图都不强制携带，但原则上如有最好保留
           - 出于尊重放流者，放流源分轨内置的封面图最好不予删除
         - CD 多版本曲目相同去冗后只留下一个版本时，随意保留一个封面其余删掉
           - 优先保留对应于保留版本的封面图
      2. CD 扫图文件规范见 扫图 部分
   6. CD 的特典 MV/Live BDRip/DVDRip (仅当压了的时候)
   7. 禁止携带的文件，包括且不限于:
      - CD 的特典 BD/DVD 原盘
      - 文件校验信息，如 *.accuraterip
      - 专辑信息文本，包括歌词
      - 其它抓碟文件
      - 放流者的问候

4. 目录结构 ~df~

   内容 | 位置和命名 | 命名规则和补充说明
   --- | --- | ---
   专辑总目录 | ~/**CDs** | 就算只有一张 CD 也叫做 CDs
   专辑目录 | 单版本或多版本: <br> ~/CDs/`专辑名` <br> 多版本: <br> ~/CDs/`专辑名`/`版本名` |  **同一专辑相同音质(CD/Hi-Res)的所有版本都放在同一`专辑名`目录**，不同音质建立另一个`专辑名`目录(因为`专辑名`命名里带音质参数所以只能分开)。同一`专辑名`目录后下如果收纳了多个版本，可以多建立一层`版本名`目录分别收纳各个版本，也可以不建立而直接使用`碟片品番`区分(见表格下一行)。<br> `专辑名`命名规范见下一小节；`版本名`可以用`完整品番`如"ABCD-0001~2"或商品名如"期间限定盘"，合理即可。<br>
   音频 | 单版本单碟：<br> \~/CDs/`专辑名`/`碟片品番`.ext <br> \~/CDs/`专辑名`/`曲目编号`. `曲目名称`.ext  <br> 单版本多碟片： <br> \~/CDs/`专辑名`/`碟片品番`.ext <br> ~/CDs/`专辑名`/`碟片品番`/`曲目编号`. `曲目名称`.ext <br> 多版本单碟片：<br> \~/CDs/`专辑名`/`版本名`/`碟片品番`.ext <br> \~/CDs/`专辑名`/`版本名`/`曲目序号`. `曲目名称`.ext <br> 或 <br> \~/CDs/`专辑名`/`碟片品番`.ext <br> \~/CDs/`专辑名`/`碟片品番`/`曲目编号`. `曲目名称`.ext | 一张专辑可能有多个版本，一个版本可能有多张CD碟片，一张CD碟片可能有整轨和分轨两种组织形式。<br>**如果`专辑名`目录下收纳了一个版本且每版本一张CD碟片**，则无论整轨分轨都将音频文件直接放置于`专辑名`目录下；**如果`专辑名`目录下收纳了一个版本且每版本多张CD碟片**，则整轨时直接将文件放置于`专辑名`目录，分轨时再建立一层`碟片品番`目录将分轨音频收纳其中(如果多碟的曲目编号是连续的则也可以不建立`碟片品番`目录而直接将分轨放置于`专辑名`目录下)；**如果`专辑名`目录下收纳了多个版本且每版本一张CD碟片**，可以先按上一行建立一层`版本名`目录并将无论整轨分轨置于其下，也可以直接将整轨音频置于`版本名`目录下并建立`碟片品番`目录以收纳分轨音频(就像单版本多碟一样)；**如果`专辑名`目录下收纳了多个版本且每版本多张CD碟片**，目前我们还没有遇到过多版本多碟的情况，如果遇到了请模仿前述规则合理放置文件。<br> 整轨音频始终以`碟片品番`命名。`碟片品番`是该碟片的唯一发行编号，可以从 [VGMDB](https://vgmdb.net)、官网、销售网站等地方找到。**注意区分`完整品番`与`碟片品番`**，没有特典碟时二者一样，但存在特典碟时`完整品番`形如"ABCD-0001~2"区分于`碟片品番`如CD碟"ABCD-0001"和特典碟"ABCD-0002"。**没有`品番`的，可以使用任意合理命名，且与CUE和LOG保持相同命名。** <br> 分轨始终以`曲目编号`+`曲目名称`命名，之间用"点+空格"分开 foobar2000 命名模板为 `%tracknumber%. %title%`
   CUE 分轨信息 | \~/CDs/`专辑名`/`碟片品番`.cue <br> \~/CDs/`专辑名`/`版本名`/`碟片品番`.cue | 仅限整轨音频 随对应音频放在同一目录
   LOG 抓轨日志 | \~/CDs/`专辑名`/`碟片品番`.log <br> \~/CDs/`专辑名`/`版本名`/`碟片品番`.log <br> \~/CDs/`专辑名`/`碟片品番`/`碟片品番`.log | 随对应音频放在同一目录
   转载声明 | \~/CDs/`专辑名`/`转载声明`.txt <br> \~/CDs/`专辑名`/`版本名`/`转载声明`.txt | 随对应音频放在同一目录 文件名规范见上一节
   封面 | ~/CDs/`专辑名`/Cover.jpg <br> \~/CDs/`专辑名`/`版本名`/Cover.jpg | 仅限整轨音频 随对应音频放在同一目录
   专辑特典 | ~/CDs/`专辑名`/`特典名`.mkv <br> \~/CDs/`专辑名`/`版本名`/`特典名`.mkv | 随对应音频放在同一目录 <br> `特典名`是专辑特典BD/DVD的名称，推荐使用`品番`(**注意特典BD/DVD`碟片品番`与CD碟不一样**)，也可以使用任何合理命名(注意路径长度)
   扫图 | 随对应音频放置：<br> \~/CDs/`专辑名`/Scans/`图片序号`.ext <br> \~/CDs/`专辑名`/`版本名`/Scans/`图片序号`.ext <br> 多版本全部收纳一处：<br> \~/CDs/`专辑名`/Scans/`版本名_图片序号`.ext <br> 多版本在Scans目录下分目录：<br> \~/CDs/`专辑名`/Scans/`版本名`/`图片序号`.ext | 专辑扫图可以跟随对应音频位置建立 Scans 文件夹，或者可以都放在`专辑名`目录下同一个 Scans 目录中。如果收录了多版本的扫图，应当通过文件名或目录结构体现出来。 <br> `版本名`可以用`完整品番`如"ABCD-0001~2"或商品名如"期间限定盘"，合理即可。注意区分`完整品番`形如"ABCD-0001~2"和`碟片品番`如CD碟"ABCD-0001"特典碟"ABCD-0002"。`图片序号`形如 01, 02, 03，保留前置 0 对齐宽度。`版本名_图片序号`中用"-"或"_"或其它合理分隔符均可。

5. `CD` = **专辑名** 命名规则 (**留意命名中空格的地方**)

    类型 | 命名
    --- | ---
    **BD/DVD 特典随卷专辑** |
    可能是任何内容 <br> **原则上在任何时候都不要在命名里添加番剧名称** | [`YYMMDD`] SPCD／`ARTISTS` (`FORMAT`) <br> [`YYMMDD`] SPCD `NUM`／`ARTISTS` (`FORMAT`) <br> [`YYMMDD`] SPCD `CONTENT`／`ARTISTS` (`FORMAT`) <br> [`YYMMDD`] SPCD `NUM` `CONTENT`／`ARTISTS` (`FORMAT`)
    **CD 音质实体或数字单行专辑** |
    主题歌 SINGLE (OP/ED 等) <br> 歌名就是专辑名 | [`YYMMDD`] ｢`TITLE`｣／`ARTISTS` (`FORMAT`) <br> [`YYMMDD`] `CONTENT`／`ARTISTS` (`FORMAT`) |
    原声/角色歌/广播/声剧等 <br> 形如“内容类型+独有专辑名” <br> 自订是否使用 ｢｣ | [`YYMMDD`] `CONTENT`／`ARTISTS` (`FORMAT`) <br> [`YYMMDD`] `CONTENT` `TITLE`／`ARTISTS` (`FORMAT`) <br> [`YYMMDD`] `CONTENT` ｢`TITLE`｣／`ARTISTS` (`FORMAT`)
    **Hi-Res 实体或数字单行专辑** |
    增加位深和频率的标识 | [`YYMMDD`] ｢`TITLE`｣／`ARTISTS` [`DEPTH`\_`FREQ`] (`FORMAT`) <br> [`YYMMDD`] `CONTENT`／`ARTISTS` [`DEPTH`\_`FREQ`] (`FORMAT`)

    - `YYMMDD` = 发售年月日
    - `TITLE` = 专辑名称
      - 注意所有的日文括号都使用 `｢｣` 而不再使用全角 `「」`
    - `CONTENT` = 专辑内容说明
    - `NUM` = 对应的 BD/DVD 卷号，只有一个时可以不写
    - `ARTISTS` = 艺人名 (可选)，即所有专辑都可以不写歌手，并推荐不写
        - 如果 `ARTISTS` 太多即 Various Artists / VA，一律不写
        - 角色歌时只写角色名即可，不用写 CV，或者直接不写
    - `FORMAT` = `音频格式`+`扫图格式`
      - 只有音频 `flac/wv`
      - 音频和一种扫图格式：`flac/wv`+`webp/jpg`
      - 音频和二种扫图格式：`flac/wv`+`webp`+`jpg`
      - 存在专辑特典视频时按格式再添加`+mp4`或`+mkv`，位置自订但保持`flac/wv`在最前
    - `DEPTH` = `16bit` / `24bit` / `32bit`
    - `FREQ` = `48kHz` / `96kHz` / `192kHz` / `384kHz`

---

## 相关扫图

1. 相关扫图（Scans）是项目番剧相关的实体商品扫图
2. 收录规范
   1. 压制源 版本 BD/DVD 扫图如有必带
   2. 美版/意版/英版等其它版本 BD/DVD 扫图可选
   3. 设定集、台本、官方画册可选
   4. CDs 扫图可选，但原则上尽量带
   5. 原图是 WebP 和 JPG 以外任何有损格式的，不予收录
3. 文件规范
   1. 原图是 BMP/PNG/TIFF 等任何无损格式的，转换为 90% 质量的 WEBP 格式有损扫图
   2. 若原图扫描精度大于 600DPI 且长于 16383px，重新采样到最长边 16383px
   3. 原图是 JPG 格式的，保持原样
      - 我们原则上不修图
4. 目录结构
   内容 | 位置和命名 | 命名规则和补充说明
   --- | --- | ---
   扫图目录 | ~/Scans | 就算只有一张扫图也叫做 Scans
   分卷 <br> 目录 | ~/Scans/Vol.`NUM` <br> ~/Scans/Box.`NUM` <br> ~/Scans/BDBOX `NUM` <br> ~/Scans/`SEPCIAL` <br> ~/Scans/`CUSTOM` | (Vol.0) Vol.1, Vol.2, Vol.3 ... <br>  Box.1, Box.2, Box.3 ... <br> BDBOX I, BDBOX II ... <br> Early Purchase Bonus, Amazon Limited Bonus ... <br> US BDBOX, ITA Vol.x, UKBD, SPA Blu-ray ...
   设定 | ~/Scans/`ArtbookTitle` | `ArtbookTitle` 尽可能用英文
   台本 | ~/Scans/`PlayScriptTitle` | `PlayScriptTitle` 尽可能用英文
   画册 | ~/Scans/`GalleryTitle` | `GalleryTitle` 尽可能用英文
   图片 | ~/Scans/`AnyTitle`/`PICNAME`.ext <br> ~/Scans/`AnyTitle`/booklet/`PICNAME`.ext | 如果原档是没意义的 imgXXX 之类 <br> 最好以 01, 02, 03 … 重排一下

---

## 制种和上传

1. 制作种子
   1. 制种要求：
      - 保留文件顺序
      - 合理区块大小
      - 路径名编码为 UTF-8
      - 非私有种子模式
      - 包含以下 tracker：

        ```txt
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

   2. 种子末端添加版本号，且每次重新制种，版本号+1
      - 如`[VCB-Studio] Sword Art Online.v2.torrent`
   3. 制作完成的种子务必再使用 Auto Torrent Inspection (ATI) 检查 tracker 列表正确。
2. 一般情况下通过 度盘/GoogleDrive 将整理成品传递给复查。如果遇到分享失败的情况，使用 `HashRenamer` 重新命名并上传。如果遇到特定被彻底拉黑的文件，将该文件使用 WinRAR 打包并加密文件名，同时带上 5% 的恢复记录。复查修订后，记得同步修改度盘链接中的文件和种子。
   - 如果你与复查/总监的网络状况都较好，也可以直接做种传递成品。

---

## 附录

1. 转载声明处理流程：

   ```mermaid
   graph TD

   Start --> Q1{TSDM以外放流?}
   Q1 -->|没| Q3
   Q1 -->|有| Q2{几个放流者?}
   Q2 -->|一个| A211 --> A212 --> Q3
   A211("3选1添加`{ID}@{平台}.txt {平台}@{ID}.txt {ID}.txt`")
   A212("在文件里填写链接")
   Q2 -->|几个都行| A221 --> A222 --> Q3
   A221(创建`转载声明.txt`)
   A222("在文件里逐个填写每个放流者ID和链接")

   Q3{TSDM个人放流?}
   Q3 -->|没| Q4
   Q3 -->|有| Q5

   Q4{TSDM论坛放流?}
   Q4 -->|没| End
   Q4 -->|有| A4("复制`天使动漫自购转载声明.txt`") --> End

   Q5{几个放流者?}
   Q5 -->|一个| Q6
   Q5 -->|几个都行| A51 --> A52 --> End
   A51("复制`天使动漫自购转载声明.txt`")
   A52("在末尾逐个添加每个放流者ID并(可选)添加链接")

   Q6{TSDM论坛放流?}
   Q6 -->|有没有都行| A51
   Q6 -->|没| A61 --> A62 --> A63 --> End
   A61("复制`天使动漫自购转载声明.txt`")
   A62("改名为`天使动漫@{会员ID}.txt`")
   A63("(可选)在末尾添加放流者ID和链接")
   ```

2. 如果使用 uTorrent 制种，参照如下设置：

   - 制作种子时勾选 `保留文件顺序 Preserve File Order`
   - **不**勾选 `私有种子 Private Torrent`
     ![uTorrent](https://img.2222.moe/images/2018/07/31/uTorrent.png "Logo Title Text 1")
   - 制作种子时使用以下 tracker，注意每个 tracker 之间空一行：

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

## Changelog

- 2022-04-18
  1. 专辑特典补充描述
  2. 转载规则补充描述

- 2022-04-04
  1. 加入会议决定的复查流程中短期调整
  2. 补充 Ma444-10p、字幕移动版语言后缀等遗漏内容
  3. 重述专辑目录结构部分

- 2022-03-12
  1. 修正视频有损音轨转换规范
  2. 移除压制将近完工时才能约定/预定任务的限制
  3. 移除只能使用 uTorrent 制种的限制
  4. 进一步更新专辑转载规范，增加转载声明文件处理流程图

- 2022-03-06
  1. 字体包不再接受 rar 格式
  2. 独立封面文件 (Cover.jpg) 当且仅当专辑为整轨时使用，专辑音频为分轨时则只使用内嵌封面图
  3. 当且仅当专辑不存在低于等于 24-bit 192kHz 放流时，现在允许收录至多 32-bit 384kHz 的 Hi-Res 的资源

- 2022-03-05
  1. 整合 dev 分支改动
  2. 更新专辑转载规范，尤其是转载TSDM专辑的要求
  3. 增加不再保证专辑和扫图尽力收录的描述
