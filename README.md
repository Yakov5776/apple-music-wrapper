# apple-music-wrapper
No need for an Android emulator, this wrapper natively runs Apple Music v3.9.1 (x86_64) ([APKMirror](https://www.apkmirror.com/apk/apple/apple-music/apple-music-3-9-1-release/apple-music-3-9-1-2-android-apk-download/))

#### Some facts:
- native arm64 has not been tested and will most likely need a lot of changes.
- this wrapper is used as a **daemon** to interface with apple music engine and therefore it's usage is external.
- while it is possible to update the target apple music version, that requires [imports](/import.h) to be updated, and possibly any of the [test](/test.c) methods for handling initialization, login, and the likes. (would be a cool project and if you're up for that, feel free to send a working patch.)

Credits goes to [zhaarey](https://github.com/zhaarey/) for the majority of their reverse-engineering efforts.


### 安装
推荐Windows Subsystem for Linux (WSL)使用
usage:  `./wrapper -L [username]:[password])`

```shell
sudo -i
wget "https://github.com/zhaarey/wrapper/releases/download/linux/wrapper.linux.x86_64.tar.gz"
mkdir wrapper
tar -xzf wrapper.linux.x86_64.tar.gz -C wrapper
cd wrapper
./wrapper -h
```
