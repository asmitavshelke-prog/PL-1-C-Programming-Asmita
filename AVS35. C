/*
Program (35) ->
Write a program to accept the details of N employees using an array of structures and display the stored employee information.

Solution: Array of Strcture
*/

#include <stdio.h>              // Header file for input and output functions

struct Employee                 // Define a structure named Employee
{
    int emp_id;                 // Declare employee ID
    char name[50];              // Declare employee name
    float salary;               // Declare employee salary
};

int main()
{
    int n, i;                   // Declare variables for number of employees and loop counter

    printf("Enter the number of employees: ");
    scanf("%d", &n);            // Accept the number of employees

    struct Employee emp[n];     // Declare an array of structures

    // Accept employee details
    for (i = 0; i < n; i++)
    {
        printf("\nEnter details of Employee %d:\n", i + 1);
        printf("Enter Employee ID: ");
        scanf("%d", &emp[i].emp_id); // Accept employee ID
        printf("Enter Employee Name: ");
        scanf(" %[^\n]", emp[i].name); // Accept employee name with spaces
        printf("Enter Employee Salary: ");
        scanf("%f", &emp[i].salary); // Accept employee salary
    }

    // Display stored employee details
    printf("\n========== Employee Details ==========\n");

    for (i = 0; i < n; i++)
    {
        printf("\nEmployee %d:\n", i + 1);

        printf("Employee ID: %d\n", emp[i].emp_id);
        printf("Employee Name: %s\n", emp[i].name);
        printf("Employee Salary: %.2f\n", emp[i].salary);
    }

    return 0;                   // Terminate the program
}

/*
Output:

Enter the number of employees: 3

Enter details of Employee 1:
Enter Employee ID: 101
Enter Employee Name: ABC
Enter Employee Salary: 25000

Enter details of Employee 2:
Enter Employee ID: 202
Enter Employee Name: XYZ
Enter Employee Salary: 50000

Enter details of Employee 3:
Enter Employee ID: 303
Enter Employee Name: LMN
Enter Employee Salary: 75000

========== Employee Details ==========

Employee 1:
Employee ID: 101
Employee Name: ABC
Employee Salary: 25000.00

Employee 2:
Employee ID: 202
Employee Name: XYZ
Employee Salary: 50000.00

Employee 3:
Employee ID: 303
Employee Name: LMN
Employee Salary: 75000.00
*/