# Codeup1463

//n*n 배열구조 출력
//ex. 입력=3;
//3 6 9
//2 5 8
//1 4 7


public class CodeUp1463{
public static void main(String[] args){
  Scanner sc=new Scanner(System.in);
  int n=sc.nextInt();
  int[][] arNum=new int[n][n];
  int x=n;
  for(int i=0 ; i < n ; i++){
    for(int j=0 ; j < n ; j++){
        arNum[i][j]=x;
        x=(n-1)+(n*(j+1));
        System.out.print(arNum[i][j]+" ");
    }
     System.out.println();
     x=n-(i+1);
    }
  }
}
