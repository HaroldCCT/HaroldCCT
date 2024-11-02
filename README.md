```php
<?php

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
      "Python", "HTML", "CSS", "JavaScript", "Node Js(Learning)", "TypeScript"(Learning), "C++", "GitHub", "C"
    },
    OS:  []string{
      "Windous", "Kali Linux"
    },
    Challenge: "I am focused on improving my skills in ethical hacking and expanding my programing knowledge"
  }
  fmt.Printf("User Info: %+v\n", harolddev)
}
```
