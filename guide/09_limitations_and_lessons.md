# 09. Limitations & Lessons

## 1. Literature-Based Project

본 프로젝트는 직접 측정 장비를 운용해 데이터를 생성한 실험 프로젝트가 아니다.

주요 결과는 논문·로드맵·장비 자료를 바탕으로 한 metrology problem analysis와 hybrid workflow proposal이다.

## 2. XRR and XRD Serve Different Roles

프로젝트는 XRR을 High-k density / roughness와 연결했고, 후반 quantitative case study에서는 XRD/XRF 기반 structural constraints가 사용된 논문을 활용했다.

따라서 “XRR-SE로 우리 팀이 14.09 nm를 측정했다”처럼 서로 다른 case를 합쳐 표현하면 안 된다.

## 3. Published Case Study ≠ High-k Experimental Proof

11-variable / 9-variable comparison은 hybrid constraint의 일반적 장점을 보여주는 supporting evidence다.

그 값을 ALD High-k film에서 직접 재현했다고 주장하지 않는다.

## 4. MSE Is Not Enough

가장 중요한 학습점은 inverse modeling에서 numerical fit quality만 보는 것이 위험하다는 점이다.

외부 physical constraint와 cross-validation이 함께 있어야 extracted parameter의 물리적 타당성을 판단할 수 있다.

## 5. Metrology as Process Feedback

이 프로젝트를 통해 공정 엔지니어링 관점에서 계측은 단순 characterization이 아니라 **ALD recipe와 interface control을 위한 feedback input**이라는 점을 연결했다.
