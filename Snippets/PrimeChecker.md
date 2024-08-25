# Prime Checker

```
         if (N <= 1) return 0;

        for (int i = 2; i <= sqrt(N); i++) {
            if (N % i == 0) {
                cout<<N<<" is a Prime number";
            }
        }
        cout<<N<<" is not a Prime number";
```