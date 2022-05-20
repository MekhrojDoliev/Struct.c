#include <stdio.h>
#include <stdlib.h>
#include <string.h>
struct Student{
 char name[50];
 double gpa;
 int age;
 char major[50];   
};

int main (){
struct Student student1;
student1.age = 22;
student1.gpa = 3.7;
strcpy(student1.name ,"Tony");
strcpy(student1.major , "Business");

struct Student student2;
student2.age = 25;
student2.gpa = 4.0;
strcpy(student2.name ,"Dony");
strcpy(student2.major , "BusArtiness");

printf("%s\t",student2.major);



    return 0;
}
