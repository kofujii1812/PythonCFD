# PythonCFD

このリポジトリでは「[Pythonで学ぶ流体力学の数値計算法](https://www.ohmsha.co.jp/book/9784274224706/)」(藤井孝藏(著)、立川智章(著)、オーム社、2020/10/20)のサンプルコードを公開しています。正誤表は[Wiki](https://github.com/kofujii1812/PythonCFD/wiki)を参照してください。

## Book Info
- Title: [Pythonで学ぶ流体力学の数値計算法](https://www.ohmsha.co.jp/book/9784274224706/)
- Author: [藤井孝藏](https://ftlab.ms.kagu.tus.ac.jp/member_page/fujii/index.htm)、[立川智章](https://ftlab.ms.kagu.tus.ac.jp/)
- Price: 4,180円(本体3,800円+税)
- ISBN: 978-4-274-22470-6
- Publisher: オーム社 / Ohmsha
- Date: 2020/10/20
- Language: 日本語 / Japanese

## Sample Codes
### 第1章 離散化の考え方
- [chapter1-1-ball.ipynb](chapter1-1-ball.ipynb) : 離散化を知る(ボールの運動問題)
  - リスト1.1, 1.2, 1.3

### 第2章 スカラー移流方程式 (数値計算法の基礎)
- [chapter2-2[2]-FTCS.ipynb](chapter2-2[2]-FTCS.ipynb) : 空間微分項に対する中心差分の利用
  - リスト2.1, 2.2, 2.3
- [chapter2-2[3]-UPWIND.ipynb](chapter2-2[3]-UPWIND.ipynb) : 空間微分項に対する1次精度風上差分の利用
  - リスト2.4, 2.5
- [chapter2-3-UPWIND.ipynb](chapter2-3-UPWIND.ipynb) : 輸送速度の符号が不明な線形問題
  - リスト2.6, 2.7, 2.8
- [chapter2-4-FLUX.ipynb](chapter2-4-FLUX.ipynb) : 数値流束
  - リスト2.9, 2.10
- [chapter2-5-UPWIND2.ipynb](chapter2-5-UPWIND2.ipynb) : 数値流束と高次精度化の考え方
  - リスト2.11
- [chapter2-6-BurgersEquation.ipynb](chapter2-6-BurgersEquation.ipynb) : 輸送速度が未知量からなる非線形問題
  - リスト2.12, 2.13, 2.14, 2.15, 2.16
- [chapter2-7-2D-UPWIND.ipynb](chapter2-7-2D-UPWIND.ipynb) : 多次元への拡張
  - リスト2.17
- [chapter2-8-TVD.ipynb](chapter2-8-TVD.ipynb) : 実践的な計算法
  - リスト2.18

### 第3章 スカラー移流方程式における時間積分法
- [chapter3-2[6]-MacCormack.ipynb](chapter3-2[6]-MacCormack.ipynb) : MacCormack法
  - リスト3.1
- [chapter3-3[6]-A-LDU-Decomp.ipynb](chapter3-3[6]-A-LDU-Decomp.ipynb) : 近似LDU分解
  - リスト3.2

### 第4章 拡散方程式
- [chapter4-2-DiffusionEquation.ipynb](chapter4-2-DiffusionEquation.ipynb) : 1次元熱伝導（拡散）方程式
  - リスト4.1
- [chapter4-4-PotentialEquation.ipynb](chapter4-4-PotentialEquation.ipynb) : 楕円型方程式を解く：ポテンシャル方程式を例に
  - リスト4.2

### 第5章 圧縮性流れの支配方程式とその性質
なし

### 第6章 圧縮性流れの数値計算法 その1(システム方程式の数値計算法)
- [chapter6-1-ShockTubeProblem-MacCormack.ipynb](chapter6-1-ShockTubeProblem-MacCormack.ipynb) : MacCormack法による衝撃波管問題の数値計算
  - リスト6.1
- [chapter6-2-ShockTubeProblem-FDS.ipynb](chapter6-2-ShockTubeProblem-FDS.ipynb) : MUSCL型Roeスキームによる衝撃波管問題の数値計算
  - リスト6.2

### 第7章 圧縮性流れの数値計算法 その2(システム方程式における時間積分法)
なし

### 第8章 複雑形状への対応
なし

### 第9章 実際の課題への対応
- [chapter9-4-Compact.ipynb](chapter9-4-Compact.ipynb) : 新たな計算法
  - リスト9.1, 9.2, 9.3

## Additional Samples

追加サンプルはこちらに追加していく予定です。

## Supplemental Materials

- [Matplotlibによるグラフ描画](/docs/appendix-matplotlib.pdf)
