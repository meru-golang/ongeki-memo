# 楽曲リスト

```
https://ongeki.sega.jp/assets/json
```

# key/value
new: 新曲か否か。新曲ならNEWが、そうでなければ空文字列がvalueとなる
date: 楽曲リリース日(YYYYMMDD形式)
title: 楽曲タイトル
title_sort: ソート用の曲名。元のタイトルを一定のルールに従って変換したもので、濁点や小文字のないカタカナとアルファベット大文字のみで構成される。形式自体はCHUNITHMやmaimaiと同一だが、こちらは検索には使用されていない
artist: 楽曲アーティスト
id: 楽曲ID
chap_id: 楽曲が属するチャプターのID
chapter: 楽曲が属するチャプター名
character: 楽曲での対戦相手の名前
chara_id: 楽曲での対戦相手のID
category: 楽曲カテゴリ名
category_id: 楽曲カテゴリのID。名前との紐付きはhttps://ongeki.sega.jp/assets/json/music/categories.jsonでも確認できる
lunatic: LUNATICか否か。LUNATIC楽曲なら1が、そうでなければ空文字列がvalueとなる
bonus: ボーナストラックか否か。ボーナストラックなら1が、そうでなければ空文字列がvalueとなる
copyright1: 著作権表示。内容が無い場合は-がvalueとなる
lev_bas ～ lev_mas: それぞれBASIC～MASTERの譜面レベル。LUNATIC楽曲の場合はいずれも空欄。『EXP』が『EXC』となっていることに注意
lev_lnt: LUNATICの譜面レベル。通常楽曲の場合は空欄となる
image_url: ジャケット画像のファイル名。URLhttps://ongeki-net.com/ongeki-mobile/img/music/に付け足すとジャケット画像を取得できる。

# 参考にしたサイト
https://blog.qmainconts.dev/articles/hj6ydkdm1j
