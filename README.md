<<<<<<< HEAD

=======
#include <iostream>
using namespace std;
int main() {
    int n;
    cin >> n;
    int count = 0;
    for (int i = 0; i < n; i++) {
        int a, b, c;
        cin >> a >> b >> c;
        if (a + b + c >= 2) {
            count++;
        }
    }
    cout << count << endl;
    return 0;
}
>>>>>>> 0abf827c4ab58f14b334d7f11e122bdbf6a3b000
