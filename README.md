
[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=15&pause=1000&color=F78CCF&random=false&width=435&lines=git+add+aboutme.py)](https://git.io/typing-svg)

```python
class AboutMe:
    def __init__(self):
        self.name = "Nicole Fabian"
        self.status = "Recent Graduate"
        self.studied = "Software and Web Development"
        self.location = "Auckland, New Zealand"
        self.languages_spoken = {"Tagalog": "native", "English": "fluent"}
        self.interests = ["Web Development", "UI/UX Design"]
        self.current_learning = "Phase 1 of Microsoft Student Accelerator"

   def welcome(self):
        print(f"Hello, I'm {self.name}! " +
          f"I am a {self.status} of {self.studied} and currently in progress doing {self.current_learning}. " +
          "Thank you for visiting :)")

me = AboutMe()
me.welcome()
```
