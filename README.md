# Welcome

```python
# Class Declaration

class ThiagoNeyE:
  
    def __init__(self):
        """
        Informations about @thiagoneye.
        """
        self.name = 'Thiago Rodrigues'
        self.age = 23
        self.email = 'thiagoney@outlook.com'
        self.formation = 'Mechanical Engineering'
        self.interests = ['Data Science', 'Data Engineering']
        self.skills = {
            'Languages': ['Python', 'MATLAB'],
            'Database': ['SQL', 'MySQL', 'PostgreSQL', 'SQLite', 'NoSQL', 'MongoDB', 'Redis'],
            'DataViz': ['Microsoft Power BI'],
            'Tools': ['Git', 'GitHub'],
            'Others': ['Microsoft Office', 'Microsoft Power Apps', 'LaTeX']
        }

    def learning(self, category: str, new: list):
        """
        Topics in studies.
        """
        if category in self.skills.keys():
            self.skills[category] += new
        else:
            self.skills[category] = new

# Main 

me = thiagoneye()
me.learning('Data Engineering', ['Apache Hop', 'Databricks', 'PySpark', 'NiFi', 'Elasticsearch'])
me.learning('Languages', ['Go'])
```

## GitHub Status

<p align= "center">
  <img height="150" src="https://github-readme-stats.vercel.app/api?username=thiagoneye&theme=react&show_icons=true&include_all_commits=false&hide_border=true" />
  <img height="150" src="https://github-readme-streak-stats.herokuapp.com/?user=thiagoneye&theme=react&hide_border=true&date_format=M%20j%5B%2C%20Y%5D" />
  <img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=thiagoneye&theme=react&hide_border=true&layout=compact" />
</p>

---

Credits: [Rafnix Guzmán](https://github.com/rafnixg/)

<!---
<p align="left"> <img src="https://komarev.com/ghpvc/?username=thiagoneye" alt="thiagoneye" /> </p>

thiagoneye/thiagoneye is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
