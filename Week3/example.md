## 1️⃣ 조건문 심화

  ```python
  score = 85
  if score >= 90:
      print("A학점")
  elif score >= 80:
      print("B학점")
  else:
      print("C학점")
```
```python
#include <iostream>
using namespace std;

int main() {
    int score = 85;
    if (score >= 90) {
        cout << "A학점" << endl;
    } else if (score >= 80) {
        cout << "B학점" << endl;
    } else {
        cout << "C학점" << endl;
    }
    return 0;
}
```

## 2️⃣ 배열 기초

  ```python
numbers = [10, 20, 30, 40]
numbers.append(50)
for num in numbers:
    print(num)
```
```python
#include <iostream>
#include <vector>
using namespace std;

int main() {
    vector<int> numbers = {10, 20, 30, 40};
    numbers.push_back(50);
    for (int num : numbers) {
        cout << num << endl;
    }
    return 0;
}
```
