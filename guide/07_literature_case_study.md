# 07. Literature Case Study

## Why This Example Was Used

최종 발표에서는 2025 Journal of Applied Physics의 hybrid metrology 연구를 사용해 fixed-constraint concept의 효과를 정량적으로 설명했다.

이 논문은 High-k ALD film 자체를 직접 측정한 우리의 실험이 아니라, **optical + X-ray hybrid modeling에서 independent constraint가 inverse solution에 미치는 영향을 보여주는 supporting case study**로 사용됐다.

## Values Used in the Presentation

| Model | Floating variables | MSE | Extracted cavity | STEM reference |
|---|---:|---:|---:|---:|
| 11-parameter optical model | 11 | 0.163084 | 11.4 nm | 15.11 nm |
| 9-parameter hybrid model | 9 | 0.428461 | 14.09 nm | 15.11 nm |

## Interpretation

11-variable model:
- lower MSE
- but extracted value farther from STEM physical reference

9-variable constrained model:
- higher MSE
- but extracted value closer to STEM reference

따라서 모델 적합도 수치 하나만 최적화하면 physically wrong solution을 선택할 수 있다는 점을 설명하는 사례로 활용했다.

## Important Scope Note

이 수치는 우리 팀이 직접 측정한 값이 아니다.

또한 이 case study의 sample structure와 High-k ALD gate dielectric은 동일한 시스템이 아니므로, 숫자 자체를 High-k film의 expected performance로 전이하지 않는다.
