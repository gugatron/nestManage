# NestManage - A C++ Program for Nest Details (Simplified Example)

This is a simplified example of a C++ program to demonstrate storing and displaying basic nest information.  It focuses on core data representation and output, and does not include file I/O or more advanced features.

## Features

* **Data Storage (In-Memory):**  Basic nest information is stored in variables within the program.
* **Display Nest Details:**  The program displays the stored nest information to the console.

## Building and Running

1. **Prerequisites:**
    * A C++ compiler (e.g., g++, clang)
2. **Compilation:**
    ```bash
    g++ -o nestmanage main.cpp 
    ```
3. **Execution:**
    ```bash
    ./nestmanage
    ```

## Usage

The program will run and immediately display the hardcoded nest information to the console.

## Code Structure

* `main.cpp`: Contains the main program logic, including variable declarations and output statements.

## Example `main.cpp` (The Code You Provided):

```cpp
#include <iostream>
using namespace std;

int main() {
    //Nest data
    int pigeonID = 15;
    int pigeonAge = 23;
    float nestFee = 75.25;
    char pigeonNest = 'B';

    //Print variables
    cout << "Pigeon ID:" << pigeonID << "\n";
    cout << "Pigeon Avrage age in Nest:" << pigeonAge << "\n";
    cout << "Nest Fee:" << nestFee << "\n";
    cout << "Pigeon Nest:" << pigeonNest << "\n";

    return 0; // Important to indicate successful program termination
}
