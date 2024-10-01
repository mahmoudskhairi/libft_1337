<!-- HTML for the header and a brief introduction
<header>
    <h1>42 Libft Project Repository</h1>
    <p>A custom C library designed for the 42 School curriculum. This project is the foundation for understanding the inner workings of standard C library functions.</p>
</header>


<!-- ---

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
└── README.md          # This documentation file --> -->

<h1 align="center">42 Libft Project</h1>
<!-- HTML for the image (replace with an actual path or URL) -->
<img src="libft_image.webp" alt="Libft Logo" style="max-width: 100%; height: auto;">
<p align="center">
  <strong>A C standard library reimplementation for the 42 school curriculum.</strong>
</p>

<h2>Table of Contents</h2>
<ul>
  <li><a href="#project-overview">Project Overview</a></li>
  <li><a href="#key-features">Key Features</a></li>
  <li><a href="#installation">Installation</a></li>
  <li><a href="#usage">Usage</a></li>
  <li><a href="#functions">Function List</a></li>
  <li><a href="#contributing">Contributing</a></li>
  <li><a href="#license">License</a></li>
  <li><a href="#contact">Contact</a></li>
</ul>

<h2 id="project-overview">Project Overview</h2>
<p>
  The Libft project consists of recreating standard library functions from C (`libc`) as well as creating some custom utility functions. This project serves as a foundational stepping stone in the 42 curriculum, enhancing understanding of memory management, string manipulation, and data structures in C.
</p>

<h2 id="key-features">Key Features</h2>
<ul>
  <li>Complete reimplementation of commonly used `libc` functions.</li>
  <li>Additional utility functions provided for string manipulation, memory management, and more.</li>
  <li>Header file that defines the function prototypes and constants for easy integration.</li>
  <li>Testable functions to validate functionality and promote code correctness.</li>
</ul>

<h2 id="installation">Installation</h2>
<p>To install the Libft project, follow these instructions:</p>
<pre>
<code>
# Clone the repository
git clone https://github.com/mahmoudskhairi/libft_42.git

# Navigate into the directory
cd 42-libft

# Compile the project
make
</code>
</pre>

<h2 id="usage">Usage</h2>
<p>To utilize the Libft functions in your C project, include the header file in your source code:</p>
<pre>
<code>
#include "libft.h"
</code>
</pre>

<p>After compilation, link with the `libft.a` archive to use the functions.</p>

<h2 id="functions">Function List</h2>
<p>Below is a list of some of the key functions implemented in Libft:</p>
<ul>
  <li><code>ft_strlen</code> - Computes the length of a string.</li>
  <li><code>ft_strcpy</code> - Copies a string to another buffer.</li>
  <li><code>ft_strcmp</code> - Compares two strings.</li>
  <li><code>ft_memset</code> - Fills a block of memory with a specified value.</li>
  <li><code>ft_memcpy</code> - Copies memory from one area to another.</li>
  <li><code>ft_strdup</code> - Duplicates a string.</li>
  <li><code>ft_atoi</code> - Converts a string to an integer.</li>
  <li><code>ft_lstnew</code> - Creates a new list element for linked lists.</li>
  <li><code>ft_lstadd_back</code> - Adds an element to the end of a linked list.</li>
  <li>... and many more!</li>
</ul>

<h2 id="contributing">Contributing</h2>
<p>Contributions are welcome! If you’d like to help improve this library, please take the following steps:</p>
<ul>
  <li>Fork the repository.</li>
  <li>Create a new branch for your feature or fix.</li>
  <li>Make your changes and commit them.</li>
  <li>Push your branch to your fork.</li>
  <li>Submit a pull request to the main repository.</li>
</ul>

<h2 id="contact">Contact</h2>
<p>For any questions, feedback, or issues, feel free to reach out:</p>
<ul>
  <li>Email: <a href="mailto:mahmoud.skhairi@gmail.com">mahmoud.skhairi@gmail.com</a></li>
  <li>LinkedIn: <a href="https://www.linkedin.com/in/mahmoud-skhairi" target="_blank">mahmoud skhairi</a></li>
</ul>

<h2>Happy Coding!</h2>
