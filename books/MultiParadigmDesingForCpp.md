## resource

https://books.google.co.jp/books/about/Multi_paradigm_Design_for_C++.html?id=r7RQAAAAMAAJ&redir_esc=y

## memo

以下、誤訳多し、注意。

### chapter1

* ビジネス要件を満たすことはもちろんだが、できるだけ理解可能で簡単に"build"できること、そして長い時間を書けて進化しマーケットにも適応できるようにすることが設計の目的
* "Domain Engineering"
  * 設計や中間物のreuseを意図して、ビジネス(domain)の抽象化律
  * "reuse" はよい設計からくる恩恵の一つであり、それを可能にする設計テクニックは時が経っても高い拡張性やメンテナンス性の獲得に導く。
  * OOだと、安定普遍的なものを親クラスに、そうでないもの派生クラスに、的に共通化したりするが、一方で OO とは関係ない generics みたいな共通化のやり方もあるわけじゃろ？Domain Engineering てのは、両方カバーする。
* "Domain Analysis"
  * そもそもパラダイムは一つじゃなくて、それぞれに独自の ルールや抽象化モデリング、、みたいなもんを持っとる
  * 特に "commonality" と "variation" の観点で見た時に、特徴づけられやすい。まずはここに着目すること。
