# Man10 Resource Pack
シーズン３用リソースパック



#### ディレクトリ構造について

- sounds(音)
- models
  - block(マイクラ従来ブロックを置き換えるとき)
  - item(マイクラ従来のアイテムを置き換えるとき)

- man10(カテゴリはtextureと同等にします)
  - common
  - food
  - fish
  - item
  - weapon
    - gun
    - other
    - sword
- （textureと同じなので省略)

- textures
  - block (マイクラ本来のテクスチャを置き換えるとき)
  - man10
    - currency (通貨アイテム・ガチャコインなど)
    - common (共通化できるテクスチャ)
    - fishe　(魚)
    - food (食べ物)
    - drink(飲み物
    - drug(薬
    - tool（ペンチとか手にもつ道具)
    - hat(頭にかぶるもの)
    - glasses(眼鏡とか)
    - slot(カジノのスロットとか)
    - furniture(家具)
    - equipment(設備 ATMや機械など)
    - instrument(楽器)
    - gadget(小物、mPhoneとかちょっとしたもの)
    - icon(ディスコードアイコンなどのアイコン)
    - other　(あてはまらないもの)
    - weapon
      - gun
      - other
      - sword

#### ルール

- models/ 以下には、jsonファイル以外は置かない。
- textures/ 以下には、pngとmcmetaファイル以外は置かない。
- modelsとtextureのカテゴリ名は一致させること
- commons以外のtextureファイルには必ずmodelのフォルダを作り、どのモデルから参照されてるかわかるようにすること
  

#### 例

pistoldemo というテクスチャを作るときの例です。

運営以外は、テクスチャはモデルと同じ名前のフォルダを作って、その下にファイルをいれてください。

ファイル名は自由ですが、わかりやすい名前をいれること。当たり前ですが、漢字や全額はダメ。

[モデル]

- /models/man10/weapons/guns/pistoldemo.json

[テクスチャ]　モデル名と一致するフォルダを作る

　* /textures/man10/weapos/guns/pistoldemo/frame.png

- /textures/man10/weapos/guns/pistoldemo/barrel.png

これらの組み合わせをセットとする







シーズン２最終データより必要なものを取り込むようにします



割り当て表

https://docs.google.com/spreadsheets/d/1Qjq2OjKzGZb6t3sb2Cl7Ph7B5xoYvHFCcLdMqbBAuiQ/edit#gid=1509554362



Wiki

https://man10.red/wiki/doku.php?id=helper:%E3%83%AA%E3%82%BD%E3%83%BC%E3%82%B9%E3%83%91%E3%83%83%E3%82%AF%E5%86%8D%E7%B7%A8



## master
マスターブランチです。正式公開されたバージョンをここにいれます。



## develop
開発中のブランチです。


基本はこのブランチを追いかけてください

このブランチをチェックアウト後、自分のブランチを作成して作業してください。
ブランチ名は
MCID/ブランチ名

[例] takatronix/xxxx
