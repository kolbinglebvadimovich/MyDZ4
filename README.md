#include <iostream>
#include <string>

int main()
{
     // Цикл с пердусловием (while).
     std::string answer{};
     while (answer != "NUMBER" && answer != "number")
     {
          std::cout <<  "Enter" \"NUMER\" or \"number\" to exit: ";
          std::getline(std::cin >> std::ws, answer);
     }

     return EXIT_SUCCESS;
}
