import java.util.Scanner;
public class LibrarySys{
public static void main(String[] args) {
	Scanner myObj=new Scanner(System.in);
	System.out.println("book name,author,serial,year published");

	String bookname=myObj.nextLine();
	String author=myObj.nextLine();
int serial=myObj.nextInt();
int yearpublished=myObj.nextInt();

System.out.println("bookname"+bookname);
System.out.println("author"+author);
System.out.println("serial"+serial);
System.out.println("yearpublished"+yearpublished);
}

}
