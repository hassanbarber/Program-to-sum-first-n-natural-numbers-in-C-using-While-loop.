# Program-to-sum-first-n-natural-numbers-in-C-using-While-loop.
Program to sum first n natural numbers in C++ using While loop.
#include <iostream>
using namespace std;
int main()
{
     int n, count, sum = 0;
    cout<<"Nhập vào n (số lượng phần tử đầu tiên cần tính tổng): ";
    cin>>n;
    count=1;
    while(count <= n){
        sum = sum + count;
        count++;
    }
    cout<<endl<<"Tổng "<<n<<" đầu tiên là: "<<sum;
    cout<<"\n-----------------------------------\n";
    cout<<"Chương trình này được đăng tại Freetuts.net";
