# yaskk
yet another skk for terminal

# description
端末上で動作する簡易なskkです．

# mode

## ASCII
-	Ctrl + J: ひらがなモードへ

## ひらがな・カタカナ
-	ESC: ASCIIモードへ
-	'l': ASCIIモードへ
-	'q': ひらがな・カタカナのトグル
-	uppercase: 変換モードへ

## 変換
-	Ctrl + J: 入力中の文字列を確定させる
-	ESC: 変換モードを抜ける
-	SPACE: 選択モードへ
-	'L': ユーザ辞書の再読み込み
-	uppercase: 送り仮名モードへ

## 送り仮名
-	Ctrl + J: 入力中の文字列を確定させる(送り仮名は含まない)
-	ESC: 変換モードへ
-	uppercase: 無視(小文字として扱われる)

## 選択
-	Ctrl + P or 'x': 前候補へ
-	Ctrl + N or SPACE: 次候補へ
-	Ctrl + J: 選択中の候補を確定させる
-	ESC: 変換モードへ
-	'l': 選択中の候補を確定しASCIIモードへ
-	'q': 選択中の候補を確定しひらがな・カナカナのトグル
-	others: 選択中の候補を確定し変換モードへ

# license
Copyright (c) 2012 haru (uobikiemukot at gmail dot com)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
