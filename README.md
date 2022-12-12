# このマップについて
 国土数値情報の「河川データ」で、河川名が「名称不明」となっているエントリーをMapboxで可視化したマップです。

# 集計手順
1. 国土数値情報のダウンロードサイトから４７都道府県の河川データを取得する
2. pyshpでshpファイルをGEOJSON形式に変換する
3. tippecanoeでGEOJSON形式のファイルをmbtilesに変換する

# 元データ 
国土数値情報 - https://nlftp.mlit.go.jp/ksj/gml/datalist/KsjTmplt-W05.html
