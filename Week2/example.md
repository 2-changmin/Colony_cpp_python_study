## 1️⃣ 조건문

- 예제:
  ```python
  temperature = 30

  if temperature > 35:
      print("너무 더워요!")
  elif temperature >= 20:
      print("날씨가 좋아요.")
  else:
      print("조금 쌀쌀해요.")


  #include <iostream>
  using namespace std;

  int main() {
      int temperature = 30;

      if (temperature > 35)
          cout << "너무 더워요!" << endl;
      else if (temperature >= 20)
          cout << "날씨가 좋아요." << endl;
      else
          cout << "조금 쌀쌀해요." << endl;

      return 0;
  }
  ```

## 2️⃣ 반복문

- 예제:
  ```python
  for i in range(5):
      print("Hello!", i)


  #include <iostream>
  using namespace std;

  int main() {
      for (int i = 0; i < 5; i++) {
          cout << "Hello! " << i << endl;
      }
  
      return 0;
  }
  ```

## 3️⃣ while문

- 예제:
  ```python
  count = 1
  while count <= 5:
      print("Count:", count)
      count += 1

  #include <iostream>
  using namespace std;

  int main() {
      int count = 1;
      while (count <= 5) {
          cout << "Count: " << count << endl;
          count++;
      }

      return 0;
  }
  ```
