# 구현할 기능 목록

- validation!!! : 검증 실패 시 오류를 던지는 메서드

## MESSAGE

- 경주할 자동차 이름을 입력하세요.(이름은 쉼표(,) 기준으로 구분)
- 시도할 횟수는 몇 회인가요?
- 실행 결과
- 최종 우승자 : 이름, 이름

## ready

- 경기 시작 전 필요한 정보를 입력받는 메서드
  - 차 이름 목록을 입력받는 함수
  - 차 이름 문자열을 검증하는 함수
  - validation!!! 경기 시도 횟수를 입력받는 함수
  - validation!!! 경기 시도 횟수가 숫자인지 검증하는 함수

## start

- 준비 단계에서 집계된 변수를 이용해 경기를 진행하는 메서드
  - 입력받은 경기 시도횟수만큼 반복시키는 함수
  - 랜덤으로 각 차별로 전진시켜 매 경기마다 결과를 출력하는 함수

## end

- 경기를 모두 진행 후 우승자를 출력하는 메서드
  - 각 경기 참가자들의 전진 횟수를 이용해 최댓값을 계산한다.
  - 계산된 최댓값을 이용해 우승자를 집계한다.
  - 집계된 우승자를 출력한다.