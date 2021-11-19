# First Program

    #include <iostream>
    
    // single line comment
   
    /*
       This is a multiline block comment.
       More lines can follow.
    */
    
    int addNumbers(int i, int j)
    {
        return i + j;
    }
    
    int main()
    {
       std::cout << "hello world" << std::endl;  // comments can appear anywhere
       
       int x {5}; int y {3};  // both statements
       
       int sum = addNumbers(x, y);
       
       std::cout << sum << std::endl;
       
       return 0;  // success status code
    }
    
# Data Types

    {
        bool is_selected = true;  // true | false value
        std::cout << is_selected << std::endl;  // prints '1'
    }
