#include <stdio.h>
int main() {
    long long int a, r, n;  //곱하기의 특성상 int의 범위를 벗어나는 정수가 나타날 수 있기 때문에 long long int 사용
    scanf("%lld %lld %lld", &a, &r, &n); \  //a : 시작값, r : 곱해지는 값, n : 몇 번째인지 나타내는 수
    for( ; (n-1) > 0; n--) {  //구문을 줄이기 위해 for문 사용
        a *= r;  //a에 n을 곱한 값을 a에 대입
    }
    printf("%lld", a);  //a값 출력
    return 0;
}
