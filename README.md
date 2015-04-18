public class Fibo {

        public static void main (String []args){

            int n1=1;
            int n2=2;
            int n3=0;
            int sum=0;

            do {
                n3=n1+n2;
                if (n2%2==0){
                    sum = sum + n2;
                }
                n1=n2;
                n2=n3;
            }
            while (n3<4000000);
            System.out.println(sum);
        }
}
