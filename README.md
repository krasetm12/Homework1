# Homework1
public class MainClass
{
   public int getLocalNumber()
    {

        return 14;
    }
}


import org.junit.Test;

public class MainClassTest extends MainClass
{
    @Test
    public void testGetLocalNumber(){
       int a=this.getLocalNumber();
       if (a==14){
           System.out.println("getLocalNumber return 14");
       }
       else{
           System.out.println("getLocalNumber do not return 14");
       }
    }

}