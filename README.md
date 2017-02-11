# Deep Reinforcement Learning Agents
 
이건 https://github.com/awjuliani/DeepRL-Agents 의 한글 버젼이다.

이 레포지토리는 텐서플로로 작성된 강화학습 알고리즘의 모음을 담고 있다. 

레포지토리가 현재 담고 있는 알고리즘은 다음과 같다 :

0. Q-Table - 확률적 환경 문제를 풀기 위해 표를 이용하는 Q-learning의 구현
1. Q-Network - Q-Table과 동일한 문제를 풀기위한 Q-Learning의 신경망 구현
2. Simple-Policy - n개 손잡이 슬롯머신 문제와 같은 상태없는(stateless) 환경에 대해 정책 그라디언트 방법의 구현
3. Contextual-Policy - Contextual bandit 문제와 같은 상태적(stateful) 환경에 대한 정책 그라디언트 방법의 구현
4. Policy-Network - 두가지 상반된 행동과 지연된 보상 상태를 갖는 완전한 강화학습 문제를 해결하기 위한 정책 그라디언트 에이전트의 신경망 구현
5. Model-Network - 환경을 모델링하는 분리된 신경망을 포함하는 정책 신경망
6. Double-Dueling-DQN - 안정적인 향상과 성능을 위해 Double DQN 과 Dueling DQN을 추가한 Deep-Q Network의 구현
7. Deep-recurrent-Q-Network - 부분 관찰가능한 강화학습 문제를 해결할 수 있는 Deep Recurrent Q-network의 구현
8. Q-Exploration - 탐험을 위한 행동 선택 전략을 포함하는 DQN 구현. 전략은 : greedy, random, e-greedy, Boltzmann, 과 Bayesian Dropout
9. A3C-Doom - A3C(Asynchronous Advantage Actor-Critic) 알고리즘의 구현. 정책을 종합적으로 향상시키기 위해 여러 에이저트를 사용함. 이 구현은 VizDoom 챌린지 같은 3D 환경에서 강화학습 문제를 해결할 수 있다.
