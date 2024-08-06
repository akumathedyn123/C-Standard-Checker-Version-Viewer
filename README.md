# Project Name: C-Standard-Checker

**Description:**

This simple C program determines the C standard version supported by your compiler. This information can be helpful for ensuring code compatibility across different compiler environments.

**License:**

The Unlicense

**Getting Started**

1. **Clone the Repository:**

   Use the following command to clone this repository to your local machine:

   ```bash
   git clone https://github.com/akumathedyn123/C-Standard-Checker-Version-Viewer.git
   ```


2. **Compiling and Running:**

   **Linux/macOS:**

     a. Navigate to the project directory:

        ```bash
        cd C-Standard-Checker
        ```

     b. Compile the code using a C compiler like GCC:

        ```bash
        gcc main.c -o c_standard_checker
        ```


     c. Run the program:

        ```bash
        ./c_standard_checker
        ```


   **Windows:**

     a. Install a C compiler like MinGW ([https://www.mingw-w64.org/](https://www.mingw-w64.org/)).

     b. Open a command prompt or terminal and navigate to the project directory:

        ```
        cd C-Standard-Checker
        ```

     c. Compile the code using the appropriate MinGW commands (replace `gcc` with your MinGW compiler name, typically `g++`):

        ```bash
        g++ main.c -o c_standard_checker.exe
        ```


     d. Run the program:

        ```bash
        c_standard_checker.exe
        ```

**Compiling with Different Compilers:**

The provided instructions use `gcc` for Linux/macOS and MinGW for Windows. You can adapt these steps by substituting the appropriate compiler command for your preferred environment:

* **Clang:**

   ```bash
   clang main.c -o c_standard_checker
   ```

* **Microsoft Visual Studio (Windows):**

   - Create a new C project.
   - Add `main.c` to your project source files.
   - Build and run the project.

**Understanding the Output:**

The output will display a number representing the C standard version supported by your compiler. You can find more information about specific C standard versions online (e.g., C99, C11, etc.).

**Contribution:**

We welcome contributions to improve this project. Feel free to submit pull requests for bug fixes, enhancements, or additional compiler support.
