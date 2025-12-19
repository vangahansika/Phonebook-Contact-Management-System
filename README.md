# Phonebook-Contact-Management-System
#A Phonebook/Contact Management System in C is a console-based mini-project that utilizes fundamental C programming concepts like structures, functions, file handling, and pointers to store and manage contact information. 
#include<stdio.h>
#include<string.h>
#include<stdlib.h>

// Define a structure to store personal information
struct person
{
    char name[35];
    char address[50];
    long int mble_no;
    char email[100];
};

// Function prototypes
void menu();
void addrecord();
// ... other functions (listrecord, searchrecord, etc.)
