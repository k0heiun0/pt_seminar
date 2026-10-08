# 配布データ

セミナーの実習ノートが読み込むデータです。`tools/prepare_data.py` で、下の2つの公開データから作りました。

## rehab24/：肩の外転（本編の実習①・②、発展A・B）

| ファイル | 中身 |
|---|---|
| front.mp4 | 右腕の外転を、正面から撮った29.3秒（正しく行った5回） |
| side.mp4 | front.mp4 と同じ時刻を、本人の左側（横）から撮ったもの |
| oblique.mp4 | 体を斜めに向けて行った外転、23.9秒（正しく行った5回） |
| *_truth.csv | モーションキャプチャーから出した正解の角度（コマごと）。elevation＝右肩の挙上角（上腕と体幹のなす角、度）、plane＝挙上面（胸郭の座標系で0°＝真横、+90°＝真前。挙上角30°未満は空欄） |
| *_truth_wrist.csv | 正解の右手首の位置（骨盤の中点からの相対位置、メートル） |

- 出典：REHAB24-6（Masaryk大学）。https://zenodo.org/records/13305826
- 引用：Černek, A., Sedmidubsky, J., Budikova, P.: REHAB24-6: Physical Therapy Dataset for Analyzing Pose Estimation Methods. SISAP 2024.
- ライセンス：CC BY-NC 4.0（学術・非営利の非商用の利用に限る）。このフォルダのファイルも同じライセンスで配布します。
- 加工：9番の人（PM_114）の腕の外転（Ex1）から区間を切り出し（正面・横は280〜1159コマ目、斜めは3262〜3979コマ目）、高さ720ピクセルに縮め、音声を外しました。正解の角度と手首の位置は、モーションキャプチャーの26関節（30fps）から計算しました。

## hand/：物を持ち上げる手（本編 7. 手指、実習④）

| ファイル | 中身 |
|---|---|
| lift_complete.mp4 | ボトルを持ち上げる運動を、できた回（11.5秒） |
| lift_incomplete.mp4 | 同じ人の、できなかった回（演じたもの、10.7秒） |

- 出典：An upper limb stroke rehabilitation exercise video dataset（Mendeley Data）。https://data.mendeley.com/datasets/49h9dcwx5v/1 、DOI 10.17632/49h9dcwx5v.1
- 健常な人が、片麻痺の人向けの運動を演じたものです。患者のデータではありません。
- ライセンス：CC BY 4.0
- 加工：01_01_01_01.mp4 と 01_01_00_01.mp4 を、高さ720ピクセルに縮め、音声を外しました。

## reach/：飲水動作（本編 6. 生活の動き、実習③）

| ファイル | 中身 |
|---|---|
| drink.mp4 | コップを口元へ運んで飲む動き（26秒、正解なし） |

- 出典：Pexels の動画 4058079。https://www.pexels.com/video/4058079/
- ライセンス：Pexels License（無料で利用・改変可、クレジット不要）
- 加工：元の動画（1080×2048、25fps）の9.6秒から26秒間を切り出し、高さ1280ピクセルに縮め、音声を外しました。

## sample_outputs/：旧版のデータ

SAM-Body4D で推論した旧版のサンプル（rom_task・reaching）です。今の本編では使いません。
