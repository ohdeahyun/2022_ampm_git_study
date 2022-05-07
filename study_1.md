# 오대현의 일기장

## 목차
###  자기소개
* 오늘 할일
* 코드 
* 내일 할일

## (h2) 1. 자기소개
 소프트웨어공학과 22학번 오대현입니다.

## (h2) 2. 오늘의 할일
* *깃 스터디 과제*
* 영어회화 과제
* 일반물리학실험 과제
* 수학 과제
### (h3) 3. 코드(c언어 과제) 
실수의 거듭제곱 형태

#### (h4)

    #define _CRT_SECURE_NO_WARNINGS
    #include <stdio.h>
    int main()
    {
    
    double num1,b;
	int t, i;
	
	b = 1;

	printf("실수의 값을 입력하십시오: ");
	scanf("%lf", &num1);
	
    printf("거듭제곱 횟수를 입력하시오: ");
	scanf("%d", &t);
	for (i = 1; i <= t; i++) {
		b = b * num1;
	}
	printf("%lf", b);
	return 0;
    }
#### (1+2+3+...+n)이 1만을 넘지 않으면서 가장 큰 값과 그때의 n값


    #define _CRT_SECURE_NO_WARNINGS
    #include <stdio.h>
    int main(){
    
    int i, sum=0;
	
    for(i=1;;i++)
	{
	    sum += i;
		if (sum > 10000)
			break;
	}
	    printf("1부터 %d까지의 합이 %d입니다.", i-1, sum-i);
	    return 0;
    }
### (h3) 4. 내일 할일

 약속이 없어서 **기숙사에서 게임할 예정이다**
 
  ~~메이플~~