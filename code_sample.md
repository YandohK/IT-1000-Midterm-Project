# Code Samples

Some code that was written and used for this class.

### Java Script Fizz Buzz
```html
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Fizz Buzz</title>
<script>

for (let i=1;i<=100;i++){
        if (i%3===0 && i%5===0){
          document.write('FizzBuzz<br>');
        }
        else if(i%3===0){
          document.write('Fizz<br>');
        } 
        else if(i%5===0){
          document.write('Buzz<br>');
        } 
        else {
          document.write(i + '<br>');
		}
	}

</script>

</head>

<body onload="fizzbuzz()">
<div id="display">

</div>
</body>

</html>
```

### Volume of Cone Python

```py
import math


radius = float(input("Enter the cone's radius: "))
height = float(input("Enter the cone's height: "))


volume = (1/3) * math.pi * (radius**2) * height


print("The volume of the cone is:", volume)
```

[return to home page](./README.md)