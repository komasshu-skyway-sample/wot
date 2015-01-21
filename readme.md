Web of Things demo

# AirPlay API

1. download video

```
$ cd airplay/public
$ mkdir movie
$ wget http://www.quirksmode.org/html5/videos/big_buck_bunny.mp4
```

2. load package
```
$ cd airplay
$ npm install
```

3. run server
```
$ bin/www
```

## known issue

iPad (iOS8.1.2) works well, however iPhone with same version doesn't work with picker (nothing appear)
