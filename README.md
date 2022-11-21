# 미션 - 다리 건너기

## 기능 구현 목록
  - 입력
    - 다리길이 입력(3이상 20이하의 숫자)
    - 라운드마다 플레이어 이동값 입력 위,아래(U,D)대문자만 가능
    - 게임 재시작/종료(R,Q) 입력
  - 출력   
    - 이동할수있는칸(O),이동할수없는칸(X)
    - 다리의 시작,끝은 []
    - 다리 칸의 구분은 '|' 구분
    - 총 시도횟수 출력
  - 생성
    - 무작위 값이 0인경우 아래칸,
    - 무작위 값이 1인경우 위칸이 건널수 있는 칸
  
-예외처리
  - [ERROR]로 에러문구 시작 
  - IllegalArgumentException, IllegalStateException으로 처리
  - 


