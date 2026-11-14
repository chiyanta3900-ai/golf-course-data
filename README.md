# ゴルフ手帳 コースデータ

ゴルフ手帳向けの公開コースデータ。スコア、個人の位置情報、アカウント情報は含みません。

`catalog.json` の `schema` はデータ形式、`revision` は配信の通し番号です。更新時は全コースを含め、番号を増やします。アプリは読み取り専用で起動時に確認し、検証後に端末へ保存します。取得できない場合は保存済みデータを使います。

現在はG-style、市川ゴルフ、三日月カントリークラブを収録しています。市川・三日月はコース概要・PAR・全体範囲のみで、ホール番号とグリーン座標は未確認です。グリーン距離のデータとして使用できません。G-styleのグリーン位置も推定値で、測量値ではありません。

各コースの出典・確認日はデータ内の `sources`・`retrieved` を参照してください。OpenStreetMap由来のデータにはODbL 1.0が適用されます。詳細は `DATA-LICENSE.txt` を参照してください。公式コース図・航空写真の画像は含みません。

OpenStreetMap data © OpenStreetMap contributors: https://www.openstreetmap.org/copyright
