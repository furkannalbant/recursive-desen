# recursive-desen


## code 

```java 
static  void desen ()
      {
          boolean  loop = true;
          while (loop)
          {
          Scanner inp= new Scanner(System.in);
          int Sayi =0 ,deger=0;
          System.out.println("\nSayi Giriniz");
          Sayi=inp.nextInt();
          System.out.print(Sayi+" ");
       if (Sayi!=deger){
           deger=Sayi;
            while (deger>0) {
                System.out.print((deger -= 5)+" ");
            }
            while (deger !=Sayi) {
               System.out.print((deger += 5)+" ");
           }
       }
       else {

            System.out.print(Sayi);
            }
         }
      }




     public static void main(String[] args) {

     
         desen();


    }
```
