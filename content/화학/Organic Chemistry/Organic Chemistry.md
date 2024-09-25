## 1 Hydrocarbon

### 1.1 Strain
#### 1.1.1 Alkane
- 단일 결합으로 서로 연결된 탄소 원자의 사슬이다. 
- 각 탄소 원자가 4개의 결합을 형성하도록 수소가 결합한다.
- 따라서 alkane의 일반식은 $\mathrm{C_{n}H_{2n+2}}$이다.
- 탄소 사슬에서 탄소의 개수가 많을수록 연소했을 때 많은 에너지를 방출한다.
- methane에서는 탄소 원자의 $\mathrm{sp^{3}}$ hybrid orbital이 수소의 1s orbital과 겹치며 4개의 $\sigma$ 결합이 형성된다.
	-> 회전 가능하다
#### 1.1.2 Alkene
```smiles
C=C
```
$\pi$ orbital의 겹침으로 이루어진 이중 결합을 형성하고 있어 친핵성 반응이 일어나기 쉽다.
#### 1.1.3 Alkyne
### 1.2 Cyclic
고리 구조를 형성하기 때문에 angle strain이 발생한다.
#### 1.2.1 Alkane
Cycloalkane은 탄화수소 사슬의 두 탄소가 연결되어 닫힌 고리가 생긴 구조이다.
alkane에서 2개의 수소를 제거하고 탄소간 결합을 형성하기 때문에 불포화도가 2이며 일반식은 $\mathrm{C_{n}H_{2n}}$이다.
cyclohexane은 boat와 chair 형으로 나뉘며 boat 형일 때에는 steric strain이 발생한다.



#### 1.2.2 Alkene

#### 1.2.3 Alkyne
### 1.3 Degree of Unsaturation
Index of hydrogen deffiency(IHD)라고도 불리며 탄화수소가 갖는 수소의 개수가 alkane에 비해 얼마나 적은 지를 나타낸다.
수소의 수를 H, 질소의 수는 N, 할로젠의 수를 X라고 할 때 다음과 같이 표기할 수 있다. 질소의 경우 탄소 원자와 단일 결합 했을 때 2개의 결합을 형성할 수 있기 때문에 더해준다.
$$
\mathrm{IHD}=\frac{\mathrm{2C+2-H+N-X}}{2}
$$
결합 종류에 따른 불포화도는 다음과 같다.

| 결합   | 불포화도 |
| ---- | ---- |
| 이중결합 | 1    |
| 삼중결합 | 2    |
| 고리형  | 1    |
이를 통해 이성질체의 구조를 예측할 수 있다. 예를 들어, 아래와 같은 카페인 분자에서 불포화도는 $\frac{8 \times 2+2-10+4}{2}=6$이다.
```smiles
Cn1cnc2N(C)C(=O)N(C)C(=O)c12
```
따라서 가능한 조합은 (이중 결합 6개), (이중 결합 5개, 고리형 1개), (이중 결합 4개, 고리형 2개), (이중 결합 4개, 삼중 결합 1개), ... 등이 있다.


---
## 2 Partial Charge
### 2.1 Halides
R-X 형태의 화합물이다. 할로젠 원소의 전기음성도가 매우 커서 할로젠기가 이탈되기 쉽고, 반응성이 크다.
$$
\mathrm{CH_{3}Cl}
$$
methyl chloride에서 chlorine의 전기음성도가 크기 때문에 chlorine은 $\delta^{-}$, carbon은 $\delta^{+}$의 부분 전하를 띄며 친전자체이다.

---
## 3 Organic Reaction
### 3.1 Neucleophilic Substitution
친핵체가 친전자체 내의 작용기를 대체하는 반응

> Markovnikov's Rule
> 주변에 전자를 제공할 수 있는 작용기가 많이 연결된 탄소는 주변 탄소로 부터 전자를 끌어와 다른 탄소에 비해 비교적 안정한 carbocation을 형성할 수 있다.
>```reaction
CC(C)=C.Cl>>C[C+](C)C.[Cl-]
>```

**균일 분해**
```reaction
C#C.FF>>FC=[CH+].[F-]
```

```reaction
FC=[CH+].[F-]>>F/C=C/F
```
공유 결합을 하고 있는 분자의 경우 순간 쌍극자를 형성하여 반응한다.
#### 3.1.1 SN1

**유발 효과**
```reaction
C=C.F>>C[C+](C)C.[F-]
```
Markovnikov's rule에 의하여 hydrogen fluoride와 ethene의 반응에서 ethene의 2번 탄소가 hydrogen과 결합하여 tertiary butyl carbocation 중간체를 형성한다. 
```reaction
C[C+](C)C.[F-]>>CC(F)(C)C
```
이 때문에 생성물은 대부분 2-fluoro-2-methylpropane의 형태로 존재한다.

0차, 1차 탄소에서는 이러한 유발 효과가 거의 일어나지 않기 때문에 SN1 반응은 대부분 2차 또는 3차 탄소에서 일어난다.
##### 3.1.1.1 친핵성 치환 반응
```reaction
CC.Br>>C[CH2+].[Br-]
```

```reaction
C[CH2+].[Br-]>>CCBr
```
alkene은 비극성이지만 $\pi$ 결합이 가지는 $\delta^{-}$로 인해 친전자체와 반응한다.
##### 3.1.1.2 친전자성 치환 반응

##### 3.1.1.3 라디칼 치환 반응
$$
\begin{align}
& \mathrm{Cl_{2} \xrightarrow{h\nu} 2Cl \cdot} \\
\end{align}\tag{initiate}

$$
개시 단계에서 chlorine은 광분해되어 chlorine radical이 된다.
$$
\begin{align}
& \mathrm{CH_{4}+2Cl\cdot \longrightarrow \cdot CH_{3}+\cdot Cl+HCl} \\
& \mathrm{\cdot CH_{3}+Cl_{2} \longrightarrow CH_{3}Cl + Cl \cdot}
\end{align}\tag{propagation}
$$
전파 단계에서 chlorine radical은 methane과 반응하여 methyl radical과 hydrogen chloride를 형성한다. 반응성이 큰 methyl radical은 다시 chlorine과 반응하여 methyl chloride와 새로운 clorine radical을 형성한다.
#### 3.1.2 SN2

**발덴 반전**
```reaction
CCl.[N-]=O>>O=NC.[Cl-]
```
methyl chloride에서 clorine의 전기음성도가 상대적으로 크기 때문에 carbon은 $\delta^{+}$, chlorine은 $\delta^{-}$의 부분 전하를 띈다. nitrogen monoxide에서는 oxygen의 전기음성도가 크기 때문에 nitrogen이 $\delta^{+}$, oxygen이 $\delta^{-}$를 띈다. 이에 따라 nitrogen monoxide가 친핵체로 작용하여 carbon과 결합을 형성하게 된다. 결합 형성 과정에서 chlorine의 반대 방향으로 nitrogen monoxide가 접근하고, 반대편의 chlorine이 이탈기가 되면서 발덴 반전이 일어나 hydrogen이 뒤집힌다.
### 3.2 Addition
#### 3.2.1 Electrophilic Addition
**Phenol의 합성**
```reaction
c1ccccc1.CC=C>[H+]>c1ccccc1-C(C)(-[H])C
```
prop-1-ene의 $\pi$ 결합과 양성자가 친전자성 첨가 반응을 일으켜 Cumene을 형성한다.
```reaction
c1ccccc1-C(C)C.O=O>>C1=CC=C(C=C1)C(C)(-C)OO
```

```reaction
C1=CC=C(C=C1)C(C)(-C)OO.[H+]>>C1=CC=C(C=C1)C(C)(-C)O[OH2]
```
산성 용액에서 oxygen이 친핵체로 작용하여 $\mathrm{H+}$를 공격한다. 
```reaction
C1=CC=C(C=C1)C(C)(-C)O[OH2]>>C1=CC=C(C=C1)O[C+](C)(-C).O
```

```reaction
C1=CC=C(C=C1)O[C+](C)(-C).O>>C1=CC=C(C=C1)OC(C)(-C)(-[OH2+])
```

```reaction
C1=CC=C(C=C1)OC(C)(-C)(-[OH2+])>>C1=CC=C(C=C1)[O+]([H])C(C)(-C)(-O)
```
proton transfer
```reaction
C1=CC=C(C=C1)[O+]([H])C(C)(-C)(-O)>>C1=CC=C(C=C1)O.CC(=O)C.[H+]
```
phenol과 acetic acid가 생성되는 산 촉매 반응이다.

### 3.3 Elimination

#### 3.2.1 E1
**3차 알코올 탈수 반응**
```reaction
CC(C)(O)C>[OH3+]>CC(C)C[OH2+]
```
2-methy-2-propanol은 산과 반응하여 tert-butyloxonium ion을 형성한다. $\mathrm{OH^{-}}$는 잘 떨어지지 않는 이탈기인 데, 산성 용액에서 protonation되어 $\mathrm{H_{2}O^{+}}$를 형성하여 좋은 이탈기가 된다.
```reaction
CC(C)C[OH2+]>>C[C+](C)C.O
```
$\mathrm{H_{2}O}$가 이탈하여 tert-butylcarbocation 중간체를 형성한다.
```reaction
C[C+](C)C.O>>CC(C)=C.[OH3+]
```
마지막으로, $\beta$ 수소가 $\mathrm{H_{2}O}$(짝염기)와 반응하여 hydronium ion(산)이 재생된다. 즉, 산 촉매 반응이다.

$\mathrm{H_{2}O}$와 $\beta$ 수소 제거가 서로 다른 단계에서 일어나므로 1차 반응이다.

**<font color="#ff0000">Nitriation of Benzene</font>**
$\mathrm{HNO_{3}}$와 $\mathrm{H_{2}SO_{4}}$가 반응하여 
```reaction
C1=CC=CC=C1.N(=O)[O]>>C1=CCC(C=C1)(N(=O)O)[H]
```

```reaction
C1=CCC(C=C1)(N(=O)O)[H]>>C1=CC=CC=C1(N(=O)O)
```
#### 3.2.2 E2
**1차 알코올 탈수 반응**

![[Alchol_Dehydration.png]]
산성 용액에서 ethanol은 위와 같은 반응을 통해 ethane이 되며 이 과정에서 $\mathrm{H_{2}O}$가 빠져나온다.  또한 반응 중간체를 형성할 때 사용되었던 hydrogen ion이 다시 재생산되므로 hydrogen ion은 이 반응에서 산 촉매로서 작용한다.

$\mathrm{H_{2}O}$와 $\beta$ 수소 제거가 동시에 일어나기 때문에 2차 반응이다. 1차 알코올에서만 관찰되며 carbocation 중간체가 나타나지 않는다.

**Fisher Esterification**
![[Fischer_Esterification.png|400]]

