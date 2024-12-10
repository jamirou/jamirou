## <p align = "Left">>. Hi, I'm Jamiro </p> #

```kotlin
class AboutMe {
    val name = "Jamiro"
    val role = "Android Developer 🚀"
    val goals = listOf("Master Jetpack Compose", "Contribute to open-source projects", "Figure out how to fix Gradle errors on time")
    val hobbies = listOf("Mobile development", "Learning random stuff", "Playing the bass like I'm in a rock band")
    val currentLearning = "Deciphering the mysteries of Android, Kotlin, and how the Android lifecycle works on Mondays"
    val contactInfo = "Reach me at: devjamiro@gmail.com (no, I won't fix your bugs for free)"
    
    fun introduceYourself() {
        println(
            """
            |Hey there! 👋 I'm $name, an $role.
            |My goals include:
            | - ${goals.joinToString("\n - ")}
            |Hobbies? Glad you asked:
            | - ${hobbies.joinToString("\n - ")}
            |Currently, I'm diving deep into: $currentLearning
            |Need help or just want to say hi? Contact me at: $contactInfo
            """.trimMargin()
        )
    }
}

fun main() {
    val aboutMe = AboutMe()
    aboutMe.introduceYourself()
}
```

<h3>Stack?: </h3>

[![My Skills](https://skillicons.dev/icons?i=kotlin,java,flutter,dart,firebase,idea,androidstudio,bash,gradle,linux,mysql,postgres,,,arduino,py,react,sublime,postman,raspberrypi,git,docker,&perline=12)](https://skillicons.dev)
--------------------------------------------

