# reverse-of-single-line-number-in-c++

<code>
#include <iostream>
#include <algorithm>  // for reverse()
using namespace std;

int main() {
    int n;
    cin >> n;
    int arr[n];

    for (int i = 0; i < n; i++) cin >> arr[i];

    reverse(arr, arr + n);  // one line reverse

    for (int i = 0; i < n; i++) cout << arr[i] << " ";

    return 0;
}
