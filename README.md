## dependency
* libx264
* fdk_aac

## configure args

```bash
configure --extra-libs=-lpthread --extra-libs=-lm --enable-gpl --enable-libfdk_aac --enable-libx264 --enable-nonfree --disable-asm
```

## files generated by configure and make
* config.h
* libavcode/bsf_list.c
* libavcode/codec_list.c
* libavcode/parser_list.c
* libavdevice/indev_list.c
* libavdevice/outdev_list.c
* libavfilter/filter_list.c
* libavformat/demuxer_list.c
* libavformat/muxer_list.c
* libavformat/protocol_list.c
* libavutil/config.h
