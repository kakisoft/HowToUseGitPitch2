### GitHubだけで作成するスライド
設定編
　  

　  
　  
　  
　　　　垣花　暁
---
このスライドの作成に、  
「GitPitch」というサービスを使っています。
---
最初にこんなの作りました。  
https://gitpitch.com/kakisoft/HowToUseGitPitch/master
---
今回は、各種設定の話です。
---
PITCHME.yaml  
というファイルを作成し、設定を記述します。
<img src="img/01.png">
---
まずはテーマ。
---
ここのテーマは  
　  
### theme :night

と指定しています。  
　  
他には ・・・
---?image=img/02.png
---?image=img/03.png
---?image=img/04.png
---?image=img/05.png
等のテーマがあります。
---
左下のメニューより、  
一時的にテーマを変更する事も出来ます。  
<img src="img/06.png">  
※テーマ未設定時のみ有効
---
背景。
---?image=img/07.png
テーマとの併用は難しそうなので、  
どちらかを選べばいいと思います。
---
画面遷移時のアクション
---
### transition : fade
等で、遷移時のアクションを設定できます。  
convex, concave, default,  
fade, none, slide, zoom
が設定できるようです。
---
ロゴ。
---
### logo : assets/logo.png
等で、ロゴを表示できます。  
（左の画像です）
---
スライド番号
---
### slide-number: true
で、番号をつける事ができます。  
（右下の番号です）
---
フットノート
---
### footnote : "© 2017 kakisoft"
等で、フットノートが設定できます。  
（左下の内容です）
---
コードハイライト
---

```
ここは
highlight : monokai
と設定した場合です。
```
a
```
ここは
highlight : mono-blue
と設定した場合です。
```
---
また、
### autoslide : 5000  
と設定することで、
5秒おきにスライドが自動で流れます。
---
```
<!-- .slide: data-autoslide="1000" -->
```
と記述すれば、スライド単位での  
遷移時間が設定可能です。
---
「５分きっかりで終わらせたい」  
といった時に有効ですね。
---
他にも色々あるので
---
詳細は、公式サイトを参照して下さい。
https://github.com/gitpitch/gitpitch/wiki/Slideshow-Settings
---
おわり
