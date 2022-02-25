
# 正誤訂正

#### 第1版第1-2刷
|章  |ページ  |内容　　　　　　　|補足|最終更新日|
|---|---|---|---|---|
|2章|p.21|下から6行目<br>(誤)教師なし学習と教師なし学習<br>(正)教師あり学習と教師なし学習||2020-12-21|
|6章|p.329|上から2行目<br>(誤)bank-autoai.ipynb<br>(正)c31\_bank\_autoai\_data.ipynb||2020-12-21|
|6章|p.329|上から3行目<br>(誤)bank-autoai.csv<br>(正)bank-train-jp-autoai.csv||2020-12-21|
|6章|p.329|図6-1を以下に差し替え <br> <img width="600" src="../images/fig06-01.png">||2020-12-21|
|6章|p.329|図6-2を以下に差し替え <br> <img width="400" src="../images/fig06-02.png">||2020-12-21|

#### 第1版第1-3刷
|章  |ページ  |内容　　　　　　　|補足|最終更新日|
|---|---|---|---|---|
|4章|p.77|コード4-1-6の図  <br> (出版時) <img width="350" src="../images/code-04-01-06-org.png"> <br> (現在) <img width="350" src="../images/code-04-01-06-new.png">|Google Colab上のライブラリバージョンアップで表示結果が変わりました。(グラフの表示順が項目順とそろって見やすくなっています)|2022-02-25|
|4章|p.96|コード4-2-4 最終行 <br> (出版時)<br>``df6 = df5.replace({'デッキ': {np.nan: 'N'}})`` <br> (修正後)<br> ``df5['デッキ'] = df5['デッキ'].astype(object); df6 = df5.fillna({'デッキ': 'N'})`` |Google Colab上のライブラリバージョンアップで動かなくなったことへの対応(replace関数が使えなくなったのでp.96脚注で解説しているのとほぼ同じ方法を用いています)|2022-02-25|
|4章|p.151|コード4-4-7 上から3行目以降 <br> (誤) <br> ``print(y_proba[:10,:])`` <hr> <img width="175" src="../images/code-04-04-07-org.png"> <br> (正) <br> ``print(y_proba[10:20,:])`` <hr> <img width="175" src="../images/code-04-04-07-new.png">||2022-02-25|
|4章|p.152|図4-4-4  <br> (誤)  <br> <img width="175" src="../images/fig-04-04-04-org.png"> <br> (正)  <br> <img width="175" src="../images/fig-04-04-04-new.png">||2022-02-23|
|5章|p.194|表5-1 上から4行目 <br> (誤)Prospect (正)Prophet||2022-02-25|
|5章|p.213|下から2行目 <br> (誤)y=0 (正)y=1||2021-06-13|
|5章|p.213|下から1行目 <br> (誤)y_proba0 (正)y_proba1||2021-06-13|
|5章|p.214|上から2行目、3行目 <br> (誤)y_proba0 (正)y_proba1||2021-06-13|
|5章|p.232|下から2行目 <br> (出版時)``df.hist(bins=50)`` <br> (現在)``df.hist(bins=20, column=columns[1:])``|Google Colab上のライブラリバージョンアップで日付列も表示されるようになったことへの対応でコードを修正|2022-02-25|
|5章|p.232|コード5-2-6の図  <br> (出版時) <img width="350" src="../images/code-05-02-06-org.png"> <br> (現在) <img width="350" src="../images/code-05-02-06-new.png">|Google Colab上のライブラリバージョンアップで表示結果が変わりました。(グラフの表示順が項目順とそろって見やすくなっています)|2022-02-25|

<hr>

[メインページに戻る](../README.md)

