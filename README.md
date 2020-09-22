<a href="https://github.com/aaronlyy">
  <img align="center" src="https://github-readme-stats.vercel.app/api?username=aaronlyy&show_icons=true&include_all_commits=true&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515" alt="Dropouts's stats" />
</a>

```
                                                                          $$\                     
                                                                          $$ |                    
                         $$$$$$\   $$$$$$\   $$$$$$\   $$$$$$\  $$$$$$$\  $$ |$$\   $$\ $$\   $$\ 
                         \____$$\  \____$$\ $$  __$$\ $$  __$$\ $$  __$$\ $$ |$$ |  $$ |$$ |  $$ |
                         $$$$$$$ | $$$$$$$ |$$ |  \__|$$ /  $$ |$$ |  $$ |$$ |$$ |  $$ |$$ |  $$ |
                        $$  __$$ |$$  __$$ |$$ |      $$ |  $$ |$$ |  $$ |$$ |$$ |  $$ |$$ |  $$ |
                        \$$$$$$$ |\$$$$$$$ |$$ |      \$$$$$$  |$$ |  $$ |$$ |\$$$$$$$ |\$$$$$$$ |
                         \_______| \_______|\__|       \______/ \__|  \__|\__| \____$$ | \____$$ |
                                                                              $$\   $$ |$$\   $$ |
                                                                              \$$$$$$  |\$$$$$$  |
                                                                               \______/  \______/ 
```
<!--
```python
class Aaronlyy():

    def __init__(self):
        self.general = {
            "name": "Aaron Levi",
            "nick": "aaronlyy",
            "age": 18,
            "location": "Germany"
            }

        self.social = {
            "instagram": "aaronleviii",
            "twitter": "levizepam",
            "discord": "aaronlyy#0001",
            "spotify": "aaronlyy",
            "website": "aaronlyy.me"
            }
        
        self.info = {**self.general, **self.social}

    def __getattr__(self, attr):
        if attr in self.info:
            return self.info[attr]
        else:
            return None

    def iter(self):
      return self.info.items()

me = Aaronlyy()

print(f"Hello there, my name is {me.name}, im {me.age} years old and from {me.location}.\n
        You find my full info and social medias down below.\n")

for k, v in me.iter():
  print(f"{' '.join([c for c in k]).upper()}: {v}")
```
-->
