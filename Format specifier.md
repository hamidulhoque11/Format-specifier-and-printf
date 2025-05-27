//Format Specifier and Printf
class Main {
    public static void main(String[] args) {
        boolean b = true;
        char c= 'h';
        short s = 3654;
        int i= 6542;
        float f=10.6f;
        double d= 50.24521;
        
        System.out.printf("boolean b = %b\n",b);
        System.out.printf("char  c = %c\n",c);
        System.out.printf("short  s = %d\n",s);
        System.out.printf("int  i = %d\n",i);
        System.out.printf("float  f = %.1f\n",f);
        System.out.printf("double  d = %.5f\n",d);
        
    }
}
