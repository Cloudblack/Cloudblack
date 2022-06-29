
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
                        please input ur company after this message :) ")
            
        else :
            return print(f"\
                        I'm already from {self.company} even u don't want anymore                        \n \ 
                        thank u for ur kind :) ")



ksj = AboutMe()
ksj()
ksj.company = input()
ksj()

```

<details>
<summary>오프라인 작업 환경</summary>
<div markdown="1">       
<br>

- 2021년 8월, 부트캠프를 시작하고 약 한달 하루종일 컴퓨터앞에 앉아   
구부정한 허리, 앞으로 튀어나온 목, 뭉친 어깨, 땀으로 흥건한 등, 고통스러운 손목과 손가락 등  
동기들은 물론, 나 또한 앞으로 반년을 생각하니 아비규환 그 자체였다  
불굴의 의지로 극복 할 수도있겠지만 차라리 작업 환경을 개선하고 그 의지는 좋은곳에 쓰기로했다

<br>

<img src="https://user-images.githubusercontent.com/86823305/176380379-5fd8c674-bf8b-4073-a785-ff9c9f183c4b.jpg"  height="150"/>

- 하나의 모니터로는 너무 답답해서 추가로 모니터를 구매했다 27, 29인치이다

<img src="https://user-images.githubusercontent.com/86823305/176380415-2567fac6-ec38-4d7e-9eb4-cd248b904340.jpg"  height="150"/>

- 키보드를 칠때 양손이 모여 손목이 꺾이게되어 반반 키보드를 찾아보니 인체공학용으로 엄청 비쌌다 
- 그래서 게임용 왼쪽짜리 키보드를 만원대에 사서 왼손용으로 쓰고있다

<img src="https://user-images.githubusercontent.com/86823305/176380467-aa0f00b4-be1b-4348-a9b6-9b2d7d456956.jpg"  height="150"/>  

- 10년을 함께한 키보드 현재는 오른손용으로 쓰고있다
- 키보드 두개를 양쪽으로 넓게 쓰는게 익숙해져서 일반 키보드 하나를 사용하면 오타가 엄청나게 나온다 

<img src="https://user-images.githubusercontent.com/86823305/176380407-2cc10941-2f7b-40ae-9ca7-0a570e528f79.jpg"  height="200"/>  

- 무선 마우스와 함께 선물받은 키보드
- 키씹힘 문제가있어 자가 수리 예정
- 매크로 용으로만 사용하고 원래 키보드를 주로 사용한다
- 공중에 뜬상태로 키보드를 치면 불편해 준비한게 키보드 아래 검은색 손목 쿠션이다

<img src="https://user-images.githubusercontent.com/86823305/176380431-67076483-5aa8-4fc6-b0db-45f8ac7b0b41.jpg"  height="150"/>  

- 오른쪽이 기존에 사용하던 마우스로 오래쓰면 불편함이있다
- 중간이 손목에 좋다고해서 산 버티컬 마우스로 다좋은데 클릭압이 강해 불편하다
- 왼쪽은 무선마우스로 가볍고 클릭압이 낮고 매크로를 등록할 수 있어서 요새 사용중이다


<img src="https://user-images.githubusercontent.com/86823305/176380437-79efb590-6e77-4c7b-981d-4248106d8061.jpg"  height="150"/>  

- 팔걸이에 팔을 걸치는걸 좋아하는데 의자 팔걸이가 책상에 부딪혀 팔을 쭉 뻗고 사용하다보니 불편함을 느꼈다
- 의자 팔걸이를 뗴어버리고 책상에 고정용 팔걸이를 달았다 
- 현재는 왼손이 사용하는 팔걸이로 반쪽짜리 키보드를 놓고 사용중이다


<img src="https://user-images.githubusercontent.com/86823305/176380444-90f464f7-ab5e-49aa-b1b2-515a9e66c091.jpg"  height="150"/>  

- 오른손용 팔걸이 자세히보면 왼쪽과 다르게 손목 쿠션이 달려있다


<img src="https://user-images.githubusercontent.com/86823305/176380450-2d37da2e-6fba-4b2f-a7dc-90ab04bc2562.jpg"  height="300"/>  

- SK 와이번즈 의자로 야구를 좋아해서가 아니고 구단이 사라져서 헐값에 올라와서 구매했다
- 의자덕분에 오래앉아있어도 편하나 가죽 재질로 땀이차게되어 통풍 시트를 설치했다
- 차에있는 목받침대를 빼와서 사용하고있다 너무 오래써서 뜯어져나가는 모습이다

**쾌-적한 환경(?)을 구축해 효율을 높일 수 있었다**


</div>
</details>

<div align="center">  
  
![Cloudblack's github stats](https://github-readme-stats.vercel.app/api?username=Cloudblack&show_icons=true&theme=cobalt&count_private=true)  

<!-- ![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Cloudblack&theme=cobalt&hide=jupyter%20notebook&show_icons=true&custom_title=Top_Language)
 -->
</div>
