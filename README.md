# sumseries1
import java.util.Scanner;
class sumseries{
public static void main(String[] args){
System.out.println("Enter the number: ");
 
Scanner n = new Scanner(System.in);
int N=n.nextInt();
int sum=0;

for( int i=1;i<=N;i++){
sum+=i;
}
System.out.println("The sum of the series:"+sum);
}
}
