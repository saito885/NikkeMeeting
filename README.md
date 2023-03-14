# NikkeMeeting
面談の正解を表示するツールです。右のReleasesリンクからDL可能。※PC版かつ日本語専用
![NikkeMeeting](https://user-images.githubusercontent.com/125429745/220867666-6d667d4a-4e31-4c14-8aec-e9cf2f93f593.jpg)

## ■使い方
①zipを解凍してNikkeMeeting.exeを実行（インストール不要）  
②スタートボタンをクリックして面談を進める

## ■注意
一部に正しく読み取れない選択肢があるため、少し待っても正解が表示されないようなら一旦キャンセルして別の会話に切り換える事をお勧めします。

面談データは<a href="https://wiki3.jp/nikke/page/217">勝利の女神：NIKKE wiki JP（有志メガニケ攻略wiki）の面談の選択肢一覧ページ</a>を参考にしています。  
wikiに追加されたデータは気付き次第反映します。

ソースコードは99.9%ウマのツールのパクリです。

## ■面談データ更新方法
方法1：設定を開いて「NikkeLibrary.jsonの更新確認」をクリック  
方法2：NikkeMeeting.exeが入っているフォルダ¥NikkeLibrary¥NikkeLibrary.jsonをメモ帳で開いて自力で修正

## ■更新履歴
<pre>
■2023/3/12 NikkeLibrary.json更新
　[add]選択肢を追加（ギルティ、シン、クエンシー）
　[fix]設定誤りを修正（ココア、イサベル、ドレイク）
　[fix]同じ選択肢があり判別が難しいため正解にキャラ名を追加（ユルハ、アドミ、ココア、ソーダ）

■2023/3/5 本体更新 v0.07
　[fix]選択肢の取得座標を微調整
　[fix]選択肢の読み取り方法を1行から複数行に変更
　[fix]上選択肢が一致するものが複数ある場合は下選択肢も一致するものを優先するよう修正

■2023/2/23 本体更新 v0.06
　[fix]下選択肢の取得座標を微調整
　[fix]画面が最小化されている場合の判定再開までの待ち時間を30秒→1秒に変更

■2023/2/15
　公式PC版向けに公開
</pre>
