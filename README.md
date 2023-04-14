# Epoch Time in C

This C program demonstrates how to obtain the epoch time using the `time()` function.

## Code

```c
#include <stdio.h>
#include <time.h>

int main() {
    time_t epoch_time;

    epoch_time = time(NULL);

    printf("Epoch time: %ld\n", epoch_time);

    return 0;
}
