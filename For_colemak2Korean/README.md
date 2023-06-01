## 적용방식(how to apply)
### 날개셋 키보드 적용
0. 키맵핑기능이 있는 키보드에 콜맥을 적용합니다(필자의 경우 AnnePro2).
1. 해당 윈도우에 [날개셋](http://moogi.new21.org/ngs_download.htm)을 설치한 뒤, cole2han.set을 설정에서 가져오기로 적용합니다.
2. 윈도우 키배열을 날개셋으로 적용하면, 윈도우에서 콜맥과 한글2벌식을 사용합니다.
3. 한글 2벌식의 'ㅔ'와 ';'의 위치를 바꿨습니다.
4. .key와 .ist파일은 설정 적용이 안 될 경우를 대비하여 개별적용하기위해 준비했습니다.
---
### 콜맥유저를 위한 vim 에디터 hjkl키 변경
0. .vimrc파일을 사용자의 home 디렉토리에 저장합니다.
``` shell
mv .vimrc ~/.vimrc
```
1. n는 좌, o는 우, i는 상, e는 하 입니다.
2. 그 외 나머지는 qwerty의 vim키 위치를 그대로 가져왔으나, yank는 j로 paste는 h로 변경했습니다.
---
### vim editor hjkl key modification for colemak user
0. put this .vimrc file at your home directory.
``` shell
mv .vimrc ~/.vimrc
```
1. n to left, o to right, i to up, e to down.
2. most of other vim key location follows that of qwerty's. however yank is j and paste is h. 

