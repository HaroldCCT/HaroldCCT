<div align="center">
<picture><img src = "https://github.com/7oSkaaa/7oSkaaa/blob/main/Images/about_me.gif?raw=true" width = 50px></picture> <h2> Hello, I'm Harold <img src="https://github.com/ABSphreak/ABSphreak/blob/master/gifs/Hi.gif" width="30px"></h2>
</div>
  
```php
package main

import "fmt"

type User struct {
  Name            string
  Age             int
  NativeLangauge  string
  Languages       []string
  Knowledge       []string
  Challenge       string
  OS              []string
}

func main() {
  harolddev := User{
    Name:              "Harold",
    Age:               22,
    NativeLangauge:    "ES",
    Languages:         []string{"Espnañol", "Ingles"},
    Knowledge:    []string{
      "Python", "HTML", "CSS", "JavaScript", "Node Js"(Learning), "TypeScript"(Learning), "C++", "GitHub", "C"
    },
    OS:  []string{
      "Windous", "Kali Linux"
    },
    Challenge: "I am focused on improving my skills in ethical hacking and expanding my programing knowledge"
  }
  fmt.Printf("User Info: %+v\n", harolddev)
}
```
