# GitHub

## 1. 원격 저장소를 만든다.
>원격 저장소를 통해서 로컬을 연결을 할겁니다.

1. github (+)버튼 'Create a new repositoy'
2. 저장소의 주소 복사한다.

</br>

## 2. 로컬 저장소와 원격 저장소 연결

```bash

git remote add origin "github주소"

git remote -v

git remote rm origin
```

### remote add origin "github주소"
   * 우리는 통로를 만들것이다.
   * 그 통로의 이름은 'origin'이며, 통로의 목적지는 "github주소"이다.

</br>

## 3. 원격 저장소에 업로드
>git에서 하는 방법 + 'push'

</br>

### git push

```bash

    git push origin master
```

### git push origin master
* 'origin' 통로에 push를 할 것이다. 'master' branch를

</br>

### 주의 사항: Github로 관리하는 것은 최대한 피한다.
* 깃의 주된 목적 중 하나는 로컬과 원격 저장소와의 동기화이다.
* github에서 직접적인 수정(Commit)을 한다면, 위 절차를 무시하는 것이다.

