package main

import "fmt"

func main() {
	var num int
	var comp string
	fmt.Scan(&num)
	if num == 11 || num == 12 || num == 13{
		comp = "компьютеров"
	} else if num % 10 == 1 {
		comp = "компьютер"
	} else if num % 10 == 2 || num % 10 == 3 {
		comp = "компьютера"
	} else {
		comp = "компьютеров"
	}
	fmt.Printf("%d %s", num, comp)
	}
