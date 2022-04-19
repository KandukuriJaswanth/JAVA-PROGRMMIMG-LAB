TASK-1(a)
Write  a  java programs that implements constructor
       public class Box
          {
    double width;
    double height;
   double  depth;
   Box(double w, double h, double d)
   {
      width = w;
      height = h;
      depth =  d; 
   } 
    double volume()
     {
        return width*height*depth;
     }
}
   class constructor
    {
       public static void main(String args[])
         {
             Box mybox1= new Box(10,50,20);
               double vol;
               vol = mybox1.volume();
              System.out.println(“volume is “+vol);
          }
   }
    


