# Sudoku_Solver_Generator_v5.0 beta
  アップデートしました(202403017)。安定までには、しばらくかかります。５月頃、再度訪れてください。

以下、調整中 ##############
# コードの配布 再開　-> Sudoku_Solver_Generator_v5

# GNPX v5 HP:
  en: https://gidoo-code.github.io/Sudoku_Solver_Generator_v5/<br>
  jp: https://gidoo-code.github.io/Sudoku_Solver_Generator_v5_jp/<br>
<br><br>
# Sudoku_Solver_Generator v5
![GNPX](./images0/GNPX_start.png)<br>


## 1. GNPX v5 は、プログラムを大幅に改良しています。<br>
   GNPX v5 は、新アルゴリズムの開発・展開のバージョンです。スマートさは二の次です。<br>
   数独の解析アルゴリズム部分では、従来のコードとの連続性はありません。<br>

## 2. 数独解析アルゴリズムについて検討しました。<br>
   論理を説明するイメージ図を用いて解説します。（具体的では本質が理解しづらい）<br>
  (1) 数独解析における "Locked"<br>
  (2) ALSの拡張(AnLS)、アルゴリズムの開発<br>
  (3) eLink、ネットワークの拡張<br>
  (4) Fish のファミリー<br>
  (5) SueDeCoq のファミリー<br>
  (6) DeathBlossomのアルゴリズム考察<br>

## 3. GNPX v5 プログラム<br>
  (1) 多くの解析アルゴリズムを改良<br>
  (2) ビット表現(Bit81をUInt128に変更)<br>
