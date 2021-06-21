
print
```
  use std::io;
  
  println!("Guess the number!");
  println!("The secret number is: {}", secret_number);
```



read
```
let mut guess = String::new();
  
io::stdin()
    .read_line(&mut guess)
    .expect("Failed to read line");
```