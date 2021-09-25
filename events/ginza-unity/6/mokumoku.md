# TODO

- [x] Input Addressable Assets System 
- [ ] ~~Input Unity Editor Extension~~ → Addressable に集中に変更

# OBJECTIVE

- [x] Unity ゲームバイブル 2nd Gen の No.35 「Addressable Assets System によるアセット管理」を読み終える
- [ ] ~~Unity ゲームバイブル 2nd Gen の No.31 「Unity エディター拡張」を読み終える~~

# FUN 

- 結構集中できた　もくもく会参加出来て幸せ
- 今日のお弁当，ボリュームが凄くて驚いた（チャーシュー・から揚げ・鮭）

# DONE

- Addressable Asset System 完全に理解した

# LEARN 
- Fast Mode / Local Host Build / Remote Host Build による Asset の読込ができた
  - Fast Mode : ビルド不要　開発中に使える
  - Remote Host Build : リモートサーバからアセットを読み込む　本番用に使える

- イベント処理・コルーチンが嫌なので，所々 async / await にした（UniTask で便利に API をラッピングするのを作った)

- アセットのダウンロードサイズの取得が生 Asset Bundle の時は苦労したのに， Addressable だと `Addressables.GetDownloadSizeAsync(ADDRESSES)` で出来てしまって泣いちゃった （iOS審査対応対策あるある）

# TRY

- 独自の Addressable Manager モジュールを作りたい（もう少し Addressable のお勉強をする)
- GitHub Actions 等の CI / CD を使って，ビルドした Addressable の bundle，catalog ファイルを FTP を使ってリモートサーバにアップロードしたい

