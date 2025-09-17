How to Run Tests in Monad

Testing is a crucial part of ensuring that the Monad codebase remains stable and secure. This guide explains how to run the existing test suite locally;

Prerequisites:
 A working build of the Monad project  
 Dependencies installed (see project README for setup)  
 A terminal environment (Linux/macOS or WSL for Windows)

 Running the Tests

 You can run all tests using the following command:

 bash
 make test


  This command will compile and execute all unit and integration tests defined in the codebase.
 
  Running Specific Tests

  To run a specific test suite or file:

bash
./build/tests/test_vm


Replace test_vm with the desired test file name.

Debugging Failing Tests

Use gdb or lldb to step through failures  
Check test logs in the build output  
Make sure test dependencies are correctly built

Note:
Keep your local fork updated with the main branch to avoid conflicts
Run tests after every major change to ensure integrity. 


