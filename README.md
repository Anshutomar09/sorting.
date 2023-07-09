# sorting.

// Online C++ compiler to run C++ program online
#include <iostream>
#include<vector>
#include<algorithm>
using namespace std;
int main() {
    // Write C++ code here
    vector<int> v={4,2,8,5,9};
    sort(v.begin(),v.end());
    for(const auto &i: v){
        cout<< i <<endl;
    }
    return 0;
}
