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
        print(f"Hello, I'm {self.name}! I am a {self.status} of {self.studied} and currently in progress doing {self.current_learning} :)")

me = AboutMe()
me.welcome()
```
