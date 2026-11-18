# PokeChampSim — Android APK Downloads

PokeChampSimの**署名済みAndroid APK専用の公開配布リポジトリ**です。アプリ本体のソースコード、署名鍵、アクセストークンはここには保管しません。

## ダウンロード

- **[正式最新版APKをダウンロード](https://github.com/MasayukiKimura/PokeChampSim-Downloads/releases/latest/download/PokeChampSim.apk)**
- **[正式版・テスト版を一覧表示](https://github.com/MasayukiKimura/PokeChampSim-Downloads/releases)**
- [最新版のSHA-256ファイル](https://github.com/MasayukiKimura/PokeChampSim-Downloads/releases/latest/download/PokeChampSim.apk.sha256)

**正式最新版は現在v0.5.26です。** リンク先に公開されている版のみ実際にダウンロードできます。

## テスト版の扱い

CircleCIによるビルド・旧署名証明書による署名・既存の公開済みAPKとの互換性チェックが成功した場合は、今後、ここに**Pre-release（プレリリース）**としてAPKを掲載する構成です。

- **TEST / Pre-release**：実機での操作検証が未完了の候補。テスト用であり、問題が残る可能性があります
- **Latest / 正式版**：実機検証と別の手動承認が済んだ版

テスト版が公開されても、[正式最新版APK](https://github.com/MasayukiKimura/PokeChampSim-Downloads/releases/latest/download/PokeChampSim.apk)は自動的に置き換わりません。テスト版の個別APKは各Pre-releaseのAssetsからダウンロードしてください。テスト版は一般閲覧可能になる点に注意してください。

## Androidでの更新

現在のPokeChampSimをアンインストールせずにAPKをインストールしてください。データ消去を伴う再インストールは避けてください。旧署名証明書と同一で、インストール済みの版より高いversionCodeを使用することが更新の前提です。

## 配布運用

Androidのビルド・テスト・署名は**CircleCI**で実行し、GitHub Releasesへは署名済みAPKと公開可能な検証情報のみをアップロードします。正式版としての公開は、実機確認後のCircleCI手動承認を必要とします。

APK、SHA-256、証明書の検証情報以外の秘密情報は、この公開リポジトリに登録しません。
