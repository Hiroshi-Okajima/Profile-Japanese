[English（研究コード索引）](https://github.com/Hiroshi-Okajima) | [日本語（教材ポータル）](https://github.com/Hiroshi-Okajima/Profile-Japanese)

# 岡島研究室 — 制御工学 教材ポータル

**岡島 寛（熊本大学大学院先端科学研究部 教授）**
研究分野：制御工学，制御理論，信号処理

このページは，講義・自習で使える**制御工学の教材（ブラウザ教材・MATLAB/Python コード・動画）**の入口です．
論文の再現コード（研究コード）は [English ページ](https://github.com/Hiroshi-Okajima) に論文との対応表としてまとめています．

- 研究室 Web：[岡島研（日本語）](https://www.control-theory.com) | 業績：[研究業績（岡島寛）](https://www.control-theory.com/jp/%E6%A5%AD%E7%B8%BE)
- [Researchmap](https://researchmap.jp/read0203288?lang=en) | [ORCID](https://orcid.org/0000-0001-7621-7482) | [Researchgate](https://www.researchgate.net/profile/Hiroshi-Okajima)
- YouTube：[制御工学チャンネル（日本語，登録者 1 万人以上）](https://www.youtube.com/c/ControlEngineeringChannel/videos) | [英語サブチャンネル](https://www.youtube.com/@ControlEngineeringCh/videos)
- ブログ：[制御工学ブログ](https://blog.control-theory.com) | Qiita：[おかじま（制御工学チャンネル）](https://qiita.com/Hiroshi-Okajima) | X：[@control_eng_ch](https://x.com/control_eng_ch)
- 動画ポータル：[制御工学チャンネル（動画 500 本以上）](https://www.portal.control-theory.com) | [電気電子チャンネル（動画 200 本）](https://www.denki.control-theory.com)

![okajima_200](https://github.com/user-attachments/assets/9cd09edb-523a-48f7-9607-f16493697911)

---

## 目次

1. [ブラウザで動く制御教材（インストール不要）](#1-ブラウザで動く制御教材インストール不要)
2. [講義動画リンク集](#2-講義動画リンク集)
3. [MATLAB / Python で学ぶ制御](#3-matlab--python-で学ぶ制御)
4. [小学生・初学者向け](#4-小学生初学者向け)
5. [研究コード（論文再現）](#5-研究コード論文再現)

---

## 1: ブラウザで動く制御教材（インストール不要）

HTML + JavaScript の単一ファイル教材です．スマートフォン・タブレットでも動作します．
リポジトリ：<https://github.com/Hiroshi-Okajima/control-interactive-tools>
一覧ページ：<https://hiroshi-okajima.github.io/control-interactive-tools/>

### 講義向け（古典制御・現代制御）

| # | 教材名 | 内容 | 実行 |
|---|--------|------|------|
| 01 | 1次系の応答 | ステップ応答・インパルス応答（K, T） | [開く](https://hiroshi-okajima.github.io/control-interactive-tools/control_1st_order.html) |
| 02 | 2次系の応答 | ステップ応答・インパルス応答（K, ωₙ, ζ） | [開く](https://hiroshi-okajima.github.io/control-interactive-tools/control_2nd_order.html) |
| 03 | ボード線図と入出力波形 | 2次系の周波数応答と正弦波入出力 | [開く](https://hiroshi-okajima.github.io/control-interactive-tools/control_bode.html) |
| 04 | PID制御 | PID フィードバック制御のステップ応答・ボード線図 | [開く](https://hiroshi-okajima.github.io/control-interactive-tools/control_pid.html) |
| 05 | 3次系の極配置 | 状態フィードバックによる極配置とステップ応答 | [開く](https://hiroshi-okajima.github.io/control-interactive-tools/control_poles.html) |
| 06 | 状態推定 | 観測ノイズと速応性の状態推定における Trade off | [開く](https://hiroshi-okajima.github.io/control-interactive-tools/control_observer.html) |
| 07 | 振れ止め制御 | クレーンの振れ止めアニメーション（コンテスト） | [開く](https://hiroshi-okajima.github.io/control-interactive-tools/control_crane.html) |
| 08 | 適応クルーズ制御 | ビークルのクルーズコントロール（状態FB） | [開く](https://hiroshi-okajima.github.io/control-interactive-tools/control_acc.html) |
| 09 | 倒立振子 | 倒立振子の目標値追従制御（状態FB） | [開く](https://hiroshi-okajima.github.io/control-interactive-tools/control_invpend.html) |
| 10 | 部屋の温度制御 | 3つの条件の比較（目標温度18度） | [開く](https://hiroshi-okajima.github.io/control-interactive-tools/control_temperature.html) |

### ゲーム形式（小学生〜）

| # | 教材名 | 内容 | 実行 |
|---|--------|------|------|
| 11 | 追跡パトカー | 小学生向けゲーム | [開く](https://hiroshi-okajima.github.io/control-interactive-tools/control_acc_game.html) |
| 12 | 荷物運び | 小学生向けゲーム | [開く](https://hiroshi-okajima.github.io/control-interactive-tools/control_crane_game.html) |
| 13 | ボール＆ビーム | 小学生向けゲーム | [開く](https://hiroshi-okajima.github.io/control-interactive-tools/control_ballbeam_game.html) |
| 14 | タンクシステム | 小学生向けゲーム | [開く](https://hiroshi-okajima.github.io/control-interactive-tools/control_tank_game.html) |
| 15 | 追跡パトカー2 | 小学生向けゲーム（ドライバー視点） | [開く](https://hiroshi-okajima.github.io/control-interactive-tools/control_acc_game2.html) |
| 16 | ドローン着陸 | 正確に着陸させる | [開く](https://hiroshi-okajima.github.io/control-interactive-tools/control_drone_game.html) |
| 17 | ブランコ共振 | 共振を利用してブランコを揺らす | [開く](https://hiroshi-okajima.github.io/control-interactive-tools/control_swing_game.html) |
| 18 | レーンキープ制御 | 小学生向けゲーム | [開く](https://hiroshi-okajima.github.io/control-interactive-tools/control_lane_game.html) |

**授業・Web への埋め込み**：各教材は iframe で貼り付けられます（はてなブログ，Moodle，Google Sites で動作確認済み）．方法はリポジトリの README を参照してください．

---

## 2: 講義動画リンク集

制御工学チャンネルの動画を，講義の単元順に並べたリンク集です．

| 科目 | 内容 | リンク集 |
|------|------|----------|
| 伝達関数に基づく制御（古典制御） | ボード線図，ブロック線図，安定性解析，PID 制御 | <https://github.com/Hiroshi-Okajima/control-education01-transferfunction> |
| 状態方程式に基づく制御（現代制御） | 極配置，最適レギュレータ，可制御性 | <https://github.com/Hiroshi-Okajima/control-education02-stateequation> |
| 電気回路 | テブナンの定理，重ね合わせの理，過渡現象の基礎，フィルタ | <https://github.com/Hiroshi-Okajima/circuits-education01> |

---

## 3: MATLAB / Python で学ぶ制御

「Open in MATLAB Online」ボタンから，インストールなしでブラウザ上の MATLAB で実行できます．

### 3-1 制御の基礎（Live Script）
伝達関数・状態方程式の基礎を Live Script で学ぶ教材です．
- <https://github.com/Hiroshi-Okajima/MATLAB_fandamental_control-LiveScriptFiles-/tree/main>
- [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=Hiroshi-Okajima/MATLAB_fandamental_control-LiveScriptFiles-)

### 3-2 状態フィードバック制御（MATLAB / Python）
状態フィードバック，極配置，LQR，オブザーバ併合系．
- <https://github.com/Hiroshi-Okajima/control_state_feedback>
- 解説記事（英語）：[State Feedback Control and State-Space Design](https://blog.control-theory.com/entry/state-feedback-control-eng)

### 3-3 線形行列不等式（LMI）
安定解析（連続・離散），l2 性能解析，安定化設計の 4 コード．
- <https://github.com/Hiroshi-Okajima/Linear-matrix-inequality-and-control-MATLAB_fandamental_control>
- [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=Hiroshi-Okajima/Linear-matrix-inequality-and-control-MATLAB_fandamental_control)
- [教育ページ](https://www.control-theory.com/en/et-linear-matrix-inequality)

　[![線形行列不等式](https://user-images.githubusercontent.com/112537733/188101141-f86dee2e-ba6a-41c3-b223-e12b2da5aef6.png)](https://youtu.be/QfXJ01dIpL0)

### 3-4 制御アニメーション（MATLAB コード → mp4）
クレーン制御，状態フィードバック，PID 制御の動画を生成するコード．
- <https://github.com/Hiroshi-Okajima/MATLAB_animation>

### 3-5 状態推定・システム同定の教育用コード
研究コードと同じリポジトリに，教育用の基礎コードも含まれています．
- 状態推定（Luenberger オブザーバ，カルマンフィルタ，H∞ フィルタ）：<https://github.com/Hiroshi-Okajima/MATLAB_state_observer>
- システム同定（ARX / ARMAX / OE / BJ，PEM，部分空間法，次数選択）：<https://github.com/Hiroshi-Okajima/MATLAB_system_identification>

---

## 4: 小学生・初学者向け

- ゲーム形式の制御教材：上記 §1 の #11〜#18
- 制御 Scratch（低学年向けプログラミング）：[OKJ1980](https://scratch.mit.edu/users/OKJ1980/)

---

## 5: 研究コード（論文再現）

論文との対応表は [English ページ](https://github.com/Hiroshi-Okajima) にまとめています．ここでは日本語の解説へのリンクのみ示します．

### モデル誤差抑制補償器（MEC）— 主要研究テーマ

モデル誤差抑制補償器は，既存の制御システムにロバスト性を付与するための特化型補償器です．モデルと制御対象のギャップに起因した出力誤差を抑制する効果を持ちます．簡単な補償構造で設計指針も難しくないことから，様々な対象（線形・非線形・MIMO・むだ時間系・非最小位相系・マルチレート系など）に対して適用することが可能です．

- [まとめページ](https://www.control-theory.com/jp/%E7%A0%94%E7%A9%B6%E3%83%A2%E3%83%87%E3%83%AB%E8%AA%A4%E5%B7%AE%E6%8A%91%E5%88%B6%E8%A3%9C%E5%84%9F%E5%99%A8) | [ブログ記事](https://blog.control-theory.com/entry/2024/01/21/model-error-compensator-mec) | [Qiita 記事](https://qiita.com/Hiroshi-Okajima/items/10256a84ed97602058b4) | [YouTube（日本語，34 分）](https://youtu.be/GceuMz3FkO0)

<img width="600" alt="MEC" src="https://github.com/user-attachments/assets/229323a7-5bc6-433f-9af8-4a2046132639" />

| 内容 | コード |
|------|--------|
| MEC の設計（ポリトープ型不確かさ，PSO + LMI） | [Robust-control-MATLAB_MEC01](https://github.com/Hiroshi-Okajima/Robust-control-MATLAB_MEC01) [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=Hiroshi-Okajima/Robust-control-MATLAB_MEC01) ・ [Python / Colab](https://github.com/Hiroshi-Okajima/python-google-colab) |
| センサノイズを考慮した MEC | [MATLAB_MEC02_sensor_noise](https://github.com/Hiroshi-Okajima/MATLAB_MEC02_sensor_noise) [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=Hiroshi-Okajima/MATLAB_MEC02_sensor_noise) |
| PFC 付き MEC（非最小位相零点への対処） | [MATLAB_MEC03_withPFC](https://github.com/Hiroshi-Okajima/MATLAB_MEC03_withPFC) [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=Hiroshi-Okajima/MATLAB_MEC03_withPFC) |
| 非線形系用 MEC | [non_linear_control_MATLAB_MEC04](https://github.com/Hiroshi-Okajima/non_linear_control_MATLAB_MEC04) [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=Hiroshi-Okajima/non_linear_control_MATLAB_MEC04) |
| 信号制限フィルタ | [MATLAB_MEC05_signal_limitation_filter](https://github.com/Hiroshi-Okajima/MATLAB_MEC05_signal_limitation_filter) [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=Hiroshi-Okajima/MATLAB_MEC05_signal_limitation_filter) |
| 車両制御への応用 | [Vehicle_control_MEC05](https://github.com/Hiroshi-Okajima/Vehicle_control_MEC05) [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=Hiroshi-Okajima/Vehicle_control_MEC05) ・ [ビークル制御の研究ページ](https://www.control-theory.com/jp/%E7%A0%94%E7%A9%B6%E3%83%93%E3%83%BC%E3%82%AF%E3%83%AB%E5%88%B6%E5%BE%A1) |

### マルチレートシステム制御

- [まとめページ](https://www.control-theory.com/jp/%E7%A0%94%E7%A9%B6%E3%83%9E%E3%83%AB%E3%83%81%E3%83%AC%E3%83%BC%E3%83%88%E5%88%B6%E5%BE%A1)

| 内容 | コード | 論文 |
|------|--------|------|
| マルチレート定常カルマンフィルタ（LMI 設計） | [multirate-kalman-filter](https://github.com/Hiroshi-Okajima/multirate-kalman-filter)（MATLAB / Python） | H. Okajima, IEEE Access, 2026（Open Access）・[arXiv:2602.01537](https://arxiv.org/abs/2602.01537) |
| マルチレート状態オブザーバ（l2 誘導ノルム） | [Code Ocean](https://codeocean.com/capsule/3611894/tree) | Okajima, Hosoe, Hagiwara, [IEEE Access, 2023](https://ieeexplore.ieee.org/document/10054014)（Open Access） |
| マルチレートシステム同定 | [MATLAB_system_identification](https://github.com/Hiroshi-Okajima/MATLAB_system_identification) | Okajima, Furukawa, Matsunaga, J. Robotics and Mechatronics, Vol. 37, No. 5, 2025（Open Access）・[arXiv:2503.12750](https://arxiv.org/abs/2503.12750) |

### 状態推定

- 研究ページ：[状態推定](https://www.control-theory.com/jp/%E7%A0%94%E7%A9%B6%E7%8A%B6%E6%85%8B%E6%8E%A8%E5%AE%9A) | [MCV オブザーバ](https://www.control-theory.com/en/mcv-observer)

| 内容 | コード | 論文 |
|------|--------|------|
| Luenberger / Kalman / H∞ / マルチレート / MCV オブザーバ（統合コード集） | [MATLAB_state_observer](https://github.com/Hiroshi-Okajima/MATLAB_state_observer) ・ File Exchange：[Multi-Rate Observer](https://jp.mathworks.com/matlabcentral/fileexchange/182941)，[MCV Observer](https://jp.mathworks.com/matlabcentral/fileexchange/182942) | — |
| 外れ値にロバストな MCV オブザーバ（原論文コード） | [MATLAB_state_estimation](https://github.com/Hiroshi-Okajima/MATLAB_state_estimation) | Okajima, Kaneda, Matsunaga, [SICE JCMSI, Vol. 14, 2021](https://www.tandfonline.com/doi/full/10.1080/18824889.2021.1985702)（Open Access） |

### システム同定

- 研究ページ：[システム同定](https://www.control-theory.com/en/system-identification)

| 内容 | コード | 論文 |
|------|--------|------|
| 周期時変系（LPTV）の巡回再定式化に基づく同定 | [MATLAB_system_identification](https://github.com/Hiroshi-Okajima/MATLAB_system_identification) | Okajima, Fujimoto, Oku, Kondo, [IEEE Access, 2025](https://ieeexplore.ieee.org/document/10858707)（Open Access） |

### 量子化制御（動的量子化器）

- [量子化器の研究ページ](https://sites.google.com/view/deltasiguma)

| 内容 | コード | 論文 |
|------|--------|------|
| 通信レート制約下の動的量子化器設計 | [MATLAB_Dynamic_Quantizer01](https://github.com/Hiroshi-Okajima/MATLAB_Dynamic_Quantizer01) [![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=Hiroshi-Okajima/MATLAB_Dynamic_Quantizer01) | Okajima, Sawada, Matsunaga, [IEEE Trans. Automatic Control, Vol. 61, No. 10, 2016](https://ieeexplore.ieee.org/document/7358078) |

---

## 引用について

各リポジトリの README に対応論文を記載しています．コードを利用された場合は，対応論文の引用をお願いします．
