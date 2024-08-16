# libft_42

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Libft - 42 Project</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
        }
        h1, h2, h3 {
            color: #333;
        }
        code, pre {
            background: #f4f4f4;
            padding: 5px;
            border-radius: 5px;
        }
        pre {
            padding: 10px;
        }
    </style>
</head>
<body>
    <h1>Libft</h1>
    <img src="https://badgen.net/badge/BornToCode/42/green" alt="42 Badge">

    <h2>Description</h2>
    <p>The <strong>Libft</strong> project is one of the foundational projects at 42. It involves creating a library of essential C functions, which will be reused in future projects. The goal is to understand how standard C functions are implemented while gaining a deeper understanding of pointers, memory allocation, and data structures.</p>

    <h2>Table of Contents</h2>
    <ul>
        <li><a href="#introduction">Introduction</a></li>
        <li><a href="#project-structure">Project Structure</a></li>
        <li><a href="#functions-implemented">Functions Implemented</a></li>
        <li><a href="#usage">Usage</a></li>
        <li><a href="#compilation">Compilation</a></li>
        <li><a href="#project-status">Project Status</a></li>
        <li><a href="#contributors">Contributors</a></li>
    </ul>

    <h2 id="introduction">Introduction</h2>
    <p>Libft is the very first project in the 42 curriculum. The objective is to rewrite some of the standard C library functions and implement additional utility functions that will be useful in further projects. Through this project, we learn how the standard library works behind the scenes and build a reusable code base for future challenges.</p>

    <h2 id="project-structure">Project Structure</h2>
    <pre>
├── Makefile
├── libft.h
├── src/
│   ├── ft_memset.c
│   ├── ft_bzero.c
│   ├── ft_memcpy.c
│   ├── ... (other function implementations)
├── bonus/
│   ├── ft_lstnew.c
│   ├── ft_lstadd_front.c
│   ├── ... (other bonus functions)
├── obj/
└── libft.a
    </pre>
    <p>The structure is organized as follows:</p>
    <ul>
        <li><code>src/</code> contains the main functions required for the project.</li>
        <li><code>bonus/</code> includes linked list functions needed to complete the bonus part of the project.</li>
        <li><code>libft.a</code> is the compiled library.</li>
    </ul>

    <h2 id="functions-implemented">Functions Implemented</h2>
    <h3>Part 1 - Libc Functions</h3>
    <ul>
        <li>ft_memset</li>
        <li>ft_bzero</li>
        <li>ft_memcpy</li>
        <li>ft_memmove</li>
        <li>ft_strlcpy</li>
        <li>ft_strlcat</li>
        <li>ft_toupper</li>
        <li>ft_tolower</li>
        <li>ft_atoi</li>
        <li>ft_isalpha</li>
        <li>ft_isdigit</li>
        <li>ft_isalnum</li>
        <li>ft_isascii</li>
        <li>ft_isprint</li>
        <li>ft_strlen</li>
        <li>ft_strdup</li>
        <li>ft_strchr</li>
        <li>ft_strrchr</li>
        <li>ft_strncmp</li>
        <li>ft_memchr</li>
        <li>ft_memcmp</li>
        <li>ft_strnstr</li>
        <li>ft_calloc</li>
        <li>ft_substr</li>
        <li>ft_strjoin</li>
        <li>ft_strtrim</li>
        <li>ft_split</li>
        <li>ft_itoa</li>
        <li>ft_strmapi</li>
        <li>ft_striteri</li>
        <li>ft_putchar_fd</li>
        <li>ft_putstr_fd</li>
        <li>ft_putendl_fd</li>
        <li>ft_putnbr_fd</li>
    </ul>

    <h3>Part 2 - Bonus Functions (Linked List)</h3>
    <ul>
        <li>ft_lstnew</li>
        <li>ft_lstadd_front</li>
        <li>ft_lstsize</li>
        <li>ft_lstlast</li>
        <li>ft_lstadd_back</li>
        <li>ft_lstdelone</li>
        <li>ft_lstclear</li>
        <li>ft_lstiter</li>
        <li>ft_lstmap</li>
    </ul>

    <h2 id="usage">Usage</h2>
    <p>To use the library in your project, include <code>libft.h</code> and compile with the <code>libft.a</code> library.</p>
    <pre>
#include "libft.h"

int main() {
    char *str = ft_strdup("Hello, 42!");
    ft_putendl_fd(str, 1);
    free(str);
    return 0;
}
    </pre>

    <h2 id="compilation">Compilation</h2>
    <p>You can compile the library by running:</p>
    <pre>make</pre>
    <p>To clean object files:</p>
    <pre>make clean</pre>
    <p>To remove all generated files:</p>
    <pre>make fclean</pre>
    <p>To recompile from scratch:</p>
    <pre>make re</pre>

    <h2 id="project-status">Project Status</h2>
    <ul>
        <li>[x] Part 1 Completed</li>
        <li>[x] Bonus Completed</li>
    </ul>

    <h2 id="contributors">Contributors</h2>
    <p>This project was developed by:</p>
    <ul>
        <li><a href="https://github.com/yourusername">Your Name</a></li>
    </ul>

    <hr>

    <h2>HTML Form Example</h2>
    <pre>
<form action="https://example.com/submit" method="POST">
    <label for="name">Name:</label><br>
    <input type="text" id="name" name="name" placeholder="Enter your name"><br><br>

    <label for="email">Email:</label><br>
    <input type="email" id="email" name="email" placeholder="Enter your email"><br><br>

    <label for="message">Message:</label><br>
    <textarea id="message" name="message" rows="4" cols="50" placeholder="Your message here"></textarea><br><br>

    <input type="submit" value="Submit">
</form>
    </pre>
</body>
</html>
