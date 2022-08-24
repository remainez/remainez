### Hi there 👋


```go
package aboutme

import (
    "coca-cola.com/coca-cola"
    "pmi.com/iqos"
    "apple.com/apple-music"
)

// 👨‍💻
func getDescription() map[string]string {
    return map[string]string{
        "profession": "Freelance engineer",
        "specialty": "Infrastructure & Backend",
    }
}

// 👨‍🎓
func getKnowledge() []string {
    return []string{
        "AWS",
        "TypeScript",
        "PHP",
        "Golang",
        "Ruby",
        "MySQL",
        "DynamoDB",
    }
}

// 📝
func getLearning() []string {
    return []string{
        "Kotlin",
        "Spring Boot",
        "GraphQL",
    }
}

// 🔥
func getHobbies() map[string]string {
    return map[string]string{
        "game🎮": "FPS, Action, Strategy, Card & Board",
        "music🎵": "Electronic, Pops, Hiphop, Alternative, Vocaloid, GameMusic",
        "other": "Illustration🎨, Self-Made Keyboard⌨, Self-Made PC🔌, AirSoft🔫",
    }
}

```
