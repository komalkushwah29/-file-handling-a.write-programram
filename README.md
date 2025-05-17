# -file-handling-a.write-programramimport java.io.*;
public class code {
    public static void main(String[] args)  throws IOException{
        int a=2;
        int b=5;

        FileWriter r=new FileWriter("hell1.txt");
        for(int i=1;i<=10;i++)
        {
            r.write("table:" +(i*a));
            r.write("\n");
        }
        //r.write("sum"+(a+b));
        r.close();
