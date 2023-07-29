<h1 align="center">Hey there 👋, RoboUzi</h1>
<p align="center">
    <br />

<br />

<br />

    ```py
from datetime import date

class AboutMe():
    def __init__(self):
        self.username = "RoboUzi"
        self.fullname = "*_*_*"
        self.pronouns = ("he", "him")
        self.location = "UK"
        self.occupation = ":missing:"
        self.birthday = date(day=1, month=6, year=2001)
        self.age = (date.today()-self.birthday).days/365  # 22 y/o
        self.hobbies = ["Coding", "Gaming", "Music", "YouTube"]
        self.interests = ["IT", "SYS Admin", "Open Source"]

if __name__ == "__main__":
    me = AboutMe()
```

<br />
