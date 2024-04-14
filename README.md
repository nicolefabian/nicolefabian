[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=15&pause=1000&color=CA5894&random=false&width=429&height=33&lines=git+commit+-m+%22Added+aboutme.py%22)](https://git.io/typing-svg)
```python
class AboutMe:
    def __init__(self):
        self.name = "Nicole Fabian"
        self.status = "Recent Graduate"
        self.studied = "Software and Web Development"
        self.location = "Auckland, New Zealand"
        self.languages_spoken = {"Tagalog": "native", "English": "fluent"}
        self.interests = ["Web Development", "UI/UX Design"]
        self.current_learning = "Phase 1 of MSA"

  
    def welcome(self):
        message = (f"Hello, I'm {self.name}! " +
          f"I am a {self.status} of {self.studied} and currently in progress doing {self.current_learning}. " +
          "Thank you for visiting :)"
        )
        print(message)

me = AboutMe()
me.welcome()
```
