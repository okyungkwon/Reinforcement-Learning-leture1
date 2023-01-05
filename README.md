## Leture 1: RL 수업소개
#### 강화학습(Reinforcement Learning): 환경(environment) 속에서 행동(act)할 때마다 상태가 업데이트되면서 최종적으로 보상(reward)을 얻는 학습을 말합니다.
<img width="533" alt="스크린샷 2023-01-06 오전 1 05 11" src="https://user-images.githubusercontent.com/121830114/210825981-cafab67a-9262-45a2-b518-976930e26b65.png"> 
강화학습 응용 예시: 알파고, 구글 데이터 센터 에너지 전력 절약, 로봇 관절 움직임, 사용자에게 광고와 콘텐츠를 보여주는 알고리즘

## Leture 2: OpenAI GYM game
#### 강화학습에는 에이전트와 환경이 있습니다. 에이전트는 어떤 행동을 하고 에이전트가 행동을 할 때마다 환경 속에서의 상태는 바뀌게 됩니다. 강화학습을 하기 위해선 에이전트와 환경이 있어야 합니다. 이때 환경은 OpenAI GYM에서 제공하는 환경을 사용해 볼 예정입니다.
<img width="810" alt="스크린샷 2023-01-06 오전 1 33 04" src="https://user-images.githubusercontent.com/121830114/210832468-6e8d3ed9-4310-497c-b30e-f7907b07a04b.png">
OpenAI GYM: 강화학습 환경을 만들어주는 프레임 워크</br> 실습: OpenAI GYM에서 제공하는 환경인 Frozen Lake
<img width="863" alt="스크린샷 2023-01-06 오전 1 32 30" src="https://user-images.githubusercontent.com/121830114/210834509-d537bee9-6024-4e11-89c2-6f0e11e1bc6d.png">
S: 시작점, F: 얼은 면, H: 구멍 G: 목표지점</br>시작 지점에서 구멍에 빠지지 않고 목표 지점까지 도착해야하는 게임</br>
에이전트는 FrozenLake 안에서 상하좌우(action)로 움직일 수 있으며 에이전트가 액션을 취하면 환경은 그에 맞는 상태나 보상을 주게 됩니다.

## 실습: 게임과정
<img width="360" alt="스크린샷 2023-01-06 오전 1 29 50" src="https://user-images.githubusercontent.com/121830114/210835625-183ed34b-2773-4a9b-98d6-48b0969bd8cb.png">
<img width="256" alt="스크린샷 2023-01-06 오전 1 27 32" src="https://user-images.githubusercontent.com/121830114/210837145-3fb68564-472f-40da-b8a2-3f2d7c4c4117.png">
<img width="259" alt="스크린샷 2023-01-06 오전 1 27 53" src="https://user-images.githubusercontent.com/121830114/210837153-d0306522-2376-4efa-b3a0-a2137e18c139.png">
<img width="258" alt="스크린샷 2023-01-06 오전 1 29 08" src="https://user-images.githubusercontent.com/121830114/210837160-1f9f6a88-2dab-44b8-93fa-7950aea5774b.png">
