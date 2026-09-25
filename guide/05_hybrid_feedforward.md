# 05. Feed-forward Hybrid Metrology

## Core Concept

하이브리드 계측의 핵심은 두 장비의 hardware를 단순히 한 시스템으로 합치는 것이 아니다.

독립적인 X-ray measurement에서 얻은 structural information을 SE inverse model에 **feed-forward**하는 데이터 결합 방식이다.

## Workflow

```text
X-ray measurement
        ↓
Independent structure information
        ↓
Fixed / constrained parameters
        ↓
SE inverse model
        ↓
Fewer floating variables
        ↓
Reduced correlation
        ↓
More physically interpretable solution
```

## Fixed vs Floating

Floating parameter:
모델이 fitting 과정에서 자유롭게 조정하는 변수.

Fixed parameter:
독립적인 외부 측정으로 정해져 fitting 과정에서 임의로 바뀌지 않는 변수.

X-ray data를 이용해 일부 parameter를 fixed로 바꾸면 SE가 동시에 찾아야 하는 unknown의 수가 줄어든다.

## Why This Helps

parameter space의 자유도가 줄어들면, thickness와 optical properties가 서로 보상하며 같은 optical signal을 만드는 correlation이 줄어들 수 있다.

따라서 hybrid metrology의 목적은 단순히 MSE를 더 낮추는 것이 아니라 **physically plausible unique solution에 가까워지도록 inverse problem을 constrain하는 것**으로 정리했다.
