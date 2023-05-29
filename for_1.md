# for 문 복습

```
public static void main(String[] args) {
		for (int i = 1; i <= 100; i++) {    
    if (i % 2 == 0) {
            System.out.println(i+" 짝수 입니다");
        } else {
            System.out.println(i+" 홀수 입니다");
        }
    }
    System.out.println();

    for (int i = 1; i <= 100; i++) {
         if (i % 3 ==0 || i%10 ==0) {
             System.out.println("짝");
        } else {
             System.out.println(i);
         }
    }
        System.out.println();

    for (int i = 1; i <= 100; i++) {
        if (i % 3 ==0 ) {
            System.out.println("짝");
        } else if (i %10 == 0) {
            System.out.println("짝짝");
        } else {
            System.out.println(i);
        }
    }
    System.out.println();

        int i = 1;
        while (i<=100) {
            if (i % 2 == 0) {
                System.out.println(i+" 짝수 입니다");
            } else {
                System.out.println(i+" 홀수 입니다");
            }
            i++;
        }
        System.out.println();

        int  j= 1;
        while (j <=100) {
          if (j % 3 ==0) {
             System.out.println("짝");
          } else {
             System.out.println(j);
            }
          j++;
        }
}

```

}