# Java

## Lamda Expression:
### Why use Lambda Expression
To provide the implementation of Functional interface.
Less coding.

No Parameter Syntax
() -> {  
//Body of no parameter lambda  
}  

One Parameter Syntax
(p1) -> {  
//Body of single parameter lambda  
}  

Two Parameter Syntax
(p1,p2) -> {  
//Body of multiple parameter lambda  
}  

### Without Lambda Expression
Drawable d=new Drawable(){  
            public void draw(){System.out.println("Drawing "+width);}  
        };  
        d.draw();  
        
 ### Java Lambda Expression Example        
 Drawable d2=()->{  
            System.out.println("Drawing "+width);  
        };  
        d2.draw();
