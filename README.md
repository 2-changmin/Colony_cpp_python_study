# Colony Club: C++ & Python Study

## 📌 Study Overview
- **Platform:** [Codetree](https://www.codetree.ai/ko/trail-info)  
- **Duration:** 5 weeks  
  - **Dates:** 3/31, 4/7, 5/12, 5/19, 5/26  
- **Time Schedule:**  
  - 🐍 **Python:** 18:30 ~ 19:30  
  - 💻 **C++:** 20:00 ~ 21:00  
- **Educators:** Lee Chang Min, Yoon Seung Hee  

---

## 🏁 Week 1: Getting Started

### ✅ Setup
- [x] 코드트리 설치하기

### 📖 Chapter 1: Basics
- [x] 출력 입문
- [x] 변수
- [x] 기본 자료형
- [x] 연산자

### 📖 Chapter 2: Input & Output
- [x] 입출력
---
## 📝 Week 1 Study Notes

### 🖥️ 스터디 진행 방식
- **진행 방식:** Discord를 이용한 온라인 설명 + VSCode 예제 시연  
- **설명 방식:** 각 Chapter의 Lesson을 차례대로 설명하고, 실습 예제를 통해 개념 이해를 돕는 방식으로 진행  
- **학습 보조 자료:** VSCode를 활용하여 코드 예제 실시간 공유 및 실행  

### 🏗️ 학습 내용 요약

#### 1️⃣ 출력 입문
- `print()` 함수와 `cout`을 활용한 기본 출력 방법 익히기  
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
- 변수 선언 및 할당  
- 주요 자료형 (정수, 실수, 문자열, 불리언 등)  
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
- 산술, 비교, 논리 연산자 학습  
- 예제:
  ```python
  a, b = 10, 3
  print(a + b, a - b, a * b, a / b, a % b)

  int a = 10, b = 3;
  cout << (a + b) << " " << (a - b) << " " << (a * b) << " " << (a / b) << " " << (a % b) << endl;

#### 4️⃣ 입출력
- 사용자 입력 받기 및 출력 포맷 학습  
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

---
