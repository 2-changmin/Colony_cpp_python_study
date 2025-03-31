#### 1️⃣ 출력 입문

- 예제:
  ```python
  print("Hello, Python!")

  #include <iostream>
  using namespace std;
  int main() {
      cout << "Hello, C++!" << endl;
      return 0;
  }

#### 2️⃣ 변수와 기본 자료형

- 예제:
  ```python
  name = "Alice"
  age = 25
  print(f"이름: {name}, 나이: {age}")

  #include <iostream>
  using namespace std;

  int main() {
      string name = "Alice";
      int age = 25;
    
      cout << "이름: " << name << ", 나이: " << age << endl;
      return 0;
  }

#### 3️⃣ 연산자

- 예제:
  ```python
  a, b = 10, 3
  print(a + b, a - b, a * b, a / b, a % b)

  int a = 10, b = 3;
  cout << (a + b) << " " << (a - b) << " " << (a * b) << " " << (a / b) << " " << (a % b) << endl;

#### 4️⃣ 입출력

- 예제:
  ```python
  name = input("이름을 입력하세요: ")
  print(f"안녕하세요, {name}님!")

  #include <iostream>
  using namespace std;

  int main() {
      string name;
      cout << "이름을 입력하세요: ";
      cin >> name;
      cout << "안녕하세요, " << name << "님!" << endl;
      return 0;
  }
