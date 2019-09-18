# find_duplicate

package elclipse;
import java.util.*;
public class LinkedList {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		int a[]= {2,8,5,7,6,1,9,3,7};
		int n=a.length;
		duplicate(a,n);  //calling duplicate function
	
	
}
	public static void duplicate(int a[],int n) {
		
		for(int i=0;i<n;i++) {
			for(int j=i+1;j<n;j++) {
				if(a[i]==a[j]) {
					System.out.println(a[i]); ///printing the duplicate element
					
				}
			}
			
		}
	}
	
}

///time complexity of this solution is o(n^2);
