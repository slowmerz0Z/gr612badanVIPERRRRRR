# gr612badanVIPERRRRRR
вайпеерррр
#include <iostream>

void test() {
    throw "OH NO! D:"; 
}

int main(int argc, char **argv)
{
    
    try {
        test();
    } catch (const char *ex) { 
        std::cout << ex << std::endl;
    }

    test();
    
    
    return 0;
}
