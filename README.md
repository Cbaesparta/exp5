# EXPERIMENT 5
c++ decision making statements

## Theory

C++ decision making statements

### if Statement

The `if` statement evaluates a condition. If the condition is true, a block of code is executed.

### if...else Statement

The `if...else` statement allows the program to execute one block of code if the condition is true, and a different block of code if the condition is false.

### if...else if...else Statement

The `if...else if...else` statement is used to test multiple conditions. It allows the program to execute different blocks of code based on which condition is true. Only the block of the first true condition is executed.

### Nested if Statements

Nested `if` statements are `if` statements within another `if` or `else` block. They allow the program to test multiple conditions in a hierarchical manner.

### switch Statement

The `switch` statement evaluates an expression and executes a block of code corresponding to the value of the expression. It allows for a more readable way to compare a variable against multiple values. Each value is called a "case", and the `switch` statement can have an optional `default` case to execute if none of the cases match.
### CODE:
![image](https://github.com/user-attachments/assets/e470c735-a118-4a1b-878e-a423353276ce)
![image](https://github.com/user-attachments/assets/ff09cbdf-d12a-4416-b403-fef0336c6072)
![image](https://github.com/user-attachments/assets/b5b110b4-8f6f-4fd2-b051-33f6c9d67dae)
![image](https://github.com/user-attachments/assets/100dff18-f177-40e2-8560-8241fcd2108e)
![image](https://github.com/user-attachments/assets/989e6ec3-02a1-460a-8365-c804074efba4)
![image](https://github.com/user-attachments/assets/e2360b84-89ca-475a-abf8-a9596ff88c20)
```
//Sai Sankar Jena
//23070123112
//EnTC B2
//Exp-2 operators
#include <iostream>
using namespace std;
int main()
{
    //arithmetic operators:
    int x,y,sum,sub,mult,divs,mod,inc,dcr;
    cout<<"enter the first number:";
    cin>>x;
    cout<<"enter the number:";
    cin>>y;
    sum=x+y;
    cout<<"x+y="<<sum;
    sub=x-y;
    cout<<"\nx-y="<<sub;
    mult=x*y;
    cout<<"\nx*y="<<mult;
    divs=x/y;
    cout<<"\nx/y="<<divs;
    mod=x%y;
    cout<<"\nx%y="<<mod;
    cout<<"\nx++="<<++x;
    cout<<"\nx--="<<--x;
    //comparision operators:
    int w,z,eq,neq,geq,leq,g,l;
    cout<<"\nenter the first number:";
    cin>>w;
    cout<<"enter the second number:";
    cin>>z;
    eq=(w==z);
    cout<<"\n"<<eq;
   
    leq=(w<=z);
    cout<<"\n"<<leq;
   
    geq=(w>=z);
    cout<<"\n"<<geq;
   
    g=(w>z);
    cout<<"\n"<<g;
   
    l=(w<z);
    cout<<"\n"<<l;
   
    neq=(w!=z);
    cout<<"\n"<<neq;
   
     //logical operators:
    int j,k,a,o,n;
    cout<<"\nenter the first number:";
    cin>>j;
    cout<<"enter the second number:";
    cin>>k;
    cout<<"\n" << (x > 1 && x < 10);
    cout<<"\n" << (x > 1 || x < 10);
    cout <<"\n"<< (!(x > 1 && x < 10));
   
    //assignment operators:
        int s;
        cout<<"\nenter the first number:";
        cin>>s;
        cout<<"\n" <<s;
        s += 3;
        cout<<"\n"<< s;
        s -= 3;
        cout<<"\n"<<s;
        s *= 3;
        cout<<"\n"<<s;
        s /= 3;
        cout<<"\n"<<s;
        s %= 3;
        cout<<"\n"<<s;
        s &= 3;
        cout<<"\n"<<s;
        s |= 3;
        cout<<"\n"<<s;
        s ^= 3;
        cout<<"\n"<<s;
        s >>= 3;
        cout<<"\n"<<s;
        s <<= 3;
        cout<<"\n"<<s;
 

// bitwise operators
int f,v;
    cout<<"\nenter the first number:";
    cin>>f;
    cout<<"enter the second number:";
    cin>>v;
    cout << "f & v = " << (f & v) << endl;
    cout << "f | v = " << (f | v) << endl;
    cout << "f ^ v = " << (f ^ v) << endl;
    cout << "~(" << f << ") = " << (~f) << endl;
    cout << "~(" << v << ") = " << (~v) << endl;
    return 0;
}
```





