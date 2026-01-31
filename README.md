# WEEK7-ASSIGNMENT
#include <string> using namespace std;
class Employee { private:     string name;     int age;     int serviceYear;     double salary;
public:     Employee(string n, int a, int s, double sal) {         name = n;         age = a;         serviceYear = s;         salary = sal;     }     ~Employee() {}
    string getName() const { return name; }     int getAge() const { return age; }     int getServiceYear() const { return serviceYear; }     double getSalary() const { return salary; }
};

