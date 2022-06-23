
 <div align="center">  
  
![header](https://capsule-render.vercel.app/api?type=Waving&color=timeGradient&height=200&section=header&text=Wellcome&fontSize=70&fontAlign=78&fontAlignY=28)  
  </div>
  
 
``` python
class AboutMe:

    def __init__(self):
        self.name     = "SukJae Kim"
        self.language = "Python"
        self.company  = None
        self._skills()

    def _skills(self):
        """ done that even once """

        self.Data     = ["Pandas", "Pytorch", "Keras-tensorflow", "Scikit-learn", "matplotlib", "plotly", "numpy"]
        self.Back_end = ["Mysql", "Mongodb", "PostgreSQL", "Django", "FLask", "Docker", "Gunicorn", "Nginx",
                        ["AWS-EC2", "AWS-lambda", "AWS-S3", "AWS-kinesis"]]
        self.ETC      = ["Git", "Postman", "Swagger"]
        

    def __call__(self):           
        if not self.company:
            return print(f"\
                        I was learned about DA, DE, NLP, Back-end currntly interesting about DE, Back-end \n \
                        i have done this skills even once                                                 \n \
                        Data skills {self.Data}                                                           \n \
                        Back_end skills {self.Back_end}                                                   \n \
                        ETC skills {self.ETC}                                                             \n \
                        please input ur company after this message :)")
            
        else :
            return print(f"I'm already from {ksj.company} even u don't want anymore \n thank u for ur kind :)")



ksj = AboutMe()
ksj()
ksj.company = input()
ksj()

```
<div align="center">  
  
![Cloudblack's github stats](https://github-readme-stats.vercel.app/api?username=Cloudblack&show_icons=true&theme=cobalt&count_private=true)  

<!-- ![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Cloudblack&theme=cobalt&hide=jupyter%20notebook&show_icons=true&custom_title=Top_Language)
 -->
</div>
