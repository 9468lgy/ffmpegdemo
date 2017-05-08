# ffmpegdemo
学习ffmpeg的demo,通过ffmpeg解码视频帧,用AnativeWindow显示视频,目前没有声音,只弄了图像
参考的http://blog.csdn.net/glouds/article/details/50937266,
比博客多解决了视频播放特别快的问题
原因是解析出一帧就展示一帧,查看了视频的帧率,通过sleep设置了AnativeWindow展示间隔.
