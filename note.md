# ExoPlayer 学习笔记
tag: `r2.11.3`

[README.md](https://github.com/google/ExoPlayer/blob/release-v2/README.md)

# 工程结构
Root project 'ExoPlayer'
* +--- Project ':demo'
* +--- Project ':demo-cast'
* +--- Project ':demo-gl'
* +--- Project ':demo-surface'
* +--- Project ':extension-av1'
* +--- Project ':extension-cast'
* +--- Project ':extension-cronet'
* +--- Project ':extension-ffmpeg' `The FFmpeg extension provides FfmpegAudioRenderer, which uses FFmpeg for decoding and can render audio encoded in a variety of formats.`
* +--- Project ':extension-flac' `The Flac extension provides FlacExtractor and LibflacAudioRenderer, which use libFLAC (the Flac decoding library) to extract and decode FLAC audio.`
* +--- Project ':extension-gvr'
* +--- Project ':extension-ima'
* +--- Project ':extension-jobdispatcher'
* +--- Project ':extension-leanback'
* +--- Project ':extension-mediasession'
* +--- Project ':extension-okhttp' `The OkHttp extension is an HttpDataSource implementation using Square's OkHttp`
* +--- Project ':extension-opus'
* +--- Project ':extension-rtmp' `The RTMP extension is a DataSource implementation for playing RTMP streams using LibRtmp Client for Android`
* +--- Project ':extension-vp9'
* +--- Project ':extension-workmanager'
* +--- Project ':library'
* +--- Project ':library-core' `Core functionality (required)`
* +--- Project ':library-dash'
* +--- Project ':library-hls'
* +--- Project ':library-smoothstreaming'
* +--- Project ':library-ui' `UI components and resources for use with ExoPlayer`
* +--- Project ':playbacktests'
* \--- Project ':testutils'