# IPTV - 中国大陆频道

基于 [iptv-org/iptv](https://github.com/iptv-org/iptv) 的精简版本，仅保留中国大陆公开 IPTV 频道。

## 包含频道

| 文件 | 说明 | 频道数 |
|------|------|--------|
| `streams/cn.m3u` | 大陆综合频道 | ~500 |
| `streams/cn_cctv.m3u` | CCTV 频道 | ~15 |
| `streams/cn_cgtn.m3u` | CGTN 频道 | ~12 |
| `streams/cn_112114.m3u` | 112114 源 | ~16 |
| `streams/cn_yeslivetv.m3u` | YesLiveTV 源 | 1 |

## 使用方法

将 `streams/` 下的 `.m3u` 文件导入支持直播流的播放器（如 VLC、IINA 等）即可观看。

## 来源

频道数据来自 [iptv-org/database](https://github.com/iptv-org/database)，仅收录公开合法的流媒体源。

## License

[MIT](LICENSE)
