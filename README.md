# 사다리 게임
## 진행 방법
* 사다리 게임 게임 요구사항을 파악한다.
* 요구사항에 대한 구현을 완료한 후 자신의 github 아이디에 해당하는 브랜치에 Pull Request(이하 PR)를 통해 코드 리뷰 요청을 한다.
* 코드 리뷰 피드백에 대한 개선 작업을 하고 다시 PUSH한다.
* 모든 피드백을 완료하면 다음 단계를 도전하고 앞의 과정을 반복한다.

## 온라인 코드 리뷰 과정
* [텍스트와 이미지로 살펴보는 온라인 코드 리뷰 과정](https://github.com/nextstep-step/nextstep-docs/tree/master/codereview)

# 기능 요구사항
**참여자**
* 참여하는 이름의 최대 5글자

**사다리**
* 최대 글자 5자 기준으로 사다리 폭 구현
* 사다리는 겹치면 안된다.
* ex) |-----|-----|
* 사다리의 높이를 갖고 있어야된다.
* 사다리 게임의 결과를 갖고 있어야된다.
* 당첨자의 정보를 갖고 있어야된다.

**입력**
* 사람 이름은 쉼표(,)를 기준으로 구분한다.
* 실행 결과는 쉼표(,)를 기준으로 구분한다.
* 최대 사다리의 높이를 숫자로 입력 받아야된다.

**출력**
* 사다리 출력을 할때 사람이름도 같이 출력
* 사다리 출력을 할때 결과도 같이 출력
* 결과를 보고 싶은 사람을 지정해서 출력
* ALL 입력시 전원 이름과 결과값 출력 



# 프로그래밍 요구사항
* 자바 8의 스트림과 람다를 적용해 프로그래밍한다.
* 규칙 6: 모든 엔티티를 작게 유지한다.

# 실행 결과
* 위 요구사항에 따라 4명의 사람을 위한 5개 높이 사다리를 만들 경우, 프로그램을 실행한 결과는 다음과 같다.
```
참여할 사람 이름을 입력하세요. (이름은 쉼표(,)로 구분하세요)
pobi,honux,crong,jk

최대 사다리 높이는 몇 개인가요?
5

실행결과

pobi  honux crong   jk
    |-----|     |-----|
    |     |-----|     |
    |-----|     |     |
    |     |-----|     |
    |-----|     |-----| 
```