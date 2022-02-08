package com.mr.sudokusolver

class Button {
    var width: Int = 0
    var height: Int = 0
    // your code goes here

    get() = field

    set(height){
        if (height < 50){
            field = 50
        } else {
            field = height
        }
    }
}  
fun main(args: Array<String>) {
    val b1 = Button()
    b1.height = readLine()!!.toInt()
    b1.width = readLine()!!.toInt()

    println(b1.width+b1.height)
}