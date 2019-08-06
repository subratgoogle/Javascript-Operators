## Javascript Operators

<hr> 

<ul> 
  
### Arithmetic Operators
#### An arithmetic operator is a mathematical function that takes two operands and performs a calculation on them. They are used in common arithmetic and most computer languages contain a set of such operators that can be used within equations to perform a number of types of sequential calculation

### Exampe: 
 
     
     <script type = "text/javascript">
            var a = 33;
            var b = 10;
            var c = "Test";
            var linebreak = "<br />";
         
            document.write("a + b = ");
            result = a + b;
            document.write(result);
            document.write(linebreak);
         
            document.write("a - b = ");
            result = a - b;
            document.write(result);
            document.write(linebreak);
         
            document.write("a / b = ");
            result = a / b;
            document.write(result);
            document.write(linebreak);
         
            document.write("a % b = ");
            result = a % b;
            document.write(result);
            document.write(linebreak);
         
            document.write("a + b + c = ");
            result = a + b + c;
            document.write(result);
            document.write(linebreak);
         
            a = ++a;
            document.write("++a = ");
            result = ++a;
            document.write(result);
            document.write(linebreak);
         
            b = --b;
            document.write("--b = ");
            result = --b;
            document.write(result);
            document.write(linebreak);
      </script>
   

### Comparison Operators
####JavaScript has both strict and type–converting comparisons. A strict comparison (e.g., ===) is only true if the operands are of the same type and the contents match. The more commonly-used abstract comparison (e.g. ==) converts the operands to the same type before making the comparison. For relational abstract comparisons (e.g., <=), the operands are first converted to primitives, then to the same type, before comparison.

### Example: 



<script type = "text/javascript">
        
            var a = 10;
            var b = 20;
            var linebreak = "<br />";
      
            document.write("(a == b) => ");
            result = (a == b);
            document.write(result);
            document.write(linebreak);
         
            document.write("(a < b) => ");
            result = (a < b);
            document.write(result);
            document.write(linebreak);
         
            document.write("(a > b) => ");
            result = (a > b);
            document.write(result);
            document.write(linebreak);
         
            document.write("(a != b) => ");
            result = (a != b);
            document.write(result);
            document.write(linebreak);
         
            document.write("(a >= b) => ");
            result = (a >= b);
            document.write(result);
            document.write(linebreak);
         
            document.write("(a <= b) => ");
            result = (a <= b);
            document.write(result);
            document.write(linebreak);
         
      </script>  

### Logical (or Relational) Operators
### Assignment Operators
### Conditional (or ternary) Operators
</ul>
