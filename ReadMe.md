# このソフトウェアについて

音声ファイルテスト用リポジトリ。

* GitHubに音声ファイルをUPする
* HTML5のaudioタグで再生できるか確認する

# 開発環境

* Linux Mint 17.3 MATE 32bit
* HTML5
    * `<audio>`

# 音声ファイル

## CMajor.ogg

<audio src="20170803/ogg/CMajor.ogg"></audio>

```html
<audio src="20170803/ogg/CMajor.ogg"></audio>
```

## CMajor.wav

<audio src="20170803/wav/CMajor.wav"></audio>

```html
<audio src="20170803/wav/CMajor.wav"></audio>
```

## ogg,wav,両方

<audio preload="metadata" controls>
<source src="20170803/ogg/CMajor.ogg" type="audio/ogg">
<source src="20170803/wav/CMajor.wav" type="audio/wave">
</audio>

```html
<audio preload="metadata" controls>
<source src="20170803/ogg/CMajor.ogg" type="audio/ogg">
<source src="20170803/wav/CMajor.wav" type="audio/wave">
</audio>
```

# ブラウザ対応

* https://developer.mozilla.org/ja/docs/Web/HTML/Supported_media_formats

# ライセンス

このソフトウェアはCC0ライセンスである。

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png "CC0")](http://creativecommons.org/publicdomain/zero/1.0/deed.ja)

