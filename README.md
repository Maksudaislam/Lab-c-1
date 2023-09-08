/*
All code i have made for me..
if you think there is error please don't inform me..
    just correct yourself .....
    if you don't understand anywhere please don't ask for help
    i am giving you guys  because you guys ask for it..
    By Maksuda islam 
[just kidding]

*/
#include<bits/stdc++.h>
using namespace std;
/*Create a class named 'Student' with a string variable 'name' and an integer variable
'roll_no'. Assign the value of roll_no as '2' and that of name as "Jamshed" by creating
an object of the class Student*/
/*
class Student {
public:
    string name;
    int roll_no;



};
int main ()
{
    Student obj1;
    obj1.name="Jamshed";
    obj1.roll_no=2;
    cout<<"student name is : "<<obj1.name<<endl;
    cout<<"student roll number is : "<<obj1.roll_no<<endl;
    return 0;
}
*/
/*Assign and print the roll number, phone number and address of two students having
names "Shofi" and "Jamshed" respectively by creating two objects of the class 'Student'.*/
/*
class Student {

public:
     string name,phone_number ;
    int roll_no;


};
int main()
{
Student obj1,obj2;
obj1.name="Jamshed";
obj1.phone_number="012434566";
obj1.roll_no=1;
obj2.name="Shofi";
obj1.phone_number="0983456";
obj1.roll_no=2;
cout<<"student name "<<obj1.name<<endl<<"student roll number is "<<obj1.roll_no<<endl<<"student phone number "<<obj1.phone_number<<endl;
cout<<"student name "<<obj2.name<<endl<<"student roll number is "<<obj2.roll_no<<endl<<"student phone number "<<obj2.phone_number<<endl;

}
*/
/*Write a program to print the area and perimeter of a triangle having sides of 3, 4 and 5
units by creating a class named 'Triangle' with a function to print the area and perimeter*/
/*
class Triangle {
    public:
int a=3,b=4,c=5;
void calculate(){
int p,area,s;
p=a+b+c;
s=p/2;

area=sqrt(s*(s-a)*(s-b)*(s-c));
cout<<"the perimeter of this triangle "<<p<<endl;
cout<<"the area of this triangle "<<area<<endl;
}
};
int main()
{
    Triangle obj1;
    obj1.calculate();

return 0;

}
*/

/*Write a program to print the area and perimeter of a triangle having sides of 3, 4 and 5
units by creating a class named 'Triangle' with the constructor having the three sides as
its parameters */
/*

class Triangle {
    public:
int a=3,b=4,c=5;
Triangle()
{
    int p,area,s;
p=a+b+c;
cout<<"the perimeter of this triangle "<<p<<endl;
}
};
int main ()
{
    Triangle obj1;
    return 0;
}
*/


/*Write a program to print the area of two rectangles having sides (4, 5) and (5, 8)
respectively by creating a class named 'Rectangle' with a function named 'Area' which
returns the area. Length and breadth are passed as parameters to its constructor.*/

/*
class Rectangle {
    public:
int a,b;
Rectangle(int m,int n)
{ a=m;
b=n;}
int  Area()
{
  int area=a*b;
  return area;

}
};
int main ()
{
   Rectangle obj1(4,5),obj2(5,8);
   cout<<"Area of retangle 1 "<<obj1.Area()<<endl;
   cout<<"Area of retangle 2 "<<obj2.Area()<<endl;



}
*/
/*
Write a program to print the area of a rectangle by creating a class named 'Area' having
two functions. First function named as 'setDim' takes the length and breadth of the
rectangle as parameters and the second function named as 'getArea' returns the area of
the rectangle. Length and breadth of the rectangle are entered through keyboard.
*/
/*
class Area {
public:
    int a,b;
    void setdim()
    {
        cout<<"Enter the length and breadth ";
     cin>> a>>b;
    }
void getArea ()
{
    cout<<"The area of rectangle "<<a*b;
}

};
int main ()
{
 Area obj1;
 obj1.setdim();
 obj1.getArea();
}
*/

/*
Write a program to print the area of a rectangle by creating a class named 'Area' taking
the values of its length and breadth as parameters of its constructor and having a
function named 'returnArea' which returns the area of the rectangle. Length and breadth
of the rectangle are entered through keyboard*/
/*
class Area {

public:
    int length ,breadth;
Area (){
    cout<<"enter the value of length and breadth ";
    cin>> length>>breadth;
}
int returnArea()
{
    int area;
    area=length*breadth;
    return area;
}

};
int main ()
{
    Area obj1;
    cout<<"The area is "<<obj1.returnArea()<<endl;
}
*/
/*Print the average of three numbers entered by the user by creating a class named
'Average' having a function to calculate and print the average without creating any
object of the Average class.
*/
/*
class Average {
public:
    static double x(int a,int b,int c)
    {
        double y;
        y=(a+b+c)/3.0;
        return y;
    }
};
int main()
{
        int a,b,c;
cout<<"Enter 3 numbers ";
cin>>a>>b>>c;
cout<<"the average is "<<Average::x(a,b,c)<<endl;
}
/*

/*Print the sum, difference and product of two complex numbers by creating a class
named 'Complex' with separate functions for each operation whose real and imaginary
parts are entered by the user.*/
/*

class Complex{
public :

    void calculate (int al,int bl,int cl,int dl)
    {

     int a,b,c,d,sr,dir,pr,sc,dic,pc;
     sr=al+cl;
     sc=bl-dl;
     dir=al-cl;
     dic=bl-dl;
     pr=al*cl;
     pc=(-1*bl*dl);
     if(sr>0)
     cout<<"The sumation is "<<sc<<"i+"<<sr<<endl;
     else
     cout<<"The sumation is "<<sc<<"i"<<sr<<endl;
        if(dir>0)
     cout<<"The difference is "<<dic<<"i+"<<dir<<endl;
     else
     cout<<"The difference is "<<dic<<"i"<<dir<<endl;
        if(pr>0)
        cout<<"the product is "<<pc<<"i+"<<pr<<endl;
        else
        cout<<"the product is "<<pc<<"i"<<pr<<endl;

    }
};
int main ()
{int a,b,c,d;
char ch,dh;
  Complex obj1;
  cout<<"enter a complex number ";
  cin>> a>>ch>>dh>>b;cout<<"enter another  complex number ";
  cin>> c>>ch>>dh>>d;
  obj1.calculate(a,b,c,d);
}
*/

/*

Write a program to print the volume of a box by creating a class named 'Volume' with
an initialization list to initialize its length, breadth and height. (Just to make you familiar
with initialization lists*/
/*

class Volume{
public:
 int length,breadth,height;
Volume(int l,int b,int h):length(l),breadth(b),height(h){}
void calculate()
{
    int v;
    v=length*breadth*height;
    cout<<"The volume is :"<<v;
}

};
int main ()
{
  Volume obj(3,4,5);
  obj.calculate();
}
*/
/*
Write a program that would print the information (name, year of joining, salary,
address) of three employees by creating a class named 'Employee'. The output should
be as follows:*/
/*
class Employee{

public:

    void x()
    {
        cout<<"Name\t   "<<"year of joining    "<<"Address\n";
    }
    void display(string m,int n,string w)
    {
        cout<<m<<"\t    "<<n<<"\t\t\t"<<w<<endl;
    }

};

int main ()
{
    string name[100] ,address[100];
    int year[100],i,n;
    double salary[100];
    cout<<"how many employee are there ?";
    cin>>n;
    Employee p,obj[n];
    for(i=0;i<n;i++)
    {
        cout<<"\nenter name of "<<i+1<<" no employee   :";
        cin>>name[i];
                cout<<"\nenter address of "<<i+1<<" no employee  :";

        cin>>address[i];
                cout<<"\nenter year of joining of "<<i+1<<" no employee  :";

        cin>>year[i] ;
    }
        p.x();
        for(i=0;i<n;i++)
    {
        obj[i].display(name[i],year[i],address[i]);
    }

    return 0;
}
*/
/*
Write a program by creating an 'Employee' class having the following functions and
print the final salary.
1 - ‘getInfo ()' which takes the salary, number of hours of work per day of employee
as parameters
2 - 'AddSal()' which adds $10 to the salary of the employee if it is less than $500.
3 - ‘AddWork ()' which adds $5 to the salary of the employee if the number of hours
of work per day is more than 6 hours*/

/*
class Employee {
public:
    double salary[1000];
    int hour[1000];
    int i, n;

    void getInfo() {
        printf("How many workers are there?\n");
        scanf("%d", &n);
        for (i = 0; i < n; i++) {
            printf("enter %d no worker salary\n", i + 1);
            scanf("%lf", &salary[i]);
            printf("enter %d no workering hour hours\n", i + 1);
            scanf("%d", &hour[i]);
            addSal();
            addWork();
            display();
        }
    }

    void addSal() {
        if (salary[i] < 500)
            salary[i] += 10;
    }

    void addWork() {
        if (hour[i] > 6)
            hour[i] += 5;
    }

    void display() {
        printf("the salary is: %.2lf$\n", salary[i]);
    }
};

int main() {
    Employee obj;
    obj.getInfo();

    return 0;
}
*/
/*
.Create a class called 'Matrix' containing constructor that initializes the number of
rows and the number of columns of a new Matrix object. The Matrix class has the
following information:
1 - number of rows of matrix
2 - number of columns of matrix
3 - elements of matrix (You can use 2D vector)
The Matrix class has functions for each of the following:
1 - get the number of rows
2 - get the number of columns
3 - set the elements of the matrix at a given position (i, j)
4 - adding two matrices.
5 - Multiplying the two matrices
you can assume that the dimensions are correct for the multiplication and addition*/
/*
class Matrix {
public:
    int m, n;
    int mat[100][100];

    Matrix(int r, int c) : m(r), n(c) {
        int i, j;
        for (i = 0; i < m; i++) {
            for (j = 0; j < n; j++) {
                cout << "Enter value of matrix [" << i << "][" << j << "]: ";
                cin >> mat[i][j];
            }
        }
    }

    Matrix(const Matrix& other) {
        m = other.m;
        n = other.n;
        for (int i = 0; i < m; i++) {
            for (int j = 0; j < n; j++) {
                mat[i][j] = other.mat[i][j];
            }
        }
    }

    void addMatrices(const Matrix& other) {
        if (m != other.m || n != other.n) {
           cout<< "Matrix dimensions do not match for addition." << endl;
            return;
        }
cout<<"Matrix addition\n";
        for (int i = 0; i < m; i++) {
            for (int j = 0; j < n; j++) {
                cout << mat[i][j] + other.mat[i][j] << " ";
            }
            cout << endl;
        }
    }

    void multiplyMatrices(const Matrix& other) {
        if (n != other.m) {
            cout<< "Matrix dimensions are not compatible for multiplication." << endl;
            return;
        }

        int result[100][100] = {0};
        for (int i = 0; i < m; i++) {
            for (int j = 0; j < other.n; j++) {
                for (int k = 0; k < n; k++) {
                    result[i][j] += mat[i][k] * other.mat[k][j];
                }
                cout << result[i][j] << " ";
            }
            cout << endl;
        }
    }
};

int main() {
    int a, b;
    cout << "Enter the row and column number: ";
    cin >> a >> b;

    Matrix obj1(a, b);
    Matrix obj2(a, b);

    cout << "Matrix 1:" << endl;
    obj1.addMatrices(obj2);

cout << "Matrix Multiplication:" << endl;
    obj1.multiplyMatrices(obj2);

    return 0;
}
*/
