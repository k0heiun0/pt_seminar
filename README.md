# 動画で上肢の動きを測る

マーカーレスモーションキャプチャー入門　理学療法士のための半日ワークショップの配布物です。ページ：https://k0heiun0.github.io/pt_seminar/

## スライド

| どれ | 開く | 中身 |
|---|---|---|
| 本編 | [スライド](https://k0heiun0.github.io/pt_seminar/slides/seminar.html)・[PDF](slides/seminar.pdf) | 今日の問い：スマホ動画1本から、この上肢は良くなったと言えるか |
| 発展編（任意） | [スライド](https://k0heiun0.github.io/pt_seminar/slides/seminar_advanced.html)・[PDF](slides/seminar_advanced.pdf) | 挙上面と挙上角・代償・手指・いろいろなモデル・筋骨格モデル・信頼性・用語集 |

## Colabノート

| どれ | 開く | 中身 |
|---|---|---|
| 実習ノート（本編） | [Colabで開く](https://colab.research.google.com/github/k0heiun0/pt_seminar/blob/main/notebooks/01_handson.ipynb) | 実習①：MediaPipeで肩の角度を2Dと3Dで測り、正解と比べる。実習②：手首の速さ |
| 発展のノート | [Colabで開く](https://colab.research.google.com/github/k0heiun0/pt_seminar/blob/main/notebooks/03_advanced.ipynb) | A 挙上面と挙上角、B 代償、C 手指（任意） |
| 推論用のノート | [Colabで開く](https://colab.research.google.com/github/k0heiun0/pt_seminar/blob/main/notebooks/00_body4d_inference.ipynb) | SAM-Body4Dで動画を処理し、正解と比べる（任意・GPUとHugging Faceの準備が必要） |

Colabで開いたら［ドライブにコピー］を押し、上から順に全部押してください。データは自動で読み込まれます。

## 配布データ

`data/` の動画と正解は、REHAB24-6（CC BY-NC 4.0）と Mendeley Data の上肢運動の動画（CC BY 4.0）から作りました。患者のデータではありません。出典・ライセンス・加工内容は [data/README.md](data/README.md) を見てください。

SAM-Body4D（推論用のノート）を試したい人は、先に [docs/handout-hf-setup.md](docs/handout-hf-setup.md) の準備を済ませてください。
