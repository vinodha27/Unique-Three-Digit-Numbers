# Unique-Three-Digit-Numbers
Write a Java program to create and display a unique three-digit number using 1, 2, 3, 4. Also count how many three-digit numbers are there.  Total number of the three-digit-number is 24

class Main {
    public static void main(String[] args) {
      int  a=0;
       for(int i=1;i<=4;i++)
       {
           for(int j=1;j<=4;j++)
           {
               for(int k=1;k<=4;k++)
               {
                   if(i!=j && j!=k && k!=i)
                   {
                       a++;
                       System.out.println(i+""+j+""+k+"");
                   }
               }
           }
       }
       System.out.println(a);
    }
}

    
