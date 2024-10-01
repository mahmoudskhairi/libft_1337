<!-- HTML for the header and a brief introduction -->
<header>
    <h1>42 Libft Project Repository</h1>
    <p>A custom C library designed for the 42 School curriculum. This project is the foundation for understanding the inner workings of standard C library functions.</p>
</header>

<!-- HTML for the image (replace with an actual path or URL) -->
<img src="library.jpg" alt="Libft Logo" style="max-width: 100%; height: auto;">

---

## Overview

The **Libft** project is an essential part of the 42 curriculum. It involves re-implementing standard C library functions from scratch to deepen understanding of memory handling, pointers, and low-level programming concepts.

Libft is a collection of custom-built functions that mimics a subset of the standard C library (`libc`), as well as additional utilities.

### Why Libft?

Libft helps developers:
- Understand fundamental C concepts, including memory management, string manipulation, and linked lists.
- Gain familiarity with common functions such as `strcpy`, `memset`, `atoi`, etc.
- Build a strong foundation for future 42 projects and personal development.

---

## Features

- **Standard C Library Functions**: Custom implementations of functions such as:
  - `ft_memcpy`
  - `ft_bzero`
  - `ft_strlen`
  - `ft_strchr`
  - `ft_atoi`

- **Additional Functions**:
  - Linked list manipulation functions like `ft_lstnew` and `ft_lstdelone`.
  - Memory allocation helpers such as `ft_calloc`.
  - String utilities like `ft_split` and `ft_strjoin`.

---

## Project Structure

Here's the structure of the repository:

```bash
libft/
├── srcs/              # Source files of the custom library
├── includes/          # Header files (libft.h)
├── Makefile           # Script to compile the library
└── README.md          # This documentation file
