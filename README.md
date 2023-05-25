# LIBFT
Welcome to the LIBFT repository! This project is part of the curriculum at School 42, and it focuses on building your very own C library.

## Table of Contents
- [Introduction](#introduction)
- [Objective](#objective)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction

In this repository, you will find the LIBFT project, which is an essential milestone in your journey to becoming a proficient C programmer. The project's main goal is to build a library of useful C functions that you can reuse in future projects. The library covers a wide range of functionalities, from basic memory manipulation to more complex string parsing and linked list operations.

Feel free to explore the repository, dive into the code, and expand upon it to further improve your C programming skills.

## Objective

The objective of the LIBFT project is to strengthen your understanding of fundamental C programming concepts while familiarizing yourself with the standard library functions. By implementing your own versions of these functions, you'll gain a deeper understanding of how they work under the hood.

Moreover, the project aims to enhance your problem-solving skills, code organization, and algorithmic thinking. You'll encounter various challenges throughout the project, which will help you grow as a programmer.

## Features

- A wide range of standard library function implementations.
- Additional functions that are commonly used in C programming.
- Modular and well-organized code structure.
- Thoroughly tested functions to ensure reliability and correctness.
- Makefile for easy compilation and management.

## Technologies Used

- C programming language

## Installation

To use the LIBFT library in your own projects, follow these steps:

1. Clone the repository:
   ```shell
   git clone https://github.com/your-username/libft.git
Change to the project directory:

2. After cloning the repository, navigate to the project directory using the following command:

   ```shell
    cd libft

3. Compile the library:
   ```shell
      make

4. Link the library to your project:

   ```shell
    Copy libft.a to your project folder.
    
5. Include the library header files in your code:

    ```c
    #include "libft.h"

6. Compile your project with the library:

   ```shell
    gcc your_project.c -L. -lft -o your_project

Now you can use the functions from the LIBFT library in your project by including the appropriate header files and linking the library.

## Usage

To use a function from the LIBFT library, include the corresponding header file in your code and call the function as you would with any other standard library function.
 
    ```c
    #include "libft.h"

    int main(void) 
    {
      char *str;

      str = "Hello, LIBFT!";
      ft_putstr(str);
      return (0);
    }

## Contributing

Contributions to the LIBFT project are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request. Your contributions can help enhance the library and make it even more valuable for others.
Acknowledgments

This project was completed as part of the curriculum at School 42.
