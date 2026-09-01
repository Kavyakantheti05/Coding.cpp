# DOREWARD - Rating 395

![Difficulty](https://img.shields.io/badge/Difficulty-Easy-green)

## Problem

_Description not available._

## Solution

**Language:** c_cpp  
**Runtime:** N/A  
**Memory:** N/A  
**Submitted:** 2026-09-01T15:24:25.764Z  

```c_cpp
#include <bits/stdc++.h>
using namespace std;

int main() {
	int t, x, y;
    cin >> t;
    while (t--) {
        cin >> x >> y;
        if (y <= 5 * x)
            cout << "Yes" << endl;
        else
            cout << "No" << endl;
    }
    return 0;

}

```

---

[View on CodeChef](https://www.codechef.com/problems/DOREWARD)