# 動画で上肢の動きを測る

マーカーレスモーションキャプチャー入門　理学療法士のための半日ワークショップの配布物です。ページ：https://k0heiun0.github.io/pt_seminar/

## スライド

| どれ | 開く | 中身 |
|---|---|---|
| 本編 | [スライド](https://k0heiun0.github.io/pt_seminar/slides/seminar.html)・[PDF](slides/seminar.pdf) | 今日の問い：スマホ動画1本から、この上肢は良くなったと言えるか |
| 発展編（任意） | [スライド](https://k0heiun0.github.io/pt_seminar/slides/seminar_advanced.html)・[PDF](slides/seminar_advanced.pdf) | 挙上面と挙上角・代償・SAM 3D Body（無料のColab）・筋骨格モデル・信頼性・用語集 |

## Colabノート

| どれ | 開く | 中身 |
|---|---|---|
| 実習ノート（本編） | [Colabで開く](https://colab.research.google.com/github/k0heiun0/pt_seminar/blob/main/notebooks/01_handson.ipynb) | 実習①：MediaPipeで肩の角度を2Dと3Dで測り、正解と比べる。実習②：手首の速さ。実習③：飲水動作。実習④：手指 |
| 発展のノート | [Colabで開く](https://colab.research.google.com/github/k0heiun0/pt_seminar/blob/main/notebooks/03_advanced.ipynb) | A 挙上面と挙上角、B 代償（任意） |
| 発展のノートC | [Colabで開く](https://colab.research.google.com/github/k0heiun0/pt_seminar/blob/main/notebooks/02_sam3d_body.ipynb) | SAM 3D Bodyで肩挙上角を測り、正解・MediaPipeと比べる（任意・無料のColabのT4 GPUとHugging Faceの申請が必要） |
| 参考のノート | [Colabで開く](https://colab.research.google.com/github/k0heiun0/pt_seminar/blob/main/notebooks/00_body4d_inference.ipynb) | SAM-Body4Dで動画を処理する（参考・無料のT4ではメモリが足りず止まる。有料のL4・A100が必要で未確認） |

Colabで開いたら［ドライブにコピー］を押し、上から順に全部押してください。データは自動で読み込まれます。

## 配布データ

`data/` の動画と正解は、REHAB24-6（CC BY-NC 4.0）と Mendeley Data の上肢運動の動画（CC BY 4.0）から作りました。患者のデータではありません。出典・ライセンス・加工内容は [data/README.md](data/README.md) を見てください。

SAM 3D Body（発展のノートC）を試したい人は、先に [docs/handout-hf-setup.md](docs/handout-hf-setup.md) の準備を済ませてください。
