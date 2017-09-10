# icart-mini-src
icart-miniとUSB版のTop-URGを使用しています。

## 起動手順
1. ypspur_rosの起動
```bash
$ roslaunch ypspur_ros ypspur.launch
```

2. urg_nodeの起動
```bash
$ roslaunch icart_pkg urg_tf.launch
```

3. joyの起動
```bash
$ roslaunch icart_pkg joy_teleop.launch
```
