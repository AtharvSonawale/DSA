# Search the Index of given Number

```
int search(vector<int>& arr, int x) {
        for (int i = 0; i < arr.size(); i++) {
            // If the element is found, return the index
            if (arr[i] == x) {
                return i;
            }
        }
        // If the element is not found, return -1
        return -1;
    }
```