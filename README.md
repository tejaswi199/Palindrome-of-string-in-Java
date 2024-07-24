# Palindrome-of-string-in-Java
#checking if string is palindrome or not
public class Main{
    public static void main(String[] args){
       String s="dod";
       
       int last=s.length()-1;
       String rev="";
       
       for(int i=0;i< s.length();i++){
           rev=rev+s.charAt(last);
           last--;
       }
      
        if(s.equals(rev)){
            System.out.println("Palindrome");
        }
        else{
            System.out.println("Not Palindrome");
        }
       
  }
}



