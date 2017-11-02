# Binary Search

## Basic Implementation
```java

public static int binarySearch(int[] A, int target) {
  int left = 0; int right = A.length - 1;
        
  while (left <= right) {       
     int middle = (l+r)/2;
     
     if (A[middle] == target) return middle;
            
     if (target < A[m]) {
        right = middle - 1;
     }
            
     if (target > A[m]) {
        left = middle + 1;
     }
  }
        
   return -1;
}

```
