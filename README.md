# cordova-plugin-IFlyspeech
科大讯飞的语音听说读写的cordova插件 
### Supported Platforms

- iOS
- android

## Installation

cordova plugin add https://github.com/ceociocto/cordova-plugin-IFlyspeech


## How to use

```js
xunfeiListenSpeaking.startSpeak(
    function(msg) {     //成功回调函数
        console.log(msg)
},
function(error) {       // 失败回调函数
    console.log(error)
},
'你好讯飞语音',           // 朗读内容
'xiaoyan')              // 发音角色，在Speech.js中查看更多角色
```