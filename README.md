# Write-a-program-that-allows-input-of-a-string
Write a program that allows input of a string
import java.util.Scanner;
public class BaiTapJavaCoBan19
{
    public static void main(String[] args)
    {
       String String;
       int soLan = 0;
       Scanner sc = new Scanner(System.in);

       System.out.println("Enter a string: ");
       string = sc.nextLine();

       char mangKiTu[] = chuoi.toCharArray();
       for (int i = 0; i < mangKiTu.length; i++)
       {
          if ('a' == mangKiTu[i])
          {
             soLan++;
          }
       }
       System.out.println(soLan);
    }
}
