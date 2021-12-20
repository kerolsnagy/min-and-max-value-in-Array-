# min-and-max-value-in-Array-
package com.company;

import jdk.swing.interop.SwingInterOpUtils;

import java.util.Scanner;

class JAVA
{
    public static void main (String args[])
    {
        int arr[]={5,2,6,8};
        Scanner n=new Scanner(System.in);
        int min=arr[0];
        int max=arr[0];

        for (int i = 1; i < arr.length; i++)
        {
            if(arr[i]<min)
                min=arr[i];
            if (arr[i]>max)
                max=arr[i];
        }
        System.out.println("max =" +max); 
        System.out.println("min =" +min);
    }
}



