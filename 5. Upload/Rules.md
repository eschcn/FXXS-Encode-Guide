# Rules
该规则只对MNHD，mUHD生效，对于个人组xxx@tag，可以有自己的写法，但强烈建议统一标准风格。

目前还是笔记状态

# 音轨
* 1.0/2.0统一使用FLAC(除非源为有损)，如原始音轨为24bit,码率较高，可以转换为16bit使用，不得使用有损编码。(主要有损编码经常给过高码率，AC3也只有16bit，DD2.0 640k很多都比无损码率还高)
* 1080p当音轨为多声道时，应使用DDP，除演唱会（或类似性质）以外，不得使用无损音轨（有需要的人让他去收原版原盘）
* 最好开始淘汰DD/AC3

# 命名规则




* 统一规则 统一大小写
* 标题以及副标题应该尽可能的包含所有变种称呼（以豆瓣为准），标题如超长可略去港台译名。
* 转载可使用来源文件名标准作为副标题，不用参考下列规则，尊重原始发布者的规则，但如有重大错误，需重命名发布
* 不可出现全角字符，不可出现ASCII以外的字符，除"."以外的其他标点符号以及特殊符号不可出现
  * 对于"&",请写成and，然后标题里写带"&"的名字作为搜索命中补充，如"Kapoor & Sons 2006"应写为"Kapoor and Sons 2006",标题里写"【卡普尔和儿子们/Kapoor & Sons/卡普尔和他的孩子们】"(不过由于实际测试中豆瓣自动带出"【卡普尔家的儿子们/Kapoor & Sons - Since 1921/卡普尔和他的孩子们/卡普尔和儿子们】",所以不用特别处理)
  * 除"-"外，其他标点和空格一起替换写为"."，如"Open Season 4: Scared Silly 2016"写为"Open.Season.4.Scared.Silly.2015","Yu-Gi-Oh!: The Dark Side of Dimensions 2016"写为"Yu-Gi-Oh.The.Dark.Side.of.Dimensions.2016"
* 英文名应尽量与IMDb保持一致(除去包含符号)，对于欧洲其他非英文国家的电影，**不可只使用源语言名称命名**，可带上源语言名称 AKA 英文名，可以参考皮，如 `La nuit américaine AKA Day for Night 1973`
* 对于有多个英文名的，只保留IMDb使用的即可，其他应出现在标题中
* 对于日韩电影，IMDb里使用罗马音或者韩文拼音(?)作为标题的，必须使用源语言名称 AKA 英文名 如`Ah-ga-ssi AKA The Handmaiden 2016`、`Tegami AKA The Letters 2006`
  * 对于日韩电影，如IMDb使用了英文名，则只使用IMDb英文名即可，源语言名称以及罗马音等应该都全部出现在标题和副标题中，以源语言为主，日文不要繁转简（除非豆瓣有，这种情况下应该两种都写），如`冰果/冰菓/氷菓`
* 对于豆瓣没有的，可以参考TMDB
* 年代以IMDb为准
* DDP/DD+统一为DDP，音轨声道连写，中间不要有空格，DDP7.1（"+"作为运算符可能会有奇妙的化学反应，故DDP较好）
* 音轨名只有DD5.1可以省略，FLAC1.0/2.0可以省略声道，Atmos 和 DTS-X可以省略声道




## 标题
【名称一/名称二】后面可以随便写

（包含国粤音轨应该标注，不包含中字应该标注）

（"/"的前后不应该包含空格）

## 副标题
副标题应尽量与文件名除"."外保持一致(但可以增加AKA)，标题不可带"."

## 文件名
文件名必须将所有空格转换为"."

# Movie
* x265压制必须为10bit，但由于以前有一些8bit压制，目前要求写上，以后Trump完所有8bit压制后可以省略，带HDR的现可以省略10bit。
* HDR type理论可以写在Source后的任何地方，我们组通常写在x265后方
* 对于UHD压制，如为SDR，可以标上以作提示
## WEB
Name Year Source Resolution Rip-type Video-codec Audio-Tag (因为WEB的源码与压制难以区分，故压制统一标注为WEBRip,另WEBRip还会被录制使用)

Long Shot 2019 WEB-DL 2160p H.265/HEVC/H265 HDR DDP5.1-PHOENiX

0.5 mm 2014 WEBRip 1080p x265 10bit DDP5.1 MNHD-FRDS


## Blu-ray Encode
Name Year Source Resolution Video-encode Audio MNHD-Tag

Goodfellas 1990 BluRay 1080p x265 10bit DTS5.1-tag


## TV Show Season/Mini-Series:
### Episode(File Name)
* 尽量避免数字连写，好看一些
* 也要避免集标题后直接接BluRay
* 尽量保证整个剧集，命名风格统一
* 对于迷你剧，尽管只有一季，也建议标S01，集数S01E01

Name S##E## Episode-Name(包含) Resolution Source Video-encode Audio-Tag

Agatha.Christies.Poirot.S02E01.Peril.at.End.House.1080p.BluRay.x265.10bit.DD2.0.MNHD-tag



Name S##E## Source Resolution Video-encode Audio-Tag

Agatha.Christies.Poirot.S02E01.BluRay.1080p.x265.10bit.DD2.0.MNHD-tag
### Season

Name S## Source Resolution Year Video-encode Audio-Tag(由于剧集很多会跨年，故建议省略年份)

The Romanoffs S01 2018 AMZN WEBRip 2160p x265 HDR DD+5.1-TrollUHD

### Pack
可以尽量简写，`Video-encode`、`Audio`都可以不写

## REPACK/PROPER/RERIP
* 不做字幕的Repack，建议提供修正后的可更改的文本类型字幕到公网即可
* 写在MNHD/mUHD前面，未重新压制写REPACK，重压写RERip，更换更好的源为PROPER
* PROPER在注明源具体版本的情况下可以省略，但需在标题中注明

* REPACK、REPACK2、REPACK3 etc
* PROPER、PROPER2、PROPER3 etc
* RERIP、RERIP2、RERIP3 etc

版本是继承的

如 REPACK、PROPER2、RERip3

对于PROPER省略的，重置计数器