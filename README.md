# LongChainKBQA

#### 项目结构
+ config.py：配置文件,配置llm模型和文本向量化模型
+ document.py：文本拆分和文本向量化
+ llm.py：大语言模型加载
+ chainKBQA.py：利用文本向量化搜索和大语言模型进行知识库问答


#### 结果如下：
> load llm model 
> load documents
> 
> 大模型自己回答的结果
> 
> 迪丽热巴的作品包括：
> 《三生三世十里桃花》、
> 《三生三世枕上书》、《三生三世枕上书之长生诀》、
> 《三生三世枕上书之长生诀之长生诀之长生诀之长生决》、
> 《三生三世枕上书之长生诀》等。
> 
> 大模型+知识库后回答的结果
> 
> {
> 	 'query': '迪丽热巴的作品有什么',
> 	 'result': '迪丽热巴的作品包括：《阿娜尔罕》、《逆光之恋》、《克拉恋人》、《漂亮的李慧珍》、《三生三世十里桃花》、《金鹰女神》等。', 
>  
>  
> 	'source_documents': [Document(page_content='2013年，迪丽热巴因主演个人首部电视剧《阿娜尔罕》而出道 [1] 。
> 	2014年，主演奇幻剧《逆光之恋》。
> 	2015年，凭借爱情剧《克拉恋人》赢得高人气，并获得国剧盛典最受欢迎新人女演员奖 [168] 。
> 	2016年，主演现代剧《麻辣变形计》 [2] ；同年，主演都市爱情励志喜剧《漂亮的李慧珍》，还凭借喜剧片《傲娇与偏见》获得中英电影节最佳新人奖 [3] 。
> 	2017年，凭借玄幻剧《三生三世十里桃花》获得白玉兰奖最佳女配角提名 [4] 。2018年，迪丽热巴成为了金鹰电视艺术节的第七位“金鹰女神” [5] ，
> 	并获得了第29届中国电视金鹰奖观众喜爱的女演员、第12届中国金鹰电视艺术节最具人气女演员两项殊荣 [6] 。', metadata={'source': 'source/txt/dilireba.txt'})]
> }
