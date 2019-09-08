# Deep Learning 

기존 Machine Learning 방법론으로는 풀 수 없는 문제를 풀기위한 방법 중 하나.

사실 Machine Learning의 분류 중 하나이다.

Machine Learning은 Label 의 형태에 따라 3가지로 분류한다.

1. Supervised Machine Learning

2. Unsupervised Machine Learning

3. Reinforcement Machine Learning

우리는 3번 강화학습을 채택하여 진행하도록 할 것이다.

# Reinforcement Machine Learning

정의 
---

Maching Learning의 한 부류이다.

어떠한 환경 속에서 정의된 에이전트가 현재의 상태를 인식하여, 선택가능한 행동 중 보상을 최대화 하는 행동 또는 행동들의 순서를 선택하는 방법이다.

자 여기서 중요한 키워드를 뽑아 내어 보면

1. 환경

2. 에이전트

3. 행동

4. 보상

5. 순서


정도로 뽑아낼 수 있는데 이는 후에 다시 이야기 하도록 하자.

특징
---

1. Trial and Error 
> 환경과의 상호작용에서 학습하여, 실제 시도를 통해 에러를 줄여나가는 방식이다.

2. Delayed Reward
> 시간의 개념을 도입하여, 미래지향적 행동에 대한 보상을 뒤늦게 올 수 있으므로, 어떤 행동이 좋은행동인지 판단하기 어렵다.


구성요소
---

강화학습은 기계학습 방법중 하나이다.

마치 인간이 걷는법을 배우듯

환경과 상호작용을 해나 가면서 배우는 것처럼 학습시키는 것.

이 때 이를 구성하는 요소들은 정의에 나와있듯이

환경, 에이전트, 상태, 행동, 보상, 정책 이다.
> environment, agent, state, action, reward, policy


발전 과정
---

1. Dynamic Programming

그렇다 dp이다. Optimal Control이라고 하는 비용함수의 최소화 이론을 바탕으로 강화학습을 진행한다.

2. Markov Decision Process

그렇다 결국 의사결정 나무인것이다.

이 두가지가 합쳐서 **강화학습**이 탄생하였다.

