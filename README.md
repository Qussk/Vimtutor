# Vimtutor

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



#### LESSON 1 요약

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


