## 1️⃣ 다중 반복문

  ```python
  # 구구단 출력 (2단~4단)
  for i in range(2, 5):
      for j in range(1, 10):
          print(f"{i} x {j} = {i * j}")
      print()
  ```
  ```python
  #include <iostream>
  using namespace std;

  int main() {
      for (int i = 2; i <= 4; i++) {
          for (int j = 1; j <= 9; j++) {
              cout << i << " x " << j << " = " << (i * j) << endl;
          }
          cout << endl;
      }
  }
  ```

## 2️⃣ 2차원 배열

  ```python
  # 3x3 이차원 배열 생성 및 출력
  arr = [
      [1, 2, 3],
      [4, 5, 6],
      [7, 8, 9]
  ]

  for row in arr:
      for elem in row:
          print(elem, end=' ')
      print()

  # 값 변경 예시
  arr[0][0] = 0
  print("변경 후:", arr[0][0])
  ```
  ```python
  #include <iostream>
  using namespace std;

  int main() {
      int arr[3][3] = {
          {1, 2, 3},
          {4, 5, 6},
          {7, 8, 9}
      };

      // 배열 출력
      for (int i = 0; i < 3; i++) {
          for (int j = 0; j < 3; j++) {
              cout << arr[i][j] << " ";
          }
          cout << endl;
      }

      // 값 변경 예시
      arr[0][0] = 0;
      cout << "변경 후: " << arr[0][0] << endl;
  }
  ```


 
