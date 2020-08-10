package Easy;
import java.util.ArrayList;
import java.util.Collections;
import java.util.List;

public class file2 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		List<String> commands = new ArrayList();
		commands.add("R");
		commands.add("L");
		List<String> returned = new ArrayList();

		
		for (int i =0; i<commands.size(); i++) { // goes through the list
			
			int lcount = 0;
			int rcount = 0;
			String temp = commands.get(i);
			//System.out.println(temp.length());
			
			// loop is going on forever
			for (int j=0; j<commands.get(i).length(); j++) { // goes through each element in the list
				
				if (temp.charAt(j) == 'L') { // checking each character in the string
					lcount++;
					System.out.println("its an L");
				}
				if (temp.charAt(j) == 'R') {
					System.out.println("its an R");
					rcount++;
				}
				
				System.out.println("random");
				
				
			}
			
			// difference between
			
			int difference = lcount-rcount;
			if (difference %4 != 0) {
				returned.add("YES");
			}
			else {
				returned.add("NO");
			}
			
			
			
		}
		System.out.println(returned);


	}

}
