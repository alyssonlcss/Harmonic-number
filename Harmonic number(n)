#include <stdio.h>

int rec(int num);

int main() {
	int num;
	float result;
	
	//input
	do {
	printf("\nNumber (n > 0): ");
	scanf("%d", &num);
	}while(num < 1);

	result = 1 + rec(num);

	//output
	printf("Harmonic number(h) = %f\n", result);

	return 0;

}

//recursive processing function
int rec(int num) {
	float h;	

	if(num == 1) {
		h = 1/1; // 1;
		return h; 
	}
	else {
		h = 1/num + 1/rec(num-1);
		return h;
	}
}
