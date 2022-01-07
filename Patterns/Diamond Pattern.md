# Diamond pattern

```
  *
 ***
*****
 ***
  *
```

```cpp

#include<iostream>
using namespace std;
int main(){
	int n;
	cin>>n;
	int i=1;
	while(i<=n){
		int space=1;
		while(space<=n-i){
			cout<<" ";
			space=space+1;
		}
		int star=1;
		while(star<=(2*i-1)){
			cout<<"*";
			star=star+1;
		}
		cout<<endl;
		i=i+1;
	}
	int a=n-1;
	while(a>=1){
		int spaces=1;
		while(spaces<=(n-a)){
			cout<<" ";
			spaces=spaces+1;
		}
		int stars=1;
		while(stars<=(2*a-1)){
			cout<<"*";
			stars=stars+1;
		}
		cout<<endl;
		a=a-1;
	}
}
```
