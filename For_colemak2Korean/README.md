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
1. h는 좌, l은 우, j는 상, n은 하 입니다.
2. k는 검색에서 다음 단어를 찾을 때 이용하도록 배열했습니다(qwerty와 같은 자리입니다).
---
### vim editor hjkl key modification for colemak user
0. put this .vimrc file at your home directory.
``` shell
mv .vimrc ~/.vimrc
```
1. h to left, l to right, j to up, n to down.
2. k is mapped to move to next word at searching(same key location of qwerty vim). 

