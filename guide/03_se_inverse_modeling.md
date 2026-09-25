# 03. Spectroscopic Ellipsometry & Inverse Modeling

## What SE Measures

SE는 박막 두께를 직접 보는 장비가 아니다.

반사된 빛의 편광 변화인 Ψ와 Δ를 측정하고,

`ρ = tan(Ψ) · exp(iΔ)`

와 같은 optical response를 multilayer model과 비교해 구조·광학 파라미터를 역산한다.

## Inverse Modeling

1. virtual multilayer model 생성
2. model에서 예상 Ψ/Δ 계산
3. measured Ψ/Δ와 비교
4. MSE가 작아지도록 thickness, n, k, roughness 등을 반복 조정
5. 최적 parameter set 추정

## Why Ultrathin Films Are Difficult

박막이 매우 얇아지면 optical phase change가 작아지고 여러 parameter가 비슷한 신호를 만들 수 있다.

예를 들어:

- thickness 증가
- refractive index 증가
- roughness 변화

가 서로 유사한 optical response를 만들면, 하나의 낮은 MSE 영역 안에 여러 조합이 존재할 수 있다.

## Key Point

**Low MSE ≠ guaranteed physical truth**

본 프로젝트는 이 parameter correlation을 단일 SE의 가장 중요한 수학적 한계로 정리했다.
