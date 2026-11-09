# Mataoto (また音)

Turn an old Android phone into a music player worth looking at.
Free, no ads, no network access. Android 5.0 and later.

古い Android を、眺めて楽しい音楽専用機に。無料・広告なし・通信なし。Android 5.0 以上。

[English](#english) | [日本語](#日本語)

> **Beta.** Latest: `1.0.0-beta.1`
> Official downloads: this page and https://mataoto.netlify.app/ (the same file). Please don't install APKs from anywhere else.

---

## English

A player for the music files already on your phone. Big type slides sideways across panorama pages, and it can replace the home screen.

- Panorama pages: start, tracks, artists, albums, controls, apps
- Music home: use it as the home screen, other apps one swipe away
- Pins, accent colors, CD-style now playing, equalizer
- Sleep timer, resume where you left off, lock screen player
- Quiet mode (mutes ringtones and notifications), headphones only
- About 2.6 MB. No INTERNET permission. No ads, analytics or accounts. English and Japanese.

Not included: streaming, bit-perfect USB DAC output, DSD.

### Download

Get `mataoto-1.0.0-beta.1.apk` from [Releases](../../releases/latest).

| | |
|---|---|
| APK SHA-256 | `451d79752ddcdc96b3f267846683409ffc1e8b98ae1d6ffca9b4400fd13c0444` |
| Signing certificate SHA-256 | `75c9bbd7733633dfb4e1f49ad822455416d1af53c8550d6bfe03525d5ac3848e` |

The certificate is the same for every version. If it differs, the APK is not mine.

```
Windows:     certutil -hashfile mataoto-1.0.0-beta.1.apk SHA256
macOS/Linux: shasum -a 256 mataoto-1.0.0-beta.1.apk
```

**Old phones (Android 7.0 and earlier):** GitHub's certificate may not be trusted by the browser on such phones and you may see a warning. Use https://mataoto.netlify.app/ instead; it opens without a warning there.

### Install

Step-by-step instructions (unknown sources, Play Protect, first launch, music home) are on the website: https://mataoto.netlify.app/en/#install

### Requirements

Android 5.0 or later. Lowest tested: 512 MB RAM, 4 cores at 1.3 GHz, 320×480 screen (Android 5.1); turn animations off in the app's settings on such a phone. Tested on real phones from Android 5.1 to 17.

### Reports

Bug reports and "works on my phone" reports are welcome in [Issues](../../issues) or the [report form](https://docs.google.com/forms/d/e/1FAIpQLSf_zoyWq96qTkPaVP3LHtkUCGloQqXUa2P9kBcE_pbT9mfy3Q/viewform). Please include:

```
Phone model:
Android version:
App version:
What happened:
What you did just before:
Does it happen every time:
```

It's a one-person project. I usually reply on weekends.

### License

Free to use. Please do not modify or redistribute it. The source code is not published. The app uses open-source fonts and libraries; the list is in the app (controls → licenses) and on the website.

### Author

drawerdev. Official accounts: https://mataoto.netlify.app/en/#official
Support (optional, changes nothing in the app): https://ofuse.me/drawerdev

---

## 日本語

端末に入っている音楽ファイルを再生するプレイヤーです。大きな文字が横に流れるパノラマ画面で、ホーム画面ごと音楽専用にもできます。

- パノラマ画面：start・tracks・artists・albums・controls・apps
- music home：ホーム画面として使えます。ほかのアプリは 1 スワイプ先
- ピン留め、アクセントカラー、CD 風の再生画面、イコライザ
- スリープタイマー、前回の続きから再生、ロック画面の再生画面
- quiet mode（着信音・通知音を消す）、イヤホンのみ
- 約 2.6MB。インターネット権限なし。広告・解析・アカウントなし。日本語と英語

入っていないもの：ストリーミング、USB DAC のビットパーフェクト出力、DSD

### ダウンロード

[Releases](../../releases/latest) から `mataoto-1.0.0-beta.1.apk` を落としてください。

| | |
|---|---|
| APK の SHA-256 | `451d79752ddcdc96b3f267846683409ffc1e8b98ae1d6ffca9b4400fd13c0444` |
| 署名証明書の SHA-256 | `75c9bbd7733633dfb4e1f49ad822455416d1af53c8550d6bfe03525d5ac3848e` |

証明書はどの版でも同じです。違っていたら、私の APK ではありません。

**古い端末（Android 7.0 以下）**：GitHub の証明書が端末のブラウザで信頼されず、警告が出ることがあります。その場合は https://mataoto.netlify.app/ を使ってください（警告なしで開けることを確かめています）。

### 入れ方

手順（提供元不明のアプリの許可、Play プロテクト、初回起動、music home）は Web サイトにあります：https://mataoto.netlify.app/#install

### 動作環境

Android 5.0 以上。動作確認済みの最低環境：RAM 512MB・4 コア 1.3GHz・画面 320×480（Android 5.1）。この環境では、設定でアニメーションをオフにしてください。Android 5.1〜17 の実機で確かめました。

### 報告

不具合や「動いた」の報告は、[Issues](../../issues) か[報告フォーム](https://docs.google.com/forms/d/e/1FAIpQLSf_zoyWq96qTkPaVP3LHtkUCGloQqXUa2P9kBcE_pbT9mfy3Q/viewform)へ。機種名・Android の版・アプリの版・起きたこと・直前にしたこと・毎回起きるか、を書いてもらえると助かります。個人で作っているので、返事は週末が多いです。

### ライセンス

無料で使えます。改変と再配布はしないでください。ソースコードは公開していません。アプリは、オープンソースのフォントとライブラリを使っています（アプリの controls → licenses と Web サイトに一覧があります）。

### 作者

drawerdev。公式アカウント：https://mataoto.netlify.app/#official
応援（任意。アプリの中身は変わりません）：https://ofuse.me/drawerdev
