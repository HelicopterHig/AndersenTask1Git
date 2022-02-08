@file:JvmName("Main")
@file:Suppress("UNUSED_EXPRESSION")

package com.mr.sudokusolver



fun main(args: Array<String>) {
    var msg = "Hello"
    change(msg)
    print(msg)
    msg = change(msg)
    print(msg)
}

fun change(msg: String): String {
    var msg = msg
    msg = "$msg world!"
    return " java!"
}