```python
class MyProfile:
    def __init__(self):
        self.name = "Arman Zaher"
        self.education = "BASc in Industrial & Systems Engineering"
        self.university = "University of Toronto"
        self.website = "https://zaherarman.github.io/"
        self.email = "a.zaher@mail.utoronto.ca"
        self.roles = {
            "current": ["Data Science @ UHN"],
            "previously": ["PM @ Bombardier", "Software Engineer @ UTAT"]
        }

    def more_info(self):
        about_me = {
            "current_focus": ["Machine Learning", "Data Science", "Drones"],
            "languages": ["Python", "SQL", "Java", "AMPL", "C++", "JavaScript", "HTML/CSS"],
            "libraries": ["NumPy", "pandas", "Matplotlib", "scikit-learn", "SimPy", "PyTorch", "Plotly", "Dash"],
            "technologies": {
                "cloud": ["AWS (learning)", "Azure (learning)"],
                "tools": ["Git", "Figma", "Docker"]
            }
        }

    def say_hi(self):
        print("Contact me through my email for any inquiries! 👋 ")
```
