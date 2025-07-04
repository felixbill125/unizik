```c
#include <stdio.h>

int main() {
    int arr[10]; // Create an array with 10 elements
    int i;

    // Ask the user to enter 10 integers
    printf(&quot;Please enter 10 integers:\n&quot;);
    for(i = 0; i < 10; i++) {
        printf(&quot;Number %d: &quot;, i + 1);
        scanf(&quot;%d&quot;, &arr[i]);
    }

    // Display the entered numbers
    printf(&quot;\nYou entered:\n&quot;);
    for(i = 0; i < 10; i++) {
        printf(&quot;%d &quot;, arr[i]);
    }
    printf(&quot;\n&quot;);

    return 0;
}
```
