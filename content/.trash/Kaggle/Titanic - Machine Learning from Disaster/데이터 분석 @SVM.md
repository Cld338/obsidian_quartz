---
svm: " "
---

## [Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic/overview)

## 0. 데이터 불러오기
### Train.csv
| PassengerId | Survived  | Pclass    | Name                                              | Sex    | Age  | SibSp              | Parch        | Ticket           | Fare    | Cabin     | Embarked |
| ----------- | --------- | --------- | ------------------------------------------------- | ------ | ---- | ------------------ | ------------ | ---------------- | ------- | --------- | -------- |
| PassengerId | 생존 여부 | 좌석 등급 | 이름                                              | 성별   | 나이 | 형제자매 및 배우자 | 부모 및 자식 | 티켓             | 운임료  | 객실 번호 | 승선지   |
| 1           | 0         | 3         | Braund, Mr. Owen Harris                           | male   | 22.0 | 1                  | 0            | A/5 21171        | 7.2500  | NaN       | S        |
| 2           | 1         | 1         | Cumings, Mrs. John Bradley (Florence Briggs Th... | female | 38.0 | 1                  | 0            | PC 17599         | 71.2833 | C85       | C        |
| 3           | 1         | 3         | Heikkinen, Miss. Laina                            | female | 26.0 | 0                  | 0            | STON/O2. 3101282 | 7.9250  | NaN       | S        |
| 4           | 1         | 1         | Futrelle, Mrs. Jacques Heath (Lily May Peel)      | female | 35.0 | 1                  | 0            | 113803           | 53.1000 | C123      | S        |
| 5           | 0         | 3         | Allen, Mr. William Henry                          | male   | 35.0 | 0                  | 0            | 373450           | 8.0500  | NaN       | S        |

## 1. 데이터 전처리
라벨에 따른 생존율을 비교해보며 적절한 라벨을 찾아야한다.
### 1) 티켓 등급
![[티켓 등급에 따른 생존율.png]]
### 2) 호칭
이름 자체로는 큰 의미가 없어 보여 호칭에 따른 생존율을 보았다. 일부 호칭에 대해서 매우 크거나 낮은 것으로 보아 분류에 꽤나 효과가 있어 보인다.
![[Pasted image 20231220014758.png]]

### 3) 성별
![[성별에 따른 생존율.png]]

### 4) 나이 다시 정리할 것
데이터의 개수가 적어 나이에 따라 분류하기 보다는 연령대 별로 분류해보았다.
![[Pasted image 20231220000506.png]]


### 5) 가족 수
![[Pasted image 20231220004903.png]]
### 6) 운임료
