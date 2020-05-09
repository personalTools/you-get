# you-get

## you-get安装 
brew install you-get

## -i 作用是解析出该地址下的视频信息
you-get -i http://

## -o , 作用是下载该视频(注意要加保存的地址)
you-get -o /user/movie/ http://

##如果希望下载不同的的画质,先用-i参数得到解析出来的视频信息
you-get --format == container path url
you-get --format == mp4hd -o D:/ http://v.youku.com/v_show/id_XMzYzMDI2MjUxMg==.html?spm=a2hww.20027244.m_250036.5~5!2~5~5!2~5~5~A&f=51755641

##-u , 作用是解析视频真实的地址(url)
you-get -u https://v.qq.com/x/cover/34rg8ntemeszdm4/j0613bozdsx.html

##获取视频的json格式信息
you-get --json https://v.qq.com/x/cover/34rg8ntemeszdm4/j0613bozdsx.html

