#include <iostream>

using namespace std;

void print_number(int n, int count) {
  for (int i = 0; i < count; i++) {
    cout << n << " ";
  }
}

int main() {
  int n;

  // دریافت عدد از کاربر
  cout << "یک عدد وارد کنید: ";
  cin >> n;

  // چاپ عدد به تعداد n بار
  print_number(n, n);

  return 0;
}
