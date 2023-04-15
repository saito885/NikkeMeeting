# NikkeMeeting
面談の正解を表示するツールです。
![20230317_013055000_iOS](https://user-images.githubusercontent.com/125429745/225843023-ba12f126-66a4-43bf-9831-d4adb2aa40fa.jpg)

## ■動作環境
・Windows PC（必須）  
・PC版NIKKE または スマホ版NIKKE（スマホの場合はミラーリングソフトApowerMirrorが必要）

## ■使い方（PC版NIKKEの場合）
①右のReleasesリンクからNikkeMeeting_x.xx.zipをDL  
②zipを解凍し、中にあるNikkeMeeting.exeを実行  
③NikkeMeetingのスタートボタンをクリックして面談を進める

## ■使い方（スマホ版NIKKEの場合）
①右のReleasesリンクからNikkeMeeting_x.xx.zipをDL  
②zipを解凍し、中にあるNikkeMeeting.exeを実行  
③スマホとPC両方にApowerMirrorをインストール（無償のままでもOK）  
④ApowerMirrorを起動してスマホの画面をPCへミラーリング  
⑤NikkeMeetingのスタートボタンをクリックして面談を進める

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
■2023/4/16 NikkeLibrary.json更新
　[add]対象キャラクターを追加（D）

■2023/4/1 NikkeLibrary.json更新
　[add]対象キャラクターを追加（サクラ）
　[fix]誤植訂正（プリバティ、アニス）

■2023/3/28 本体更新 v0.11
　[fix]選択肢が出ているか判定する処理を追加
　[fix]全体的にCPU使用量を低減

■2023/3/26 本体更新 v0.10
　[fix]マッチングロジック見直しによる判定精度向上

■2023/3/23 本体更新 v0.09
　[fix]上選択肢が同じものが複数ある場合の判定精度を向上
　[add]ApowerMirrorを使用してスマホからPCへミラーリングした画面でも判定できるよう対応
 
■2023/3/23 NikkeLibrary.json更新
　[fix]上下共に同じ選択肢がある場合のjsonの書き方を変更
 
■2023/3/18 NikkeLibrary.json更新
　[add]調査中としていた正解を設定（ビスケット、ギルティ）
　[add]複数のキャラに同じ選択肢がある場合の正解の書き方を変更
 
■2023/3/17 本体更新 v0.08
　[fix]NIKKE本体の邪魔にならないよう余分なスペースを削除してウィンドウを縮小化
　[fix]選択肢の取得座標を微調整

■2023/3/16 NikkeLibrary.json更新
　[add]対象キャラクターを追加（ビスケット）

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
