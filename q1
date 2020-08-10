package Easy;
import java.util.ArrayList;
import java.util.Collections;

public class file {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		
		String newstr = "";
		String s = "baca";
		for (int i = 0; i<s.length(); i++) {
			
			for (int j = i; j<= s.length(); j++) { // start at i because that is like the left counter
				String temp = s.substring(i,j);
				System.out.println(temp);
				if (temp.compareTo(newstr) > 0) { // for unicode comparison
					newstr = s.substring(i,j);
				}
			}
			
			
		}
		
		System.out.println(newstr);	

}
}

/* baca    
 * 
 * 
 * b
 * ba
 * bac
 * baca
 * a
 * ac
 * aca
 * c
 * ca
 * 
 * 
 * 
 * 
 * 
 * */

