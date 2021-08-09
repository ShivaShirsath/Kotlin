# Kotlin
```kotlin
package src

internal object Main {
    @kotlin.jvm.JvmStatic
    fun main(args: Array<String>) {
        print("Enter your name : ")
        println("Hello " + java.util.Scanner(System.`in`).next() + " !")
    }
}
```
```kotlin
Enter your name : Shiva
Hello Shiva !
```
