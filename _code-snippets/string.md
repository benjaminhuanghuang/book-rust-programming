



## String to number
```
let mut guess = String::new();

let guess: u32 = match guess.trim().parse() {
  Ok(num) => num,
  Err(_) => continue,
};
```

## iteration
```
  let bytes = s.as_bytes();

  for (i, &item) in bytes.iter().enumerate() {
      if item == b' ' {
   
      }
  }


```