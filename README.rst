golang base36
================



.. contents::


用例
---------


.. code:: golang

    package main

    import (
        "fmt"
        "github.com/yuanbenio/go-base36"
    )

    func main(){
        // length 64
        hash := base36.DecodeToHexString("5RN80I4FEE7Z7TDEZEE53P2U9J99R1GI8LM1GNFLFFI6AW5J40")
        fmt.Println(hash)
    }



