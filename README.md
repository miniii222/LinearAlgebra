# LinearAlgebra

## 3Blue1Brown 채널 [link](https://www.youtube.com/channel/UCYO_jab_esuFRV4b17AJtAw)
시각화 너무 좋음...

### Chapter 2
#### span : The sapn of v and w is the set of all their linear combinations
- av + bw
##### 2D sapn(planes or lines)
- lines : 같은 선상에 있으려면, 두 벡터가 같은 방향일 때
![image](https://github.com/miniii222/LinearAlgebra/blob/master/span_2d.PNG "2d")
##### 3d span(planes)
- 세 벡터가 같은 평면(span)에 있으면, 세 번째 벡터 역시 추가되어도 같은 span
- 세 번쨰가 나머지 두 벡터의 span위에 있지 않으면, 세번째의 방향에 따라 첫번째, 두번째 span이 움직임
- 세 번째가 나머지 두 벡터의 span위에 있다. 즉, v와 w로 세번째 벡터 표현 가능. `(linearly dependent)`
![image](https://github.com/miniii222/LinearAlgebra/blob/master/span_3d.PNG '3d')

### Chapter 3 Linear Transformations
- The word `transformation` suggets that you think usin movement
- a.k.a function
- Grid lines remain parallel and evenly spced
- Lines remain lines
- Origin remains fixed


### Chapter 4 Matrix multiplication as composition
![image](https://github.com/miniii222/LinearAlgebra/blob/master/composition.PNG 'composition')
- 행렬곱은 결국, 여러 가지 선형변환의 결합
- M1M2 != M2M! 행렬곱은 교환법칙이 성립하지 않는데, 이 이유는 여러가지 변환이라 생각하면 쉽다


### Chapter 5 Three-dimensional linear transformations


### Chapter 6 The determinant
- `determinant` : 선형변환에 의한 영역의 변화를 나타내는 팩터 / 3차원에서는 부피로 생각 
- negative determinant는 orientation-flipping
- determinant = 0 : 부피 혹은 면적이 0이 된다는 것!(linearly dependent)

### Chapter 7 The determinant Inverse matrices, column space and null space
- Ax = v : A행렬을 이용하여 변환 후, v가 되는 벡터x가 있는지 찾아 보는 것
- A변환이 면적 혹은 공간을 아예 0으로 만드는 것이 아니라면( det(A)!=0 ), x벡터는 존재. (일대일대응)
- det(A)!=0 - > A inverse 존재
- 공간을 뭉게버리면(det(A) = 0) 다시 돌아갈 수 없다. A inverse 존재 x
- `Rank` : Number of dimensions in the output (n x n 행렬의 rank max = n)
- `Column Space` of A : Set of all possible outputs Av
- zero vector is always in the column space
- full rank이면, 원점으로 변환되는 경우는 원점뿐
- full rank가 아니라면, 평면이 통째로 원점으로 변환될 수 도 있음. 
- `null space` or `kernel` : 원점으로 이동되는 벡터들의 집합

### Chapter 8 Nonsquare matrices as transformations between dimensions



