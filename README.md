# random_Q_learning

最短経路問題のランダムなグリッドフィールド環境を作成して、Q学習するプログラム  
（河野先生の学習用プログラムを一部改変して作成）

---

## HOW TO USE

1. シェルからmain.pyを実行する
2. 環境の生成と学習を規定回数分繰り返す（ログがシェルに出力される）
3. Qテーブル、学習状態を記載したCSVファイルが出力される
---

## Introduciton of files

1. main.py : メインの実行用スクリプト
2. agent.py : エージェントの行動や評価、CSV保存関係
3. config.py : path、各種設定用スクリプト
4. environment.py : pygameの描写処理
5. world.py : グリッドフィールド情報
6. make_maze.py : ランダムなグリッドフィールドを作成
7. graph.py : 本プログラムでは未使用
8. scope.py : 本プログラムでは未使用 (なら削除しろ)
