# integer


## 양수, 음수, 0을 나타내는 코드
package sungil21102algo;

import java.util.Scanner;
public class 정수 {

	
	public static void main(String[] args) {
		
	
	Scanner stdIn = new Scanner(System.in);
	
	System.out.print("정수를 입력하세요. :");
	int n = stdIn.nextInt();
	
	if (n > 0)
		System.out.println("이 수는 양수입니다.");
	else if (n < 0)
		System.out.println("이 수는 음수입니다.");
	else
		System.out.println("이 수는 0입니다.");
	}

}
