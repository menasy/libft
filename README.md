<h1 align="center">Libft</h1>
<div align="center">
  <a href="https://github.com/menasy/libft" target="_blank">
    <img src="https://github.com/menasy/Project_icons/blob/main/badges/libftm.png" alt="Libft Badge">
  </a>
</div>

Libft is a C library project included in the 42 schools curriculum. This project aims to create your own library that contains a collection of functions that make basic functionalities in C easier and more useful. It will serve as a helpful tool throughout your training.

## Project Details

- **Program Name:** libft.a
- **Files to Submit:** Makefile, libft.h, ft_*.c
- **Makefile Rules:** NAME, all, clean, fclean, re
- **External Functions:** malloc, free, write

## Sections

### 1. Libc Functions

You need to rewrite a set of functions from libc. The functions you write should have the same prototypes and behave in the same way as their original versions. They must adhere to the definitions in the man pages of the original functions. Your functions will start with the 'ft_' prefix.

### 2. Additional Functions

In this section, you will develop functions that are not part of libc or are different from libc’s existing functions. Some examples include:

- **ft_substr:** Creates a substring from a given string.
- **ft_strjoin:** Concatenates two strings.
- **ft_strtrim:** Trims specific characters from a string.
- **ft_split:** Splits a string based on a specified character.
- **ft_itoa:** Converts an integer to a string.
- **ft_strmapi:** Transforms a string using a function.
- **ft_striteri:** Transforms a string iteratively using a function.
- **ft_putchar_fd:** Writes a character to a specific file descriptor.
- **ft_putstr_fd:** Writes a string to a specific file descriptor.
- **ft_putendl_fd:** Writes a string followed by a newline character to a specific file descriptor.
- **ft_putnbr_fd:** Writes an integer to a specific file descriptor.

### 3. Bonus Section

- ft_lstnew: Creates a new node.
- ft_lstadd_front: Adds a new node to the front of the list.
- ft_lstsize: Counts the number of nodes in a list.
- ft_lstlast: Returns the last node in a list.
- ft_lstadd_back: Adds a new node to the end of the list.
- The bonus section contains functions for manipulating lists. You should use the `t_list` structure to represent a node in your list.

```c
typedef struct s_list
{
    void *content;
    struct s_list *next;
} t_list;
```

## Installation Instructions

Clone the project to your local machine:

```bash
git clone https://github.com/menasy/libft
cd libft
```

## Build The Library
```bash
make
```

