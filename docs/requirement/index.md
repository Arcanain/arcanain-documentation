# Requirement overview
本ページでは、AASの要求についてUSDM形式で定義する。

## USDM(Universal Specification Describing Manner)
USDMは要求を仕様化する技術の一つである。  
USDMでは、要求と仕様を階層構造で捉える。

| 要求 | 要求ID-01 | 要求内容 |
|:---|:---|:---|
|    | **理由** | 理由内容 |
|    | **説明** | 説明内容 |
|    |  | **<仕様グループ1>** |
|    | **仕様ID1-01.1** | 仕様内容1 |
|    | **仕様ID2-01.2** | 仕様内容2 |
|    |  | **<仕様グループ2>** |
|    | **仕様ID1-01.3** | 仕様内容1 |
|    | **仕様ID2-01.4** | 仕様内容2 |
| **要求** | **要求ID-02** | **要求内容** |
|    | **理由** | 理由内容 |
|    | **説明** | 説明内容 |
|    | **仕様ID1-02.1** | 仕様内容1 |
|    | **仕様ID1-02.2** | 仕様内容1 |

USDMの記載ルールを以下に記す。

* 「要求」はシステムに求められる機能・性能・品質など実現したいことを抽象的に表現する
* 「要求」はシステムの振る舞いを「動詞」と「目的語」に着目して記載する
* 「理由」があることで「要求」の意味を理解しやすい
* 「理由」を書くことで「要求」の根拠を確立する
* 「説明」は「仕様」の動きなどの補足説明をする
* 「要求」の「動詞」に対して＜仕様グループ＞を立てる
* 「仕様」は「要求」の中の「動詞」および「目的語」に存在する
* 「仕様」は「動詞」を「プログラムコード」に変換するための記述