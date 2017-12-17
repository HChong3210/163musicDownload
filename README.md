# 163musicDownload

根据歌单的Json来下载,
 
1. 首先在Web页面打开调试工具, 获取歌单的返回的数据Json,
2. 解析出来歌曲name和id
3. 把id拼接到`http://music.163.com/song/media/outer/url?id=[id].mp3`来下载


