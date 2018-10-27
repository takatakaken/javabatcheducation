# javabatcheducation
JavaのBatch処理を使ったオブジェクト指向教育用(主能力確認目的が中心ですかね・・・)

## 実装仕様（第１段階）

1. Mainメソッドがあるクラスを用意する（Java実行用：クラス名を好きなのでどぞ）
2. DBDataValueクラスを作る（中にaaa,bbb,ccc,dddというプロパティとアクセサ用意すること）
3. CSVDataValueクラスを作る（Listでもいいです。CSVデータが貯められること）
4. DBDataValueクラスをListでもらう事ができるDBDataDaoクラスを作成する（もらう部分は自分でnewして詰めてOK：DAOクラスのイメージ）
5. 上のListオブジェクトを１件ずつ取り出してaaaが「1」であること,もしくはbbbが「1」であれば,cccとdddをCSVDataValueに格納して別Listに貯めるLogicクラスを作成する
6. 4の別リストからCSVファイルを出力する（Fileの出力面倒だったらCSVのデータ文字列が標準出力がだせることでもOK）

## クラス図（要る？）
