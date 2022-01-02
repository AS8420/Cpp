# Square Patterns


1. 
```
****
****
****
****
```

```cpp
#include<iostream>

using namespace std;

int main() {
  int n;
  cout << "Enter the number of rows:";
  cin >> n;
  int i = 1;
  while (i <= n) {
    int j = 1;
    while (j <= n) {
      cout << "*";
      j++;
    }
    cout << endl;
    i++;
  }
}
```

2. 
```
1111
2222
3333
4444
```

```cpp
#include<iostream>

using namespace std;

int main() {
  int n;
  cout << "Enter the number of rows:";
  cin >> n;
  int i = 1;
  while (i <= n) {
    int j = 1;
    while (j <= n) {
      cout <<i;  //Don't use "i" as it will at as a string and print i
      j++;
    }
    cout << endl;
    i++;
  }
}
```

3.
```
1234
1234
1234
1234
```

```cpp
#include<iostream>

using namespace std;

int main() {
  int n;
  cout << "Enter the number of rows:";
  cin >> n;
  int i = 1;
  while (i <= n) {
    int j = 1;
    while (j <= n) {
      cout <<j;  //Don't use "j" as it will at as a string and print j
      j++;
    }
    cout << endl;
    i++;
  }
}
```

4.
```
4321
4321
4321
4321
```

```cpp
#include<iostream>

using namespace std;

int main() {
  int n;
  cout << "Enter the number of rows:";
  cin >> n;
  int i = 1;
  while (i <= n) {
    int j = 1;
    while (j <= n) {
      cout <<n-j+1; 
      j++;
    }
    cout << endl;
    i++;
  }
}
```
