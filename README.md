# DSA-Problem-Solving-Java-
This repository contains DSA problems I solve daily while learning data structures and algorithms using Java.
Pattern 1
class Main {
    public static void main(String[] args) {
         pattern(5);   
    }
    static void pattern(int n){
    for(int row=1;row<=n;row++){
        for(int col=1;col<=row;col++){
            System.out.print("*");
        }
    System.out.println();
    }
}
}
Output
*
**   
***  
**** 
*****

