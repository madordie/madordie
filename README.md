```swift
#!/usr/bin/env swift
import UIKit

struct Welcome: CustomStringConvertible {
    let blog = "https://madordie.github.io"

    var description: String {
        return """
            - 🌱 [学习使我快乐](\(blog))
            """
    }
}

print(Welcome())
```

---
- 🌱 [学习使我快乐](https://madordie.github.io)


<!--
**madordie/madordie** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
