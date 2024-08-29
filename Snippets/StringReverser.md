# Reverse a String

```
class Solution
{
    public:
    string reverseWord(string str)
    {
        int n = str.length();
        string reversed = "";
        while(n>=0){
            reversed += str[n];
            n--;
        }
        return reversed;
    }
};
```