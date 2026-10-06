# MIT-portfolio
portrfolio for MIT

2026 (11 years old)

big projects on CPP:
4-in-one calculator
#include <iostream>
float multiply(float x, float y)
{
	float z{ x * y };
	return z;
}
float divide(float x, float y)
{
	float z{ x / y };
	return z;
}
float add(float x, float y)
{
	float z{ x + y };
	return z;
}
float subtract(float x, float y)
{
	float z{ x - y };
	return z;
}
int main()
{
	std::cout << "enter 2 numbers: ";
	float num1{};
	float num2{};
	std::cin >> num1 >> num2;
	std::cout << "\n";
	std::cout << num1 << "*" << num2 << " = " << multiply(num1, num2) << "\n";
	std::cout << num1 << "/" << num2 << " = " << divide(num1, num2) << "\n";
	std::cout << num1 << "+" << num2 << " = " << add(num1, num2) << "\n";
	std::cout << num1 << "-" << num2 << " = " << subtract(num1, num2) << "\n";

	return 0;
