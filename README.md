# Structures-
###STRUCTURES 

 In  an array User-defined data types called structures let you combine variables of several data kinds under a single name. A structure can have one or more members, and each member's data type can vary.
 
 ![image](https://user-images.githubusercontent.com/91966097/234196971-1d6df7bc-a175-4668-9723-19dd4afcc4b5.png)

 
 Basic Syntax
 
 struct person {
   char name[50];
   int age;
   float salary;
};

In the above example, we have defined a structure called person, which has three members: name, age, and salary. name is an array of characters with a size of 50, age is an integer, and salary is a floating-point number.

Code for Student Details 

#include <stdio.h>

struct student {
    char name[50];
    int roll_no;
    int marks;
};

int main() {
    struct student s;

    printf("Enter name: ");
    scanf("%s", s.name);

    printf("Enter roll number: ");
    scanf("%d", &s.roll_no);

    printf("Enter marks: ");
    scanf("%d", &s.marks);

    printf("\nStudent details:\n");
    printf("Name: %s\n", s.name);
    printf("Roll number: %d\n", s.roll_no);
    printf("Marks: %d\n", s.marks);

    return 0;
}

