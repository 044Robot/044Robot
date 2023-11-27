#include <iostream>
#include <cmath>

const double PI = 3.14159265358979323846;

int main() {
    double radius;
    std::cout << "Enter the radius of the circle: ";
    std::cin >> radius;

    double perimeter = 2 * PI * radius;
    double area = PI * pow(radius, 2);

    std::cout << "Perimeter of the circle: " << perimeter << std::endl;
    std::cout << "Area of the circle: " << area << std::endl;

    return 0;
}


















