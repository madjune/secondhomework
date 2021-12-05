# VimGolf 과제


## 첫번째 문제 Add quotes to ansible playbook 5f0f5fbe280fbf000c233304
![GOMCAM-20211205_0218380814](https://user-images.githubusercontent.com/94767794/144731224-3d4e85f2-6602-41c8-a61c-998702d46baa.gif)
최고점 : 8 \
내풀이점수 : 9
> 1) G : 마지막줄로 이동 (1)
> 2) W : 다음단어의 시작으로 이동( {앞으로 이동) (2)
> 3) i : 현재 위치부터 입력모드 시작 (3)
> 4) " : "입력 (4)
> 5) (end) : end키로 그줄의 마지막으로 이동 (5)
> 6) " : "입력 (6)
> 7) (esc) : 입력모드 종료 (7)
> 8) ZZ : 저장후 나오기  (9) \
> 수업에서 알려준 이상은 모르겠습니다.


## 두번째 문제 simple replacements 603ba26a01b4d00009c10a49
![GOMCAM-20211205_0258560494](https://user-images.githubusercontent.com/94767794/144731621-06c11a36-8f23-4acc-8676-4d57b140890b.gif)
최고점 : 19 \
내풀이점수 : 28
> 1. :%s/sublime\|emacs/vim/g|wq(ENTER) : String 치환인 :%s/str/replace/g에 \|를 이용해 sublime과 emacs를 동시에 치환하면서 |를 이용 동시에 저장후 나옴 (28)

## 세번째 문제 Satisfy the go linter 5f1063aa8361810006e73210
![GOMCAM-20211205_1204280309](https://user-images.githubusercontent.com/94767794/144731925-57d75c3b-a583-4aee-98ff-2980cda96b47.gif)
최고점 : 20 \
내풀이점수 : 35
> 1. :4(Enter) : 4번째 줄로 이동 (3)
> 2. yw : 단어복사 (Version 복사) (5)
> 3. O : 현재 줄은 다음 줄로 넘기고 입력모드시작 (6)
> 4. // TODO(esc) : // TODO입력후 입력모드종료 (14)
> 5. b : 앞 단어의 앞으로 이동(TODO앞으로) (15)
> 6. P : 그 위치에 붙여넣기 (Version 입력됨) (16)
> 7. (down)(down) : 아래로 2번 내려감 (18)
> 8. 0 : 그 라인의 맨 앞으로 이동(19)
> 9. w : 앞 단어의 앞으로 이동(Debug 앞으로)(20)
> 10. yw : 단어복사 (Debug 복사) (22)
> 11. O : 현재 줄은 다음 줄로 넘기고 입력모드 시작 (23)
> 12. // TODO(esc) : // TODO입력후 입력모드 종료 (31)
> 13. b : 앞 단어의 앞으로 이동(TODO 앞으로) (32)
> 14. P : 그 위치에 붙여넣기 (Debug 입력됨) (33)
> 15. ZZ :저장후 종료 (35)

## 네번째 문제 Plotting some variables in python 9v0060da5177000000000209
![GOMCAM-20211205_1026410758](https://user-images.githubusercontent.com/94767794/144732225-ed288983-4248-48de-b733-67242e11da30.gif)
최고점 : 34 \
내풀이점수 : 59
> 1. :%s/y1/abs(y1)/g(Enter) : 모든 y1을 abs(y1)으로 치환함(String 치환) (17)
> 2. gg : 맨 앞으로 돌아옴 (19)
> 3. /1(Enter) : 1탐색 (22)
> 4. nnn : 첫줄의 1은 넘기고 4번째 1으로 이동 (25) 
> 5. r2 : 뒤char(1)을 2로 바꿈(27)
> 6. n.n. : 다음 1로 이동후(n) 마지막 행동 반복(.)(r2) (31)
> 7. nr3 : 다음 1로 이동후(n) 뒤char(1)을 3으로 바꿈(34)
> 8. n.n. : 다음 1로 이동후(n) 마지막 행동 반복(.)(r3) (38)
> 8. nr4 : 다음 1로 이동후(n) 뒤char(1)을 4로 바꿈(41)
> 9. n.n. : 다음 1로 이동후(n) 마지막 행동 반복(.)(r4) (45)
> 10. /k(Enter) : k탐색 (48)
> 11. nrb : 다음 k로 이동후(n) 뒤char(k)을 b로 바꿈 (51)
> 12. nrr : 다음 k로 이동후(n) 뒤char(k)을 r로 바꿈 (54)
> 13. nrg : 다음 k로 이동후(n) 뒤char(k)을 g로 바꿈 (57)
> 14. ZZ : 저장후 종료 (59)

## 다섯번째 문제 Python dataclasses 6013804df3308e0009368f1c
![GOMCAM-20211205_1120540117](https://user-images.githubusercontent.com/94767794/144732649-4ce68c0f-2caf-4ae4-9308-662ce50f4dbc.gif)
최고점 : 19 \
내풀이점수 : 29
> 1. :5(Enter) : 5번째 줄로 이동(3)
> 2. yw : 단어복사(student_id) (5)
> 3. G : 맨아래 라인으로 이동 (6)
> 4. (up) : 위로 한번 이동(7)
> 5. f" : 그 라인의 첫번쨰 "를 탐색해 그 앞으로 이동 (9)
> 6. p : 한 칸 뒤에 붙여넣기함("뒤에 student_id입력") (10)
> 7. a : 다음 칸에서 입력모드를 시작함 (11)
> 8. ,name,age,score(Enter) : ,name,age,score를 입력한뒤 입력모드 종료(27)
> 9. ZZ : 저장후 종료 (29) \
>> 8에서 저렇게 안쓰고 뭐 복사해서 옮긴다든가 시도는 여러가지 해봤으나 오히려 길어져서 그냥 타이핑 하기로 했습니다.


### 여기까지 vimgolf 과제를 마칩니다~

>> 채점 수고하셨습니다

