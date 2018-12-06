# how to use github pages
 - make my repository
 - setting 
 - github pages → Sorce → push master branch →  save
 - https://ユーザまたは組織名.github.io/リポジトリ名
 - got it
 - https://www.tam-tam.co.jp/tipsnote/html_css/post11245.html
`
# http key の抜け方
 - git config --global credential.helper cache
 
 # copordrop
 - https://github.com/susoab/copordrop.git
 - git@github.com:susoab/copordrop.git
 - https://susoab.github.io/copordrop/

# how to use "rust"
 - 公式サイトURL：https://www.rust-lang.org/
 - レポジトリURL：https://github.com/rust-lang/rust
 - Firefox を開発する Mozilla が開発
 - Stack Overflowのアンケートによると、Rustは2015年、2016年と2年連続で、最も愛されているプログラミング言語に選ばれた
 - システムプログラミング言語
 - Nimと比較した面白いブログ(http://wolfbash.hateblo.jp/entry/2017/07/30/193412)
 - 借用検査という概念を導入することによりメモリ安全およびデータ競合安全をコンパイラが保証する言語
 - Rust は「寿命」を変数の型に含めることによりメモリ管理を行うという概念を導入し、メモリ安全性など様々な健全性が実現できることが証明された
 - Rustはこんな用途で採用されている
   - データベースやOSなどのシステムソフトウェア
   - レンダリングエンジンやゲームエンジンなど、高速性が必要なコンポーネント
   - ベンチマーカやテキストエディタなど、IOや描画といったイベントを効率的・即時的に扱うソフトウェア
 - 多くのことをコンパイル時に静的に解決する言語(すべてを実行時に解決する動的な言語とは対極)
   - ランタイムのGCがないものの、コンパイル時解析のおかげで自動メモリ管理ができる
   - マルチスレッドプログラミングで悩ましいデータ競合（競合状態ではない）をコンパイル時に防げる
   - ポリモーフィズムをコンパイル時に解決できる
```
fn main() {
  println!("Hello, World");
}
```
 - 関数定義
 ```
 fn 関数名(引数) -> 返り値の型 {
    関数本体
}
```
 - 返り値が何もない場合には、-> 返り値の型は省略できる
 ```
 fn 関数名（引数）{
     関数本体
 }
```
 - http://tracpath.com/works/devops/rust-lang/ (わかりやすいかも)
