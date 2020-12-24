// TIME COMPLEXITY O(N)
import java.util.*;
import java.lang.*;
import java.io.*;
class GFG
 {
	public static void main (String[] args) throws Exception
	 {
	  BufferedReader br=new BufferedReader(new InputStreamReader(System.in));
	  int n=Integer.parseInt(br.readLine());
	  while(n--!=0){
	      String str=br.readLine();
	      HashMap<Character,Integer> map=new LinkedHashMap<Character,Integer>();
	      boolean flag=true;
	      for(int i=0;i<str.length();i++){
	          char x=str.charAt(i);
	          Integer j=map.get(x);
	          if(j==null){
	              map.put(x,1);
	          }else{
	              map.put(x,j+1);
	              if((j+1)>(str.length()-j)){
	                  System.out.println(0);
	                  flag=false;
	                  break;
	              }
	          }
	      }
	      if(flag)
	      System.out.println(1);
	  }
	 }
}
