# 혼자하는 끝말잇기 게임

<br/>

* 각각의 다른 저장소 2개로 끝말잇기 게임 진행

**제시어**

1st round

* 깃허브 - wordchain1
* 브라질 - wordchain2

2nd round

* 질갱이 - wordchain1
* 이발소 - wordchain2

3rd round

* 소나기 - wordchain1
* 기념품 - wordchain2

=================================================== End Game^^



#### review


> 수업 시간에는 다른 수강생 분과 같이 진행해서 재미있었는데, 혼자하니 재미는 별로다ㅋㅋ 일딴 원리는 같다. 각각의 다른 저장소를 이용해서 한 저장소에서 커밋하면 다른 저장소로는 커밋된 파일을 내려 받는다.
>
> ```shell
> //wordchain1 저장소
> 
> $ git add README.md
> $ git commit -m "1"
> $ git push origin master
> 
> 
> //wordchain2 저장소
> 
> $ git pull
> $ code . //끝말잇기 작성
> $ git add README.md
> $ git commit -m "2"
> $ git push origin master
> 
> 
> //wordchain1 저장소
> 
> $ git pull
> $ code . //끝말잇기 작성
> $ git add README.md
> $ git commit -m "3"
> $ git push origin master
> 
> //여기서부터는 계속 번갈아 가면서 진행
> ```
>
> 
>
> 복습 덕분에 **add, commit, push, pull** 의 사용법을 확실히 숙지한 것 같다. 다음에는 내 리퍼지토리에 권한을 부여하는 방법을 찾아봐야 겠다. 수업시간에 나는 권한을 주는 쪽이 아니라서 그건 실습을 못 해봤다ㅠ
>
> 


