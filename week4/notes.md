# Week 4: Pointers & Hexadecimal



Hexadecimal:

## Pointers


Everything in the memory has an address.
Pointer takes 8 bytes of memory. A pointer is an address.

A pointer is a data item whose value is a memory address. the type describes the data located at the memory address.

I finally understood the pointer explanation.



## Malloc


We use malloc to dynamically allocate memory. We must always use free() to free up the memory at the end of the program.
Never use free() for a statically allocated memory and do not use free() twice on a dynamically allocated memory.


## Call stacks

When a function is called it will pushed in the stack. When a function is executed it will be popped off of the stack.


## File Pointers



fopen(): for opening a file.

fgetc(): for reading a file.

fputc(): to writes or append a character in a file

fread(buffer, size, qty, file pointer): This one reads the quantity of units of size (s) from the file pointed to and stores them in memory in a buffer (usually an array) pointer to by <buffer>.
  
fwrite(buffer, size of(char), 1, pointer file): Helps us write into a pointer file.\
  
  
  
Other file pointer commands:
  
- fgets(): Reads a full string from a file.
- fputs(): writes a full string to a file.
- fprintf(): writes a formatted string to a file
- fseek(): allows you rewind or fast-forward within a file
- ftell(): tells you at what(byte) position you are at within a file.
- feof(): tells if I have read to the end of a file
- ferror(): indicates whether an error occured in working with a file.
  
  
  
  
  2022.12.04:
  
  Today I was solving the filter problem set. And I came accross a very interesting problem: Sobel Operator.
  
  
  It is used in image processing and computer vision, particularly within edge detection algortithms where it creates and image emphasising on edges.
  
  
  
  
  I also started workign on the recover  provblem set. Which is a problem in which I try to recover the JPEGs from a forensic image.
