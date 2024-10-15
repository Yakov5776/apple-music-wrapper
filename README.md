# apple-music-wrapper
No need for an Android emulator, this wrapper emulates Apple Music v3.9.1 (x86_64) ([APKMirror](https://www.apkmirror.com/apk/apple/apple-music/apple-music-3-9-1-release/apple-music-3-9-1-2-android-apk-download/))

Credits goes to [zhaarey](https://github.com/zhaarey/) for the majority of the reverse-engineering efforts.


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
