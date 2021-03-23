# 【衛星画像解析】夜間光データから機械学習を使ってGDPを推定してみた

Qiitaに投稿した「【衛星画像解析】夜間光データから機械学習を使ってGDPを推定してみた（https://qiita.com/syurenuko/items/63c9ef9528def7075b7e )」で使用したコードです。

データサイトからデータを持ってきて、データ加工し、夜間光データからGDPを機械学習で推定する流れになっています。

DMSP-OLS衛星の夜間光データを可視化するにあたって【入門】Pythonによる人工衛星データ解析（Google Colab環境）https://qiita.com/takubb/items/97b2e4ed91cf417c4a66 を参考にさせて頂きました。

## 使用したデータサイト

・Version 4 DMSP-OLS Nighttime Lights Time Series(https://ngdc.noaa.gov/eog/dmsp/downloadV4composites.html)

・【DataHub】Country, Regional and World GDP (Gross Domestic Product)(https://datahub.io/core/gdp)

・国土数値情報（国土交通省）(https://nlftp.mlit.go.jp/index.html)

## ipynbファイルが読み込まれない時
GitHubの不具合でipynbファイルが読み込まれないことがあるそうです。その時はnbviewer(https://nbviewer.jupyter.org/) にURL貼り付けると見れるそうなので試してみてください。

このipynbファイルのnbviewerURL (https://nbviewer.jupyter.org/github/syurenuko/NightLight_GDP.ipynb/blob/main/%E3%80%90%E8%A1%9B%E6%98%9F%E7%94%BB%E5%83%8F%E8%A7%A3%E6%9E%90%E3%80%91%E5%A4%9C%E9%96%93%E5%85%89%E3%83%87%E3%83%BC%E3%82%BF%E3%81%8B%E3%82%89%E6%A9%9F%E6%A2%B0%E5%AD%A6%E7%BF%92%E3%82%92%E4%BD%BF%E3%81%A3%E3%81%A6GDP%E3%82%92%E6%8E%A8%E5%AE%9A%E3%81%99%E3%82%8B.ipynb)
