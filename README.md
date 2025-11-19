# DSA-STRIVER-2
### HASHING 
###### character hashinng 


### DSA
-ARRAYS -> https://github.com/Saujanya-rajvanshi/Striver
```cpp
#include<bits/stdc++.h>
using namespace std;

int main() {
string s;
cin >> s;

//pre compute
int hash [26] = {0};
for(int i = 0;i<s.size(); i++) {
    hash[s[i]]++;
}
int q;
cin >> q;
while(q -- ) {
    char c;
    cin >> c;
    // fetch 
    cout << hash [c] << endl ;
}
return 0;
}
```
