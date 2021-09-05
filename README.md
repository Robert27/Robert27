## Hi there! 👋

```python
class AboutMe:
    def __init__(self):
        self.name = 'Robert'
        self.role = 'Computer Science Student'
        self.degree = 'Artificial Intelligence'
        self.languages = [
            'Python',
            'Java',
            'Swift',
            'Javascript',
        ]
        self.databases = [
            'PostgreSQL',
            'SQLite',
            'MongoDB'
        ]
        self.languages.append('SQL')

    def say_hi(self):
        print(
            f'• {self.name}\n• {self.role} - {self.degree}\n'
            f'• Languages: {", ".join(self.languages)}\n• Databases: {", ".join(self.databases)}'
        )


me = AboutMe()
me.say_hi()

```
