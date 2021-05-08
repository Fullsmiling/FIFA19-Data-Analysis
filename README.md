# FIFA19-Data-Analysis

## KQ
"왼손잡이가 공부를 잘한다는 속설처럼 왼발잡이는 축구를 잘할까?"

- 문제 정의: 왼발잡이 선수가 오른발잡이 선수보다 축그를 잘하는지 확인해보고 싶다.
- 검증 방식: 구단 가치 상위 10개 팀에서 왼발잡이와 오른발잡이 급여의 차이 확인.

#### 활용 데이터

|칼럼명 | 의미 | 예시 |
|- | - | - |
|Name | 이름 | L.Messi |
|Age | 나이 | 31 |
|Nationality | 국적 | Argentina |
|Overall | 현재 선수의 종합 능력치 | 94 |
|Potential | 선수의 잠재적 능력치 | 94 |
|Club | 소속 구단 | FC Barcelona |
|Value | 선수 가치 (단위 : €유로) | 110000000 |
|Wage | 급여 (단위 : €유로) | 565000 |
|Preferred Foot | 선호하는 발 | Left |
|Position | 포지션 | RF |

*출처 : https://www.kaggle.com/karangadiya/fifa19*

---

## 데이터 분석 결과를 통해 도출한 결론

#### 데이터 분석 결과
 1. 왼발잡이의 평균 급여는 108717.65(유로) (소수점 3번째 자리에서 반올림)
 2. 오른발잡이의 평균 급여는 99517.39(유로) (소수점 3번째 자리에서 반올림)
 3. 왼발잡이 선수가 오른발잡이 선수에 비해 급여가 소폭 높음을 확인
 
#### 결론

1. 분석 결과 왼발잡이 선수가 오른발잡이 선수에 비해 급여가 소폭 높은 것을 확인했으나 위 결과만을 보고 왼발잡이 선수가 축구를 더 잘한다고 단정 짓는다면 위험할 것 같다.
2. 축구선수에 대한 기본 지식이 부족한 상황에서 검증 방식을 결정하고 결과를 도출해냈기 때문에 분석에 대한 결론에 신뢰도가 떨어지는 것을 느낀다.
3. 제대로 된 문제 해결을 위해서는 분석하고자 하는 분야에 대한 도메인 지식을 충분히 쌓아 탄탄한 논리를 기반으로 데이터 분석을 진행해야 할 것 같다.
