# hackerrank



import java.io.*;
import java.math.*;
import java.security.*;
import java.text.*;
import java.util.*;
import java.util.concurrent.*;
import java.util.regex.*;

public class Solution {
    public static void main(String args[]) throws Exception
    {
    
    int count=0;
    Scanner sc = new Scanner(System.in);
    int n = sc.nextInt();
    
    String[] strings = new String[n];
    String[] query = new String[n];
    
    for(int i=0;i<n;i++)
    {
        strings[i] = sc.next();
    }
    
    int n1 = sc.nextInt();
    for(int j=0;j<n1;j++)
    {
        query[j] = sc.next();
    }
    
    for(int i=0;i<n1;i++)
    {
        count=0;
        for(int j=0;j<n;j++)
        {
            if  ((strings[j].equals(query[i])))
            {
                count = count+1;
            }
           
            
        }
        System.out.println(count);
       
            
            
            
    }
  }
    
        
    
}
