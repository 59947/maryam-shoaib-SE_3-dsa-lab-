LAB NO 2 


                                                                 TASK 1 : 


#include<iostream>
using namespace std;
int main()
 {
 	int arr[5] = {1, 2, 3, 4, 5};
    int *ptr = arr;

    for (int i = 0; i < 5; i++) {
        cout <<*ptr<<endl;
        ptr++;
    }

    return 0;
}

 
                                TASK 2 :


#include<iostream>
using namespace std;

 
 	void swap(int *a, int *b) {
    int temp = *a;
    *a = *b;
    *b = temp;
}

int main() {
    int x = 10, y = 20;
    cout<< " values before swap" <<"x = " << x << "y = " << y <<endl;
    swap(&x, &y);
    cout << "values after swap"  <<"x = " << x << " y = " << y << endl;
    return 0;
}
