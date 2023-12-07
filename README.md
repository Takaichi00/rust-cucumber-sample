# 概要
* ここでは [cucumber-rs/cucumber](https://github.com/cucumber-rs/cucumber) を用いたシナリオテストを実装します

# セットアップ
* [Cucumber (Gherkin) Full Support - Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=alexkrechik.cucumberautocomplete) → VSCode のプラグインを入れておくと、.feature ファイルのフォーマットをしてくれます

# 実行方法
* コードからテストを実行する
```
cargo test -p rust-cucumber-sample --test rust-cucumber-sample
```

* タグが付いたもののみを実行する (下記は @minimum の場合)

# 参考文献
* [Cucumber Rust Book](https://cucumber-rs.github.io/cucumber/current/introduction.html)
* [Gherkin Reference - Cucumber Documentation](https://cucumber.io/docs/gherkin/reference/)
