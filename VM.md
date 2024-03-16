# VM（Virtual Machine）提供型の仮想化インフラ
## 概要
* VM（Virtual Machine）提供型の仮想化インフラとは、物理的なハードウェアリソース上で動作する仮想的なマシン（つまりVM）を提供するインフラストラクチャのことである。
* 1つの物理マシン上で複数の仮想マシンを動作させることが可能となる。
### 特性
* VMは独立したオペレーティングシステムとアプリケーションを動かすことができ、それぞれが他のVMから隔離されて動作する。各VMは専用のハードウェアを持っているかのように動作する。
### メリット
* 仮想マシンを利用することにより、物理ハードウェアのリソースを効率的に利用することができる。
* また、各VMは独立して動作するため、1つのVMでの問題が他のVMに影響を与えることがない。
* さらに、VMは容易にコピー・移動・バックアップすることができ、柔軟な運用が可能となる。
### デメリット
* 仮想マシンはホストシステムのリソースを共有するため、その運用を誤るとパフォーマンスの低下やリソースの無駄使いを引き起こす可能性がある。
* また、全てのアプリケーションが仮想環境で適切に動作するわけではない。
### 従来技術との違い
* 従来は物理的なハードウェア上で直接アプリケーションを動かす必要があったが、VM提供型の仮想化インフラを利用すると、1つの物理マシン上で複数の異なる環境を同時に動作させることができる。
### 留意点
* VM提供型の仮想化インフラを利用する際は、適切なリソース管理とセキュリティ対策が重要となる。
* また、VM間でのリソース競合を避けるための適切な設定が必要である。
### 利用シーン
* 開発環境の構築、テスト環境の分離、レガシーシステムの移行、データセンターの効率化など、多様なシーンでVM提供型の仮想化インフラが利用されている。