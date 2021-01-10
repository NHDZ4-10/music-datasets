# music-datasets
### 数据获取
使用爬虫爬取了网易云音乐中1066个歌单从25952首歌，存储格式为txt格式，数据大小为50.4M，数据说明如下：
#### pl_mess_all包含以下信息：
"pl_id"	歌单id
"pl_name"	歌单名称
"pl_create_time"	歌单创建时间
"pl_update_time"	歌单更新时间
"pl_songs_num"	歌曲数
"pl_listen_num"	歌单播放数
"pl_share_num"	歌单分享数
"pl_comment_num"	歌单评论数	
"pl_follow_num"	歌单收藏数
"pl_tags"	歌单标签	
"pl_img_url"	封面网址	
"pl_desc"	歌单描述	
"pl_creator_id"	用户id
#### sing_mess_all包含以下信息：
"sing_id"	歌手id
"sing_name"	歌手名称
"sing_music_num"	演唱歌曲数
"sing_mv_num"	mv数
"sing_album_num"	专辑数
"sing_url"	图片来源
#### song_mess_all包含以下信息：
"song_id"	歌曲id
"song_name"	歌曲名称	
"song_pl_id"	歌曲所在歌单
"song_publish_time"	歌曲发布时间	
"song_sing_id"	歌手	
"song_total_comments"	总评论数
"song_hot_comments"	热门评论数
"song_url"	歌曲链接
#### user_mess_all包含以下信息：
"u_id"	用户id
"u_name"	用户名称	
"u_birthday"	用户生日	
"u_gender"	用户性别	
"u_province"	用户省份
"u_city"	用户城市
"u_type"	用户类型	
"u_tags"	用户标签	
"u_img_url"	用户头像	
"u_auth_status"	是否实名认证
"u_dj_status"		用户dj数
"u_vip_type"	用户VIP类型	
"u_sign"	用户签名
