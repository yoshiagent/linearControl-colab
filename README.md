# 線性控制：原課程 MATLAB 程式的 Python 筆記本

「[線性控制 Linear Control](https://yoshiagent.github.io/linearControl/)」課程原本以 MATLAB／Simulink 示範。這裡把原課程的 MATLAB 程式與 Simulink 模型改寫成 Python 筆記本，可以直接在 Google Colab 執行，不需要安裝任何軟體。

| 筆記本 | 內容（原課程的檔案） | 對照的網頁 | 開啟 |
|---|---|---|---|
| [狀態空間設計](notebooks/StateSpace_Design.ipynb) | phasevariable.m（相變數標準式）、poleplaceregu.m（Regulator 極點配置）、poleplace.m（Type 1 Servo）、observer.m（全階觀測器）、observerregulator.m（觀測器＋狀態回授，倒單擺） | [網頁](https://yoshiagent.github.io/linearControl/SS.html) | [![在 Colab 開啟](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yoshiagent/linearControl-colab/blob/main/notebooks/StateSpace_Design.ipynb) |

* 每本筆記本都先列出原本的 MATLAB 程式，再給逐段對應的 Python 版本，並已實際執行（存有輸出與圖）。
* 只用 Colab 內建的 numpy、scipy 與 plotly。
* 每本都用手算的特徵多項式驗證增益；原程式有誤的地方以「編註」標出並更正。
