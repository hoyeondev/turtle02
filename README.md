# turtle02
- pyamaze를 활용한 미로찾기
- 참고 : https://github.com/MAN1986/pyamaze

# 설치 
- pyamaze 1.0.1

# loopPercent
loopPercent 값은 미로의 루프 복잡성 정도를 나타냅니다:

## loopPercent=0: 루프가 전혀 없는 단순한 트리 구조 미로
- 각 지점에서 목적지까지 유일한 경로만 존재
막다른 길이 많음

## loopPercent=50: 중간 정도의 복잡성
- 가능한 루프의 절반 정도를 포함
일부 대안 경로와 순환 구조 존재

## loopPercent=100: 최대 복잡성
- 생성 가능한 모든 루프를 포함
매우 많은 대안 경로와 순환 구조
여러 방법으로 같은 지점에 도달 가능
