package Brainy;

public class Array_occurno {
public static int occurance(int arr[],int n,int y)
{
	int cnt=0;
	for (int i=0;i<n;i++) {
	if(y==arr[i])
	
		cnt++;
	
	
	}
	return cnt;
}
	
	
	
	
	
	
public static void main(String[] args) {
	
		int arr[]= {4,10,5,5,5,4,3,5,5,2};
		int n=arr.length;
		int y=4;
		System.out.println(occurance(arr,n,y));
		
		
	
}
}
