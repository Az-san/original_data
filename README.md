【PROHIBITED DO NOT CHANGE】

実験で使用したROSシステムの使用方法
1) 端末(ターミナル)を開いて以下の2行を実行する
   cd rosi_ws/src/robot_pkg
   bash start_ee_simX.sh A

   ※末尾のAは地図の種類を表し、A-Cの3種類がある

2) Gazebo、Rvizなどの起動を待つ

3) 別ウインドウで端末(ターミナル)を開いて以下の2行を実行する
   cd rosi_ws/src/robot_pkg
   bash start_ee_robotV.sh True
   ※末尾のTrueはミニマップの表示有無。True：表示する、False：表示しない

4) 実験条件を入力する

5) Press enter to startでエンターを押して開始

実験用のROSシステムで中心になる2つのファイル
/home/user/rosi_ws/src/robot_pkg/script/node/MS_main.py
/home/user/rosi_ws/src/robot_pkg/script/node/MS_maze_search_node.py
