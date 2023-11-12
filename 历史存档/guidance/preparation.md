## 软件准备

1. 找到 Explorer 的 Details 模式

    ![Explorer Details](https://img.2222.moe/images/2018/07/31/explorer-details.png)

2. 收藏网站 [VideoHelp](https://www.videohelp.com/software)
3. 安装 [MKVToolNix](https://mkvtoolnix.download) + [gMKVExtractGUI](https://www.videohelp.com/software/gMKVExtractGUI) 并设置好后者找到前者的路径
4. 从群文件下载 `Mediainfo Project NG`
5. 安装并正确配置主站所推荐的播放器（`PotPlayer`、`MPC-BE`、`mpv` 或 `IINA`），使用 `macOS` 播放时请注意关闭硬件解码。
6. 安装 [Foobar2000](http://www.foobar2000.org/download)，并装好 [free encoders](http://www.foobar2000.org/encoderpack) + [AC3 decoder](http://www.foobar2000.org/components/view/foo_ac3) + [DTS decoder](http://www.foobar2000.org/components/view/foo_input_dts) + [APE decoder](http://www.foobar2000.org/components/view/foo_input_monkey) + [TAK decoder](http://www.foobar2000.org/components/view/foo_input_tak) + [TTA decoder](http://www.foobar2000.org/components/view/foo_input_tta)，再装好 [iTunes](https://www.apple.com/itunes/download) 或 QuickTime，FLAC 参数设为 `Level 8`，QAAC 参数：`-i -s -q 2 -v 192 --no-delay -o %d -`

    ![qaac](https://img.2222.moe/images/2018/07/31/qaac.png)

7. 安装 [XnConvert 64-bit](https://www.xnview.com/en/xnconvert/) 或 [XnViewMP 64-bit](https://www.xnview.com/en/xnviewmp/) （0.93.1 及以上），并将 webp 质量参数设置为 90
8. 安装 [Python 3](https://www.python.org/downloads/release/python-366)（3.6 及以上版本）；从群文件下载 `ToWebp-n-vcbs.py` `DiffChap.py`；从群文件下载 `audio_differ.zip` 解压并编辑 .py 文件中 sox 路径指向解压出来的 `sox.exe`；下载 [Spek](http://spek.cc/) 
9. 安装 [uTorrent 2.2.1](http://www.oldversion.com/windows/utorrent-2-2-1-build-25302)；下载 [RapidCRC-Unicode](https://github.com/OV2/RapidCRC-Unicode/releases) 
10. 从 [TautCony](https://tautcony.xyz/tcupdate.html) 下载 `AutoTorrentInspection` 和 `ChapterTool`