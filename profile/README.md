
![Screenshot 2024-07-29 at 14 10 53](https://github.com/user-attachments/assets/2d732df4-34ce-4603-92e9-029a07b3d2df)



## Bgolearn [HomePage](http://bgolearn.caobin.asia/) 

[View package usage statistics / download counts](https://www.pepy.tech/projects/Bgolearn)
 ![PyPI Downloads](https://static.pepy.tech/badge/bgolearn)
### A Bayesian global optimization package for material design ｜ Adaptive Learning | Active Learning

### Code tutorial : [BiliBili](https://www.bilibili.com/video/BV1LTtLeaEZp/?spm_id_from=333.337.search-card.all.click)

### Repos
+ [Bgolearn](https://github.com/Bin-Cao/Bgolearn) : The Source Code of Bgolearn
+ [MultiBgolearn](https://github.com/Bin-Cao/MultiBgolearn): Multi-Objective Bayesian Global Optimization for Materials Design
+ [BgoFace](https://github.com/Bgolearn/BgoFace) : User interface of the Bgolearn platform
+ [CodeDemo](https://github.com/Bgolearn/CodeDemo) : Provides code demonstrations and data to illustrate the application of Bgolearn
+ [Document](https://bgolearn.netlify.app/) : The Document of Bgolearn
+ [MLMD](https://github.com/Jiaxuan-Ma/MLMD) : A programming-free AI platform to predict and design materials

### Cite
+ Cao, B., Su, T., Yu, S., Li, T., Zhang, T., Zhang, J., ... & Zhang, T. Y. (2024). Active learning accelerates the discovery of high strength and high ductility lead-free solder alloys. Materials & Design, 241, 112921. https://doi.org/10.1016/j.matdes.2024.112921


### [related  works](https://scholar.google.com/scholar?hl=zh-CN&as_sdt=0%2C5&q=bgolearn&btnG=)



---

### Key Points to Understand:

**Multi-target selection is not the same as multi-target optimization!**

- **Multi-target optimization** considers multiple properties simultaneously in both prediction and utility space. It can be implemented using **MultiBgolearn** in Python.
  
- **Multi-target selection** typically considers two properties independently and then combines them in either the property space or utility space using a Pareto front. A method is constructed to select one solution from the points on the Pareto front. This can be implemented using **BgoKit** in Python.


**Note:** We are not claiming that one approach is better than the other; they are fundamentally different. Multi-target optimization truly accounts for the interdependencies between properties, whereas multi-target selection treats properties more independently.





If you are still unclear about the differences, please refer to the [video](https://m.bilibili.com/video/BV1LTtLeaEZp?buvid=Y345CE3557236F9745C19B291052E1114B47&is_story_h5=false&mid=cKE7LXHZdUdBetZbd%2FNVln8FTQ%2FSZMtL1rElX6M3iMo%3D&plat_id=240&share_from=ugc&share_medium=iphone&share_plat=ios&share_source=WEIXIN&share_tag=s_i&timestamp=1726650391&unique_k=fyJEJqG&up_id=3546615870654962) for further explanation.
