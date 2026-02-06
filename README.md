# GET_NEXT_LINE

42 School project aimed at creating a function that reads a file description line by line.

Following the [42 norm](https://github.com/42school/norminette)

## Skills developed
- Advanced memory management
- Single and multiple file handling
- Pointers

## How to run
```make```
OR to manage multiple file descriptors at the same time
```make bonus```

### Using it in another C project
```C
#include "get_next_line.h"
int main(void)
{
	int fd = open("file.txt", O_RDONLY);
	char *line = get_next_line(fd);
} ```
