# Hik-Model
ChatGPT API의 Prompt Engineering을 통해 어체 번역 기능, 어체 학습 기능 총 2가지에 활용

#### 1) 어체 번역 기능
- university, school, online-transaction, online-chatting, general 총 5가지 location에 대해 prompt를 구성함.
- 입력받은 location이 unviersity, school, online인 경우 각 prompt를 호출하고 그 외 location의 경우 general prompt를 통해 어체 번역을 제공함.
- prompt의 경우 system과 prompt 2가지 부분으로 나누어 system에서는 수행해야 하는 일, few-shot learning 예시 등을 담고 있으며 prompt에서는 수행하라는 것에 대한 설명을 담고 있음.

#### 2) 어체 학습 기능
- 어체가 번역된 이유에 대한 설명을 출력하는 prompt를 구성함.
- 단순한 번역 이유가 아닌 input 필터값(location, listener, intimacy)와 번역에 쓰인 filter값과의 차이점을 통해 번역이 된 이유에 대해서 설명함.
