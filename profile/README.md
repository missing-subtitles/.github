# Missing Subtitles ～沧海遗注～

> 闭合字幕的最后一行。

许多 YouTube 长视频仅有声音而无字幕，这使得观看和理解难度增大，也导致内容难以检索和无障碍访问。
<!--- 就此被埋没在电子之海中。-->

本项目利用 whisper 模型生成相对准确的**辅助字幕 (Closed Captions, CC)**，以 WebVTT 格式归档在此。
<!--- 作为重要的“**遗失脚本**” **(The Missing Script)** 资源。-->
<!--- 我们的目标是让不再“两眼一抹黑”，为每一个声音找到它对应的文本**灯塔 (Text Beacon)**。-->

## 获取字幕

直接在 `missub.cc/` 后添加视频链接，即可前往视频对应字幕在 `missing-subtitles/archive` 的存档。

支持 `(www.)youtube.com` 和 `youtu.be` .

<!-- <img src="/img/main.webp" alt="" width="400"/> -->
<img src="https://raw.githubusercontent.com/missing-subtitles/.github/master/img/main.webp" alt="" width="400"/>

如需直接访问原始文件，则使用 raw 子域名。

<img src="https://raw.githubusercontent.com/missing-subtitles/.github/master/img/raw.webp"  alt="" width="400"/>
<!-- <img src="/img/raw.webp" alt="" width="400"/> -->

亦可直接在 [archive](https://github.com/missing-subtitles/archive) 中搜索 video ID.

## 在视频中加载字幕

得到的字幕文件可以直接用 [+Sub](https://github.com/plussub/plussub) 加载到 YouTube 的在线播放器中，

或者用 [yt-dlp](https://github.com/yt-dlp/yt-dlp) 将原视频下载到本地，使用 vlc 等播放器播放时挂载字幕。

## 项目构成

|仓库                                                                     |说明                  |
|-------------------------------------------------------------------------|----------------------|
|[archive](https://github.com/missing-subtitles/archive)                  |已收录的视频字幕      |
|[redirector](https://github.com/missing-subtitles/redirector)            |`missub.cc` 源代码    |
|[mlx-whisper-demo](https://github.com/missing-subtitles/mlx-whisper-demo)|`mlx_whisper` 调用示例|

## Contact curator

mailto: contact at missub dot cc
