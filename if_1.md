# 조건문 if

```java
int a = 8;

if (a % 2 == 0) {// a 나누기 2의 나머지가 0 - 짝수
	System.out.println("짝수");
}

else if (a % 3 ==0) {
	System.out.println("홀수");
}

else if (a % 6 ==0) {
	System.out.println("6");
}

int b = 9;

if (b % 2 != 0) {// b나누기 2의 나머지가 0이 아닐떄 - 홀수
	System.out.println("홀수");
}

&& : and 둘다 만족
|| : or 둘중에 하나 만족

if(a % 2 ==0 && a % 4 == 0) {
		System.out.println("a를 2로 나누었을 때 0 그리고 a를 4로 나누었을 때 0 ");
}
else if (a % 3 == 0 || a % 4 == 0) {
		System.out.println("a를 3로 나누었을 때 0 또는 a를 4로 나누었을 때 0");
}
```