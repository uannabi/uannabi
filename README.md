# 👋 Hey there, I'm a Python Engineer in Data and Analytics.
<p>With vast experience in software engineering, I have developed a deep proficiency in Python, SQL and advanced analytics tools like Tableau, DAQ, D3, Jupyter Notebook, EMR and Sagemaker. This extensive background has seamlessly transitioned into a pioneering Data Science role encompassing Data Engineering, Data Mining, Predictive Analytics, Data Visualization, and Machine Learning. More than just proficiency, my expertise represents a commanding ability to turn complex data sets into compelling narratives, actionable strategies and directions. My journey from software engineering to data science is not merely a shift in skillset but a testament to my capacity to lead and innovate in the ever-evolving digital narrative!</p>

<p align="center">
  <a href="https://www.linkedin.com/in/uannabi/" target="_blank"><img alt="LinkedIn" src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="https://medium.com/@uannabi/" target="_blank"><img alt="Medium" src="https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white"></a>
  <a href="https://www.kaggle.com/zahidunnabi" target="_blank"><img alt="Kaggle" src="https://img.shields.io/badge/Kaggle-035a7d?style=for-the-badge&logo=kaggle&logoColor=white"></a>
  <a href="https://leetcode.com/uannabi/" target="_blank"><img alt="LeetCode" src="https://img.shields.io/badge/LeetCode-000000?style=for-the-badge&logo=LeetCode&logoColor=white"></a>
</p>

## 📌 About Myself

| Who I Am | Education | Skills | Special Qualities |
|----------|-----------|--------|------------------|
| Passion for converting complex data into actionable insights. | Bachelor's Degree in Computer Science & Engineering | Python, R, SQL, Tableau, AWS | Data strategist committed to solving complex business issues. |

| Collaboration & Engagement | Data Specialties |
|----------------------------|-----------------|
| Thrive in team environments, collaborating with Business Analysts, Data Scientists, and Software Engineer | Data Engineering, Predictive Analytics, Data Visualization & Machine Learning |


## 📞 Let's Connect!
Connect on [LinkedIn](https://www.linkedin.com/in/uannabi/).




## 🧰 Tools I've experienced with

[![Python Badge](https://img.shields.io/badge/-Python-black?style=flat&logo=Python&logoColor=white)]()
[![Django Badge](https://img.shields.io/badge/-Django-black?style=flat&logo=Django&logoColor=white)]()
[![Scala Badge](https://img.shields.io/badge/-Scala-black?style=flat&logo=Scala&logoColor=white)]()
[![Pandas Badge](https://img.shields.io/badge/-Pandas-black?style=flat&logo=pandas&logoColor=white)]()
[![Plotly Badge](https://img.shields.io/badge/-Plotly-black?style=flat&logo=Plotly&logoColor=white)]()
[![Anaconda Badge](https://img.shields.io/badge/-Anaconda-black?style=flat&logo=Anaconda&logoColor=white)]()
[![Jupyter Badge](https://img.shields.io/badge/-Jupyter-black?style=flat&logo=Jupyter&logoColor=white&)]()
[![NumPy Badge](https://img.shields.io/badge/-NumPy-black?style=flat&logo=NumPy&logoColor=white)]()
[![Databricks Badge](https://img.shields.io/badge/-Databricks-black?style=flat&logo=Databricks&logoColor=white)]()
[![Metabase Badge](https://img.shields.io/badge/-Metabase-black?style=flat&logo=Metabase&logoColor=white)]()
[![Docker Badge](https://img.shields.io/badge/-Docker-black?style=flat&logo=Docker&logoColor=white)]()
[![Kubernetes Badge](https://img.shields.io/badge/-Kubernetes-black?style=flat&logo=Kubernetes&logoColor=white)]()
[![Git Badge](https://img.shields.io/badge/-Git-black?style=flat&logo=Git&logoColor=white)]()
[![Linux Badge](https://img.shields.io/badge/-Linux-black?style=flat&logo=Linux&logoColor=white)]()
[![Apache Spark Badge](https://img.shields.io/badge/-ApacheCassandra-black?style=flat&logo=ApacheCassandra&logoColor=white)]()
[![Elastic Search Badge](https://img.shields.io/badge/-Elastic-black?style=flat&logo=Elastic&logoColor=white)]()
[![Amazon AWS Badge](https://img.shields.io/badge/-AmazonAWS-black?style=flat&logo=AWS&logoColor=white)]()
[![Google Cloud Badge](https://img.shields.io/badge/-GoogleCloud-black?style=flat&logo=GoogleCloud&logoColor=white)]()
[![Google Colab Badge](https://img.shields.io/badge/-GoogleColab-black?style=flat&logo=GoogleColab&logoColor=white)]()
[![Kaggle Badge](https://img.shields.io/badge/-Kaggle-black?style=flat&logo=Kaggle&logoColor=white)]()
[![Tableau Badge](https://img.shields.io/badge/-Tableau-black?style=flat&logo=Tableau&logoColor=white)]()
<!-- Add more badges here -->

---

``` 
class DataAnalyticsEngineer:
    def __init__(self, name, degree, languages, tools):
        self.name = name
        self.degree = degree
        self.languages = languages
        self.tools = tools
        self.stakeholders = []

    def introduction(self):
        return f"Here I am, {self. name}, fortified by a robust passion for converting complex data into groundbreaking solutions, all backed by the collaborative and versioning strengths of GitHub."

    def educational_background(self):
        return f"I hold a {self. degree} in Computer Science and Engineering."

    def technical_skills(self):
        languages = ', '.join(self.languages)
        tools = ', '.join(self.tools)
        return f"Further enhanced by a mastery of programming languages like {languages}, and proficient use of cutting-edge analytics tools like {tools}."

    def data_capabilities(self):
        return "My background spans data engineering, predictive analytics, data visualization, and machine learning, proving my ability to turn multifaceted data into compelling narratives and actionable insights."

    def unique_selling_points(self):
        return "What sets me apart is my technical acumen and my deep-rooted understanding of leveraging data as a strategic asset for solving complex business issues and driving informed decisions."

    def collaboration(self):
        stakeholders = ', '.join(self.stakeholders)
        return f"Thriving in collaborative settings, I effortlessly engage with stakeholders at every organizational level: {stakeholders}."

    def ambition(self, organization):
        return f" As a proactive self-starter and an invaluable team player, I am eager to deploy my broad data engineering and analytics skills to elevate {organization} to new heights of excellence."

    def add_stakeholder(self, stakeholder):
        self. stakeholders.append(stakeholder)

    def full_profile(self):
        return f"{self.introduction()}\n{self.educational_background()}\n{self.technical_skills()}\n{self.data_capabilities()}\n{self.unique_selling_points()} \n {self.collaboration()}\n{self.ambition('LSEG')}"

if __name__ == "__main__":
    engineer = DataAnalyticsEngineer(name="Zahid Un Nabi", 
                                     degree="Bachelor's Degree", 
                                     languages=['Python', 'SQL'], 
                                     tools=['Tableau'])

    engineer.add_stakeholder('Business Analysts')
    engineer.add_stakeholder('Data Scientists')
    engineer.add_stakeholder('Product Managers')

    print(engineer.full_profile())

```

- 🔭 Currently working at Post Trade London Clearing House [LSEG](https://www.lch.com/)
- 🌱 I’m currently working with a large number of financial data.
- 👯 No collaboration !=```01000101 01001111 01000100```
- 🤔 I’m looking for ```01011111 01011111 01101001 01101110 01101001 01110100 01011111 01011111 ```
- 💬 Ask me about ```01100100 01100001 01110100 01100001 00100000```

<hr>
<p>
<img src="https://github-readme-stats.vercel.app/api?username=uannabi&show_icons=true&count_private=true&theme=merko"width="50%"/><img src="https://github-readme-streak-stats.herokuapp.com?user=uannabi&theme=merko" width="50%" height="10.0%"/> 
</p>




<strong>🔭 Hightlighted repositories  ...</strong>

<a href="https://github.com/uannabi/SparkDataFrame"> <img src="https://github-readme-stats.vercel.app/api/pin/?username=uannabi&repo=SparkDataFrame" width=400> </a> 
<a href="https://github.com/uannabi/DesignPatterns"> <img src="https://github-readme-stats.vercel.app/api/pin/?username=uannabi&repo=DesignPatterns" width=400> </a> 
<hr>

## Try these articles to enrich your knowledge on Medium


#### The first one ABC about Big Data Analysis [5 V for Big Data Analysis ](https://zahid-uan-nabi.medium.com/five-v-of-data-analysis-47868610b6f6) 

#### Build your own data lake [Data Lake on AWS ](https://zahid-uan-nabi.medium.com/data-lakes-on-aws-b598cd9616b2) 

#### ETL explained using aws!  [ETL Techniques ](https://zahid-uan-nabi.medium.com/etl-techniques-5d409597bfe5)

#### First Missing Positive  [Problem-solving](https://uannabi.medium.com/first-missing-positive-bf233f6c180b)
#### Train your personal AI Model [AI Model](https://uannabi.medium.com/train-your-personal-ai-model-892478fd09e6)
<hr>





     
