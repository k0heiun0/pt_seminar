# 動画で上肢の動きを測る

マーカーレスモーションキャプチャー入門　理学療法士のための半日ワークショップの配布物です。ページ：https://k0heiun0.github.io/pt_seminar/

## スライド

| どれ | 開く | 中身 |
|---|---|---|
| 本編 | [スライド](https://k0heiun0.github.io/pt_seminar/slides/seminar.html)・[PDF](slides/seminar.pdf) | 今日の問い：スマホ動画1本から、この上肢は良くなったと言えるか |
| 発展編（任意） | [スライド](https://k0heiun0.github.io/pt_seminar/slides/seminar_advanced.html)・[PDF](slides/seminar_advanced.pdf) | 仕組み・信頼性と妥当性・架空の症例・倫理・用語集 |

## Colabノート

| どれ | 開く | 中身 |
|---|---|---|
| 実習ノート（本編） | [Colabで開く](https://colab.research.google.com/github/k0heiun0/pt_seminar/blob/main/notebooks/01_handson.ipynb) | 実習①：肩の角度を測る（3節・4節）、実習②：手の動きの質を見る（5節） |
| 発展のノート | [Colabで開く](https://colab.research.google.com/github/k0heiun0/pt_seminar/blob/main/notebooks/03_advanced.ipynb) | 体幹の代償・肩と肘の協調・手首の軌跡（任意） |
| 自分の動画で動かす | [Colabで開く](https://colab.research.google.com/github/k0heiun0/pt_seminar/blob/main/notebooks/00_body4d_inference.ipynb) | SAM-Body4Dの推論（任意・GPUとHugging Faceの準備が必要） |

Colabで開いたら［ドライブにコピー］を押し、「2. データを持ってくる」のセルに講師から配られたIDを貼って、上から順に全部押してください。

## サンプルデータ

`data/` の2本は、公開されている動画（Pexels）をSAM-Body4Dで推論した結果です。患者のデータではありません。

自分の動画で試したい人は、先に [docs/handout-hf-setup.md](docs/handout-hf-setup.md) の準備を済ませてください。
