from datetime import date

class AboutMe():
    def __init__(self):
        self.username = "RoboUzi"
        self.fullname = "***"
        self.pronouns = ("he", "him")
        self.location = "UK"
        self.occupation = "IT, Tech and Computing"
        self.birthday = date(day=01, month=06, year=2001)
        self.age = (date.today()-self.birthday).days/365  # 22 y/o
        self.hobbies = ["Gaming", "Hacking"]
        self.interests = ["IT", "SYS Admin", "Open Source"]

if __name__ == "__main__":
    me = AboutMe()
