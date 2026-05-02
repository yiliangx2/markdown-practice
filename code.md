可以用 ``` 包裹一段代码，并指定一种语言（也可以不指定）
```c++
int power(int a,int n) {
    int ans = 1;
    while (n) {
        if (n % 2) ans = ans * a;
        a = a * a;
        n = n / 2;
    }
    return ans;
}
```
