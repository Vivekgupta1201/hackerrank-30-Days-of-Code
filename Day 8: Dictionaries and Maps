//Complete this code or write your own from scratch
import java.util.*;
import java.io.*;
Day 7: Arrays
class Solution{
    public static void main(String []argh){
        Scanner in = new Scanner(System.in);
        int n = in.nextInt();
        HashMap<String,Integer> m=new HashMap<>();
        for(int i = 0; i < n; i++){
            String name = in.next();
            int phone = in.nextInt();
            // Write code here
            m.put(name,phone);
        }
        while(in.hasNext()){
            String s = in.next();
            // Write code here
            if (!m.containsKey(s))
            System.out.println("Not found");
            else
            System.out.println(s+"="+m.get(s));
        }
        in.close();
    }
}
