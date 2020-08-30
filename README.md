# JAVA

public class arrayTest {

	public static int maxValue(int[] arr) {
		int max_num = arr[0];  
		for(int e : arr) {
			if(e > max_num) {
			max_num = e;
			}
		}
		return max_num;
	}
	
	public static int minValue(int[] arr) {
		int min_num = arr[0];
		for(int e : arr) {
			if(e< min_num) {
				min_num = e;
			}
		}
		return min_num;
	}
	
	
	
	public static void main(String[] args) {
		// TODO Auto-generated method stub
		int[] arr = new int[] {3,4,1,6,5,2};
		System.out.println(maxValue(arr));  //최댓값출력
		System.out.println(minValue(arr));  //최솟값출력

	}

}
