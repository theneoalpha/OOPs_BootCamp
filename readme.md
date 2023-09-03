        # OOPs BootCamp Notes

             OOPs(Object oriented Progaming) is used for "Easily Solving real world problems using classes and Objects".


             Package            (Group of Classes)
                |
                |
             Classes         (Group of Methods/Attributes)
                |
                |
         Method/Function       (Group of Actions / operations)



        #   BASIC JAVA PROGRAM

             package basic;

             public class MainClass {
                public static void main(String[] args){

                    System.out.println("Hello World");
                }
             }


        # Classes and Objects 

            basic components of OOPs - Classes and Objects

            # Pseudo Code 
                File.java

                    public class File{           [Single public class and  the file name and public class name must be same]
                        
                        class Phone{

                        }

                        class Car{

                        }
                    }     

            # Actual code with classes and object      


                MainClass.java

                    package basics;

                    class Person{
                        String name;
                        int age;
                    }  

                    public class MainClass{
                        public static void main(String[] args){
                            Person p1 = new Person();     //Normal Class(jo public na ho) ko access karne ke liye uss class ka object banana padhta hai.then only access kar sakte hai.
                            p1.name = "Deepak";
                            p1.age = 34;
                
                        }
                    }
            
        



