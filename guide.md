# 新手指南

## Android 模擬器設置

在 Host 列出裝置清單：

```
adb devices
```

執行結果如下：

```
List of devices attached
192.168.XXX.XXX:5555	device
```

然後在 Guest 連線至指定裝置（使用 Host 的 IP 位址）：

```
adb connect 192.168.XXX.XXX:5555
```

## 建立並執行 React Native 專案

建立新專案：

```
react-native init MyApp
```

建置並執行：

```
react-native run-android
```

