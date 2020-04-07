### ** Multiplecation Table using `cout` and `<<`

![Image description](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fk.kakaocdn.net%2Fdn%2FGSl6m%2FbtqCioLyghu%2FzjNe9EGq056oP7vwwu448K%2Fimg.png)

### **Code:**

``` cpp
#include<iostream>
using namespace std;
 
int main() {
    int i, j;
    
    for(i=1; i<10; i++){
        for(j=1; j<10; j++) {
            cout << j << "x" << i << "=" << j*i << '\t';
            if(j==9) // 9단 출력 후 줄바꿈. 
                cout << endl;
        }
    }
    return 0;
}
```
