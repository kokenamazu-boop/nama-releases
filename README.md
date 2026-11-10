# Nama Releases

Nama シリーズ（Windows x64 / VST3）の**配布専用**リポジトリです。
ソースの開発は別の非公開リポジトリで行っています。

## Nama Hub

Nama Hub は次の固定URLから最新版の一覧を読みます。

```text
https://github.com/kokenamazu-boop/nama-releases/releases/latest/download/manifest.json
```

## 収録物

| ファイル | 内容 |
|---|---|
| `Nama-<Name>-Windows-v<version>.zip` | 各プラグインの VST3 |
| `Nama-All-Windows-<date>.zip` | まとめて導入用 |
| `manifest.json` | 版・SHA-256・サイズ・更新内容 |
| `source/<id>-v<version>-src.zip` | 対応ソース（AGPL-3.0-only） |

## インストール

1. DAWを終了します。
2. zipを展開します。
3. `Nama ●●.vst3` フォルダ**全体**を `C:\Program Files\Common Files\VST3\` へコピーします。
4. DAWで再スキャンします。

フォルダ内のバイナリだけを取り出さないでください。

## ライセンス

各プラグインは **AGPL-3.0-only** です。対応ソースは各リリースの `source/` にあります。
Nama Hub（別途配布）は MIT の予定です。

本プラグインは独自実装です。特定の他社製品の公認・提携を受けたものではありません。

## 状態

2026-11-11: リポジトリ準備中。配布物は梱包スクリプトの完成後に追加します。
