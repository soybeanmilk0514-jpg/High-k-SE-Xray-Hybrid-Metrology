# High-k Thin-Film Characterization with SE–X-ray Hybrid Metrology

**Presented at:** 2026년 7월 부산 아난티 · 반도체학술대회 차세대반도체학과 특별세션

## Overview

ALD 기반 High-k 초박막에서 단일 SE inverse modeling이 가지는 parameter-correlation 문제를 분석하고, X-ray-derived structural information을 fixed constraint로 feed-forward하는 hybrid metrology concept을 제안한 프로젝트입니다.

![Project flow](./figures/project-flow.svg)

## Main Problem

초박막에서는 thickness, refractive index, roughness가 서로 유사한 optical signal을 만들 수 있어 SE fitting의 unique solution이 약해질 수 있습니다.

## Proposed Strategy

1. XRR/X-ray 계측에서 independent structural information 확보
2. 해당 값을 SE model의 fixed / constrained parameter로 입력
3. floating-variable 수 감소
4. parameter correlation 감소
5. density / roughness / optical-property interpretation의 물리적 타당성 향상

## My Contribution

내 담당은 hybrid-metrology section으로, parameter-correlation ambiguity, X-ray fixed constraint, feed-forward modeling, floating-variable comparison, STEM-based literature validation, High-k application logic을 정리하고 발표했습니다.

## Published Case Study

The conference presentation used a published hybrid-metrology example:

| Model | Floating parameters | MSE | Extracted value | STEM |
|---|---:|---:|---:|---:|
| Unconstrained optical | 11 | 0.163084 | 11.4 nm | 15.11 nm |
| X-ray constrained hybrid | 9 | 0.428461 | 14.09 nm | 15.11 nm |

The values are literature evidence, not original team measurements.

## Documentation

See [Project Navigation](./guide/00_navigation.md) and [My Contribution](./guide/06_my_contribution.md).
