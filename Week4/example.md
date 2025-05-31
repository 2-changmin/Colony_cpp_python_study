## 1️⃣ 문자열

  ```python
  # 문자열 길이와 문자 접근
  text = "Colony"
  print(f"길이: {len(text)}")
  print(f"첫 글자: {text[0]}, 마지막 글자: {text[-1]}")

  # 문자열 반복 처리
  for ch in text:
      print(ch)

  # 문자열 치환 및 탐색
  print(text.replace("o", "0"))
  print("lo" in text)
```
```python
#include <iostream>
#include <string>
using namespace std;

int main() {
    string text = "Colony";
    cout << "길이: " << text.length() << endl;
    cout << "첫 글자: " << text[0] << ", 마지막 글자: " << text[text.length() - 1] << endl;

    // 문자열 반복 처리
    for (char ch : text) {
        cout << ch << endl;
    }

    // 문자열 치환 (replace는 substr과 조합하거나 직접 구현 필요)
    size_t pos = text.find("o");
    if (pos != string::npos) {
        text.replace(pos, 1, "0");
    }
    cout << text << endl;
}
```
## 2️⃣ 반복문 심화
```python
# 1부터 n까지의 누적 합
n = 10
total = 0
for i in range(1, n + 1):
    total += i
print(f"누적 합: {total}")

# 리스트에서 최대값 찾기
arr = [3, 9, 1, 7, 5]
max_val = arr[0]
for num in arr:
    if num > max_val:
        max_val = num
print(f"최댓값: {max_val}")
```
```python
#include <iostream>
#include <vector>
using namespace std;

int main() {
    int n = 10, total = 0;
    for (int i = 1; i <= n; i++) {
        total += i;
    }
    cout << "누적 합: " << total << endl;

    vector<int> arr = {3, 9, 1, 7, 5};
    int max_val = arr[0];
    for (int num : arr) {
        if (num > max_val) {
            max_val = num;
        }
    }
    cout << "최댓값: " << max_val << endl;
}
```


