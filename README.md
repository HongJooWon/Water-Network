# Water-Network

① Accelerometer — 가속도 데이터

배관 표면의 진동을 측정합니다. 누수로 인해 발생하는 배관 진동의 변화를 분석하는 데 적합합니다.
첫 번째 실습 추천

② Dynamic Pressure Sensor — 동압 데이터

배관 내부의 압력 변동을 측정합니다. 누수에 따른 압력 신호의 변화와 순간적인 변동을 분석할 수 있습니다.
두 번째 실습 추천

③ Hydrophone — 수중음향 데이터

물속으로 전달되는 소리를 측정합니다. 누수음과 주변 소음의 주파수 특성을 분석할 수 있습니다. RAW 파일을 먼저 변환해야 합니다.

**기호	의미	예시**
T	관망 구조(Topology)	BR, LO
L	누수 유형(Leak type)	NL, OL, LC, CC, GL
F	배경 유량(Flow)	ND, 0.18 LPS, 0.47 LPS
S#	센서 종류 및 번호	A1, A2, P1, P2

각 코드의 의미는 다음과 같습니다.
- BR: Branch, 분기형 관망
- LO: Looped, 루프형 관망
- NL: No Leak, 정상 상태
- OL: Orifice Leak, 구멍 형태 누수
- LC: Longitudinal Crack, 배관 길이 방향 균열
- CC: Circumferential Crack, 배관 둘레 방향 균열
- GL: Gasket Leak, 연결부 가스켓 누수
- ND: 배경 유량이 없는 조건
- 0.18 LPS, 0.47 LPS: 배경 유량이 각각 초당 0.18L, 0.47L인 조건
예를 들어 BR_CC_0.18 LPS_A1.csv라면 다음과 같습니다.
- 분기형 관망에서
- 둘레 방향 균열 누수가 발생했고
- 배경 유량은 0.18L/s이며
- 가속도계 A1로 측정한 데이터입니다.
