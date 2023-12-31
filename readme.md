# オリアカ 支援所最適化VBA

オリアカの支援所の配置を最適化するExcel VBAです

## 前提条件

1. ExcelがインストールされたPC
2. 支援所の半分くらいはUR1以上の英雄を入れ、残りを★5で埋めている

## インストール

サンプル Excel ファイルを適当な場所にダウンロード

## 使い方

1. ダウンロードしたファイルをクリックして Excel で開きます
2. VBAプログラムが入っているため、警告が画面上部に表示されることがあります。この場合には ```コンテンツを有効化``` でVBAの実行を許可してください。
3. さらに場合によっては、エクスプローラーでダウンロードしたファイルを選択し、プロパティからセキュリティを ```許可する``` に変更する必要があります。
5. ```英雄一覧``` タブで手持ちの英雄のランクを★1～UR5で選択します。★5以下は計算しないので、あえて★5以下を設定する必要はありません。
6. チームに入れる英雄の行の ```出撃``` 列を ```する``` と選択。現在のバージョンはエラーチェックをしていないので、きっちり6名だけを ```する``` としてください。
7. ```支援所``` タブで ```探索開始``` をクリックします。

PCの性能にも寄りますが数分程度で終了するはずです。

## その他

探索開始時点とその後は約30秒ごとに、途中経過を知らせるダイアログを1秒間だけ表示します。途中で探索を中断したいときにはこのダイアログでキャンセルを選択してください。

プログラムのバグで終了せずExcelが固まったようになる可能性もあります。その場合には、Excelごと強制終了させてください。

作者はこのプログラムを使用、実行したことで生じるいかなる損害に対して責任を取らないものとします。
