##网易易盾
http://dun.163.com

##接口说明
- golang版本: 1.19

- 文件说明
```

├── aigc AIGC流式检测解决方案接口演示
│   │── aigc_callback.go AIGC流式检测解决方案获取离线结果接口演示
│   └── aigc_check.go AIGC流式检测解决方案检测提交接口演示
├── audio 语音接口演示
│   │── audio_callback.go 点播语音检测结果获取接口演示
│   │── audio_query.go 点播语音结果查询接口演示
│   │── audio_submit.go 点播语音检测提交接口演示
│   │── audio_check.go 点播语音在线检测接口演示
│   │── liveaudio_callback.go 直播语音检测结果获取接口演示
│   │── liveaudio_querytask.go 直播语音结果获取接口演示
│   │── liveaudio_querymonitor.go 直播语音人审操作记录获取接口演示
│   │── liveaudio_feedback.go 直播语音信息更新接口演示
│   │── liveaudio_queryextra.go 直播语音增值检测结果获取接口演示
│   └── liveaudio_check.go 直播语音在线检测提交接口演示
├── crawler 网站解决方案接口演示
│   │── crawler_callback.go 网站解决方案检测结果获取接口演示
│   │── crawler_submit.go 网站解决方案在线检测提交接口演示
│   └── crawler_job_submit.go 网站解决方案主站检测任务提交接口演示
├── filesolution 文档解决方案接口演示
│   │── filesolution_callback.go 文档解决方案检测结果获取接口演示
│   │── filesolution_query.go 文档解决方案结果查询接口演示
│   └── filesolution_submit.go 文档解决方案在线检测提交接口演示
├── image 图片接口演示
│   ├── image_callback.go 图片离线结果获取接口演示
│   ├── image_check.go 图片在线检测接口演示
│   ├── image_asynccheck.go 图片离线检测接口演示
│   ├── image_asyncresult.go 图片离线检测结果查询接口演示
│   ├── image_query.go 图片检测结果查询接口演示
│   ├── imagelist_delete.go 图片名单删除接口演示
│   ├── imagelist_query.go 图片名单查询接口演示
│   ├── imagelist_submit.go 图片名单添加接口演示
│   ├── imagelist_update.go 图片名单更新接口演示
│   └── image_submit.go 图片批量提交接口演示
├── livevideosolution 直播音视频解决方案接口演示
│   │── livevideosolution_callback.go 直播音视频解决方案离线结果获取接口演示
│   │── livevideosolution_querymonitor.go 直播音视频解决方案人审操作记录获取接口演示
│   │── livevideosolution_feedback.go 直播音视频解决方案信息更新接口演示
│   │── livevideosolution_queryaudio.go 直播音视频解决方案查询音频断句信息接口演示
│   │── livevideosolution_queryimage.go 直播音视频解决方案查询视频截图信息接口演示
│   └── livevideosolution_submit.go 直播音视频解决方案在线检测提交接口演示
├── text 文本接口演示
│   │── text_callback.go 文本离线结果获取接口演示
│   │── text_check.go 文本在线检测接口演示
│   │── text_batch_check.go 文本批量在线检测接口演示
│   │── text_query.go 文本检测结果查询接口演示
│   └── text_submit.go 文本批量提交接口演示
├── livevideo 直播视频接口演示
│   ├── livevideo_callback.go 直播流检测结果获取接口演示
│   ├── livevideo_query.go 直播视频结果查询接口演示
│   ├── livevideo_submit.go 直播视频信息提交接口演示
│   ├── livevideo_feedback.go 直播视频信息更新接口演示
│   ├── liveimage_query.go 直播视频截图结果查询接口演示
│   ├── livewall_callback.go 直播电视墙检测结果获取接口演示
│   ├── livewall_querymonitor.go 直播电视墙人审操作记录获取接口演示
│   └── livewall_submit.go 直播电视墙信息提交接口演示
├── video 点播视频接口演示
│   ├── video_callback.go 视频点播检测结果获取接口演示
│   ├── video_query.go 视频点播结果查询接口演示
│   ├── videoimage_query.go 视频点播截图结果查询接口演示
│   └── video_submit.go 视频点播信息提交接口演示
├── videosolution 点播音视频解决方案接口演示
│   │── videosolution_callback.go 点播音视频解决方案检测结果获取接口演示
│   │── videosolution_query.go 点播音视频解决方案结果查询接口演示
│   └── videosolution_submit.go 点播音视频解决方案在线检测提交接口演示
├── mediasolution 融媒体解决方案接口演示
│   │── mediasolution_callback.go 融媒体解决方案离线结果获取接口演示
│   │── mediasolution_submit.go 融媒体解决方案在线检测提交接口演示
│   └── mediasolution_query.go 融媒体解决方案结果查询接口演示
├── keyword 敏感词接口演示
│   │── keyword_submit.go 敏感词提交接口演示
│   │── keyword_delete.go 敏感词删除接口演示
│   └── keyword_query.go 敏感词查询接口演示
├── list 名单接口演示
│   │── list_submit.go 名单提交接口演示
│   │── list_delete.go 名单删除接口演示
│   │── list_query.go 名单查询接口演示
│   └── list_update.go 名单修改接口演示
├── digital 数字阅读解决方案接口演示
│   │── digital_callback.go 数字阅读解决方案结果获取接口演示
│   │── digital_submit.go 数字阅读解决方案检测提交接口演示
│   └── digital_query.go 数字阅读解决方案结果查询接口演示
├── report 投诉举报解决方案接口演示
│   │── report_callback.go 投诉举报解决方案结果获取接口演示
│   │── report_submit.go 投诉举报解决方案检测提交接口演示
│   └── report_query.go 投诉举报解决方案结果查询接口演示
└── README.md
```

##使用说明
- demo仅做接口演示使用，生产环境接入请根据实际情况增加异常处理逻辑。