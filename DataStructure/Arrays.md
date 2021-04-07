
## Arrays
### 목차 

- 배열
- 선형배열과 다차원 배열
- 배열 기본
- 다차원 배열
- 동적 배열 
- 가변 배열
- 배열과 리사이징 


****
Arrays are constant time to access 
<-> random access 

# 1. 배열의 address 구하는 방법 

- 기준 주소+ ( i- first_index(통상적으로 1임) ) * elem_size
 
1. 1차원 배열 address 
= array_addr(시작 주소) + elem_size * ( i - first_index)

2. 2차원 배열 address 
int Arr[i][j] (행우선)
= array_addr(시작 주소) + elem_size *(i-1) +(j-1) 

3.int Arr[i][j] (열우선)
= array_addr(시작 주소) + elem_size *(j-1) +(i-1) 


## 1.2. Times for Common Operations


| 항목 | Add | Remove |
|:---:|:----:|:----|
| Beginning | O(n) | O(n) |
| End |O(1)| O(1) |
| Middle |O(n) | O(n) |



<img src="https://user-images.githubusercontent.com/64263694/113883457-20ed3700-97f9-11eb-9c22-0cec69f694a5.jpg"  width="800" height="800">


<img src="https://user-images.githubusercontent.com/64263694/113883456-20ed3700-97f9-11eb-8ce5-cca9a224a1be.jpg"  width="800" height="800">

<img src="https://user-images.githubusercontent.com/64263694/113883454-2054a080-97f9-11eb-9351-4bd29524f6fa.jpg"  width="800" height="800">

<img src="https://user-images.githubusercontent.com/64263694/113883451-1fbc0a00-97f9-11eb-8a29-7bc537d16e13.jpg"  width="800" height="800">

<img src="https://user-images.githubusercontent.com/64263694/113883447-1f237380-97f9-11eb-857c-d94766e35163.jpg"  width="800" height="800">


<img src="https://user-images.githubusercontent.com/64263694/113883444-1f237380-97f9-11eb-8f38-ae2f7c4cca18.jpg"  width="800" height="800">

<img src="https://user-images.githubusercontent.com/64263694/113883442-1e8add00-97f9-11eb-97de-b4fbe772b880.jpg)"  width="800" height="800">

<img src="https://user-images.githubusercontent.com/64263694/113883439-1df24680-97f9-11eb-91f0-b673aadbac14.jpg"  width="800" height="800">


<img src="https://user-images.githubusercontent.com/64263694/113883438-1d59b000-97f9-11eb-9a45-a86d6a493bc7.jpg"  width="800" height="800">


<img src="https://user-images.githubusercontent.com/64263694/113883433-1d59b000-97f9-11eb-87a1-f55379175351.jpg"  width="800" height="800">


<img src="https://user-images.githubusercontent.com/64263694/113883426-1cc11980-97f9-11eb-9b12-b5a17dfc0342.jpg"  width="800" height="800">


<img src="https://user-images.githubusercontent.com/64263694/113883421-1b8fec80-97f9-11eb-98b2-efce5dff6494.jpg"  width="800" height="800">

<img src="https://user-images.githubusercontent.com/64263694/113883415-1af75600-97f9-11eb-807e-8b16a6113498.jpg"  width="800" height="800">
https://user-images.githubusercontent.com/64263694/113886649-d0c3a400-97fb-11eb-8004-152fa98a5365.jpg
