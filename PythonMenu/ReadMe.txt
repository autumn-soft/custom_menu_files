==============================================================
Pythonのコードを簡単に入力するためのカスタムメニュー
                                                       Ver1.04
                                     2023/02/08   オータム西野
                            [E-Mail] hiroshi24@autumn-soft.com
                      [Web Site] https://autumn-soft.github.io
==============================================================

● インストール
~~~~~~~~~~~~~~~
PythonMenu.zipに含まれているファイルは以下のとおりです。

ReadMe.txt : このファイル
PythonMenu.txt : メニューファイルの本体

・以下のファイルはPythonMenu.txtの中から自動的にインポートします。

PyPip.txt : pipの定型パターン
PyPipEnv.txt : pipenvの定型パターン
PyConda.txt : condaの定型パターン
PyBasic.txt : Pythonの定型パターン
PyNumPy.txt : NumPyの定型パターン
PyPandas.txt : Pandasの定型パターン
PyMatplotlib.txt : Matplotlibの定型パターン
PySeaborn.txt : Seabornの定型パターン
PyPlotly.txt : Plotlyの定型パターン
PyWebScraping.txt : BeautifulSoup, Seleniumの定型パターン
PyScikitLearn.txt : Scikit-learnの定型パターン
PySymPy.txt : SymPyの定型パターン

ペースターのデータフォルダの中に新しく「PythonMenu」などの
サブフォルダを作成して、上記のファイル一式をコピーして下さい。

そして、［ペースターの設定ダイアログ］－［カスタムメニュー］タブ
にある「カスタムメニューの設定」の「追加」ボタンを押して、
「PythonMenu.txt」をリストに追加して下さい。

最後に、下にあるショートカットキーの設定の欄で、
お好きな呼び出しキーを選んで「設定▲」ボタンを押します。
私は、[Alt]+[Ctrl]+Pキーを設定しています。

SeabornやPlotlyの各種のメソッドではリストメニューを表示しますが、
上部にある「複数項目を選択した場合」のコンボボックスでは、
「キー操作で改行」を選択してください。
キー操作で改行することにより、VS CodeやJupyter Labのインデント処理が
適切に行われます。
なお、選択する引数が２～３個で一行で収まる場合には、
「改行せずに連結」を選択してください。


● カスタマイズ
~~~~~~~~~~~~~~~
各自でメニューファイルを追加したり、カスタマイズする場合には、
上記のファイル名とかぶらないようにしてください。
例えば、自分専用のNumPy用のファイルを作成した場合には、
PyNumPy_taka.txt
などの名前を付けて、PythonMenu.txtからインポートしてください。

● サポート
~~~~~~~~~~~
ご意見・ご質問・バグ報告などは、
ホームページにあるお問い合わせフォームか、メールにてお願いします。

● その他
~~~~~~~~~
ペースターはドネーションウェアとなっています。
基本的にはフリーソフトですので、すべての機能を無期限、無制限で
使用することができます。

ただ、もしペースターの開発を支援して頂ける方は、
寄付という形でサポートして頂けると大変嬉しく思います。

https://autumn-soft.github.io/paster.htm#donation

--- 以上 ---
