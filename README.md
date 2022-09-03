# lisp_language

## lisp 기초

- [Unleash The REPL With Sly](https://youtu.be/0DLdQ6yb7h8)

## emacs 에서 list - package 로 SLY 를 설치해 주자

- 그 다음 emacs 에서

```
M-x Sly
```

이거 하면

```

CL-USER> (+ 1 2)
3 (2 bits, #x3, #o3, #b11)

CL-USER>
```

파이썬 처럼 한줄 한줄 쳐서 코드를 확인할 수 있다.

<br>

<hr>

# 다른 방법 2

```
M-x sly-scratch
```

- 이거 하면 코드 scratch 화면에 입력하고

- C-x C-e

하면 바로 결과를 볼 수 있다.

내가 찾던 자료 ㅎㅎㅎ

- M-x sly-scratch 화면 예시

```
;; This buffer is for text that is not saved, and for Lisp evaluation.
;; To create a file, visit it with C-x C-f and enter text in its buffer.


```

- 이런 화면이 나온다. 그럼 빈 화면에 lisp코드를 입력해서 바로 결과를 볼 수 있다.

```
(+ 1 2)

) 여기에 커서를 올리고
C-x C-e


왼쪽 하단에 결과가 바로 나온다 .최고 !!

3 (2 bits, #x3, #o3, #b11)

이런 화면이 왼쪽 하단에 나오는걸 볼 수 있다.

```

자세한건 영상을 보면서 이해하자

- [Unleash The REPL With Sly](https://youtu.be/0DLdQ6yb7h8)

<br>

<br>

<hr>

# 또 다른 방법 3

```clips

(write-line "hello lisp")
```

emacs 에서 M-x

```clips
emacs-lisp-mode
```

Doom Emacs 기준

emacs-lisp-mode 작동 후에

hello.lisp

이 안에서

space - a - e

하면 바로 파일을 볼 수 있다.

e(pp-eval-expression)

이렇게 하면 한줄 한줄 바로 확인가능

<br>

⭐️⭐️⭐️⭐️⭐️⭐️⭐️⭐️⭐️⭐️⭐️⭐️⭐️

<hr>

# 다른 방법 4(난 이게 젤 편한것 같다. )

```
$ clisp hello.lisp
```

- 이렇게 그냥 쌩으로 실행하면 결과 하면 볼 수 있다. ㅋ

hello.lisp 파일 예시

```

(defun name()
  (princ "hello lisp "))

(name)

(terpri)

(defun name1()
  (princ "hell2 lisp \n"))

(name1)

```

- 이걸 실행하면 밑에 화면이 나온다.
  웃긴게 lisp에서 \n 이거 안된다 ㅋㅋㅋ

<br>

result :

```
$ clisp hello.lisp
hello lisp
hell2 lisp n
```

<br>

⭐️⭐️⭐️⭐️⭐️⭐️⭐️⭐️⭐️⭐️⭐️⭐️⭐️

<hr>

## 너무 좋은 자료 모음

[Lisp tutorial 최고 ](https://economiceco.tistory.com/14811)

<br>

<hr>

<br>

## Lisp Tutorial

Lisp Tutorial

[https://youtu.be/ymSq4wHrqyU](https://youtu.be/ymSq4wHrqyU)
