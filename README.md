# Meamea button

All for Kagura Mea!🍥 [Desktop Version](https://github.com/daflyinbed/meaButton)

[![Build Status](https://travis-ci.org/zyzsdy/meamea-button.svg?branch=master)](https://travis-ci.org/zyzsdy/meamea-button)

Related Links:

* [Kagura Mea's Youtube channel](https://www.youtube.com/channel/UCWCc8tO-uUl_7SJXIKJACMw)

* [Kagura Mea's Twitter](https://twitter.com/KaguraMea_VoV)

## Contributing

请Fork本项目进行修改,完成修改后在本项目中发起一个Pull Request.

### Add-voice

所有音频的相关信息都存储在[src/voices.json](src/voices.json)中,要添加或修改音频,你需要对应地修改这个文件。

音频一律以mp3格式存储在[public/voices](public/voices)中,对应的URL为`voices/`.

添加的新音频请先进行音量标准化,目前音量全部标准化为`80`.

由于默认采用强缓存策略,除`index.html`外,文件名一致的文件,即使修改也**永远**不会被客户端刷新.因此新添加的音频,无论是新增还是修改,文件名都**必须**和之前任何文件名不相同.

修改音频后请删除原音频文件.

### Translation

请帮助进行英文和日语的翻译!

主程序翻译在 [src/locales](src/locales) 中的以语言名命名的js文件中.

语音的翻译在 [src/voices.json](src/voices.json) 中.

## Building

目前使用`Vue`,`jQuery`与`Bootstrap 3`开发.

要部署本地开发环境,请先安装最新版本的`node`,然后运行:

```shell
git clone https://github.com/CharlotteFallices/meamea-button.git
cd meamea-button-master
npm install
```

## License

Under the premise of not violating [the Kagura Mea Secondary Creation Regulations](https://bilibili.com/read/6597175) and the purpose and principles of it,it is applicable to the MIT License.

## Special Thanks

This project is supported by [MeowSound Idols](https://github.com/MeowSound-Idols).
