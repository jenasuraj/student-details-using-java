# student-details-using-java


/*find the details of a student getting total,avg and percentage of 6 subject in 10th class*/
import java.util.Scanner;
public class www {
    public static void main(String[] args)
    {

        int sum=600;
        System.out.println("Name of the student:");
        System.out.println("suraj kumar jena");
        System.out.println("the subjects are :");
        System.out.println("math");
        System.out.println("C - programming");
        System.out.println("chemistry");
        System.out.println("mechanics");
        System.out.println("basic mechanical engineering");
        System.out.println("basic electrical engineering");

           Scanner sc=new Scanner(System.in);
        System.out.println("the marks of each subject is:");
          int Each_subject= sc.nextInt();
        System.out.println(Each_subject);
        System.out.println("the total subject mark is :");
        int total_marks= sc.nextInt();
        System.out.println(total_marks);
        System.out.println("he scored marks in each subjects are");
        System.out.println("the marks of suraj in math is:");
        int math= sc.nextInt();
        System.out.println(math);
        System.out.println("the marks of suraj in c-programming is:");
        int c_programming= sc.nextInt();
        System.out.println(c_programming);
        System.out.println("the marks of suraj in chemistry is:");
        int chemistry=sc.nextInt();
        System.out.println(chemistry);
        System.out.println("the marks of suraj in mechanics is:");
        int mechanics= sc.nextInt();
        System.out.println(mechanics);
        System.out.println("the marks of suraj in basic mechanical engineering is :");
        int mechanical= sc.nextInt();
        System.out.println(mechanical);
        System.out.println("the marks of suraj in basic electrical engineering is :");
        int electrical= sc.nextInt();
        System.out.println(electrical);

        System.out.println("the total marks of suraj is:");
        int total=math+c_programming+chemistry+mechanics+mechanical+electrical;
        System.out.println(total);
        System.out.println("the average marks of suraj kumar jena is:");
        int average=total/6;
        System.out.println(average);
        System.out.println("now the percentage of suraj kumar jena is :");
        int percentage =total/sum*100;
        System.out.println(percentage);
    }

}
