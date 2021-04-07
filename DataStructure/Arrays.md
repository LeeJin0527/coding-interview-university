
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

*** 마크다운 너무 귀찮당
