# Vimtutor

들어가기 전에
- [x] `<ESC>`를 이용하여 명령모드로 빠져 나옵니다. 
- [x] 한글일 때 작동되지 않습니다.
  
## 시작하기 (접속)

* vimtutor
* vim tutor.ko

---


### Lesson 1 

* hjkl (←, ↓, ↑, →) 위치이동
* x = 지우기
* i = 입력모드 (해당영역)
* a = 입력모드 (문장뒤)
* :wq = 저장후 나가기 
* :q! = 나가기 



#### 요  약

``` 
  1. 커서를 움직일 때에는 화살표 키나 hjkl 키를 이용합니다.
         h (왼쪽)       j (아래)       k (위)       l (오른쪽)
  2. 쉘 프롬프트에서 빔을 시작하려면 vim FILENAME <ENTER>
  3. 수정한 내용을 무시한 채로 빔에서 빠져나가려면   <ESC>   :q!   <ENTER>
                     저장한 후 빔에서 빠져나가려면   <ESC>   :wq   <ENTER>
  4. 명령 모드에서 커서가 위치한 곳의 글자를 지우려면   x  를 입력합니다.
  5. 명령 모드에서 커서가 위치한 곳에 텍스트를 삽입하려면
         i   를 누른 후 텍스트를 입력하고  <ESC>      커서 앞에 삽입합니다.
         A   를 누른 후 텍스트를 입력하고  <ESC>     문장 뒤에 추가 합니다.

참고: <ESC>는 명령 모드로 돌아가는 데 쓰며, 원치 않는 명령이나 완전히 입력되지
      않은 명령을 취소하는 데에도 씁니다. 
    
```


### Lesson 2
 
 
* dw = 단어 지우기
* de = 단어 지우기 (공백 미포함)
* d$ = 문장모두 지우기 (문장끝으로 이동)
* 2w = 두 단어 탭 
* 3e = 세 단어 탭 
* 0 = 문장 첫시작으로 이동 
* d(횟수)w = 횟수만큼의 단어삭제 ex) `d2w -> 두 번의 단어 삭제`
* (횟수)dd = 횟수만큼의 문장삭제(단어 첫머리이동) ex) `2dd -> 두 문장(줄) 삭제`
* u = 명령 취소 (cm + z 되돌리기 기능)
* U = 줄 전체 명령 취소
* contrl + R (취소한 것을 취소)


**** 요  약

```
1. 커서가 위치한 곳부터 단어의 끝까지 지우려면:    dw
  2. 커서가 위치한 곳부터 줄 끝까지 지우려면:    d$
  3. 줄 전체를 지우려면:    dd
  4. 횟수와 함께 대상을 반복 시키려면:    2w
  5. 명령 모드에서 내리는 명령의 형식은 다음과 같습니다:
       [횟수] 명령 대상    또는    명령 [횟수] 대상

     여기서:
       횟수 - 그 명령을 몇 번 반복할 것인가
       명령 - 어떤 명령을 내릴 것인가 ( 예를 들어, 삭제인 경우는 d )
       대상 - 명령이 동작할 대상, 예를 들어 w (단어), $ (줄의 끝) 등.

  6. 커서를 문장 맨 앞으로 옮기려면: 0
  7. 이전 행동을 취소하려면: u (소문자 u)
     한 줄에서 수정한 것을 모두 취소하려면: U (대문자 U)
     취소한 것을 다시 실행하려면: CTRL-R
     ```

