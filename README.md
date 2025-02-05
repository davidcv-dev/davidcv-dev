### Hi 👋

```kotlin
class AboutMe {
    val name: String = "David"
    val location: String = "Bolivia"
    val introduction: String = "Hello! I am passionate about mobile app development, specializing in creating efficient and engaging solutions for Android and iOS. I love exploring new technologies, optimizing app performance, and delivering smooth user experiences."
    
    val skillsAndTechnologies: List<String> = listOf(
        "✅ Native development (Swift, Kotlin)",
        "✅ Cross-platform frameworks (Flutter, KMP)",
        "✅ CI/CD for automation and efficient deployment",
        "✅ UI/UX focused on user experience",
        "✅ API integration and cloud services"
    )

    fun aboutMe() {
        println("👤 Name: $name")
        println("📍 Location: $location")
        println("\n$introduction")
        println("\n💡 Skills & Technologies:")
        skillsAndTechnologies.forEach { println(it) }
        println("\nI am always eager to learn and take on new technological challenges. Let’s connect and talk about mobile innovation! 🚀")
    }
}

fun main() {
    val me = AboutMe()
    me.aboutMe()
}
