# F026 RNN音乐推荐和情感分析可视化系统vue+flask+带爬虫前后端分离系统

>完整项目收费，可联系QQ: 81040295 微信: mmdsj186011 注明从git来的，谢谢！
也可以关注我的B站： 麦麦大数据 https://space.bilibili.com/1583208775
关注B站，有好处！
# F026 🎶vue+flask RNN音乐推荐和可视化系统+带爬虫前后端分离系统
编号：F026
B站视频介绍：
发布后更新视频介绍
## 概要介绍
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/bf9aea9939a74c979519048aaf764bea.png)
###  功能介绍
- 音乐数据的爬取：爬取歌曲、歌手、歌词、评论
- 音乐数据的可视化：数据大屏+多种分析图
    - 歌曲、专辑分析：折线图、柱状图、环图、饼图
    - 数据总览：水滴图
    - 歌手、专辑热度分析：滚动柱状图
    - 歌曲发行：大数据图
    - 版权分析、翻唱分析： 饼图 / 环图
    - 热门歌手分析：折线图
    - 热度分析：散点图
- 交互式音乐推荐： 3种音乐推荐算法【RNN + usercf+itemcf】、通过点击歌曲喜欢来修改用户对歌曲的评分
- 歌词、乐评的词云
- 登录、注册、修改个人信息等
### 系统架构
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/73e3ef41a23649f287e141d454da8789.png)
###  系统功能模块图
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/5186237db36844888b2869576521ed39.png)
### 音乐系统说明文档
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/773f59e3374d4280a2c016e50d57b02b.png)
## 功能展示
### 1 登录&注册
登录和注册在一个界面上，可以切换，背景是一个动图：
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/2613fbbf9bc446c7ac6e71f7f06a86fb.png)
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/1dfa7b25e3ca45bab48c36f26782fcb6.png)
### 2  主页 &  推荐算法 & 用户评分
主页展示最新歌曲，上方一个轮播图，**下面是三种推荐算法**，显示RNN算法推荐4个歌曲：
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/e80bfb14b8484df490ab990fd7cd3a6f.png)
usercf推荐的4首歌曲的卡片,itemcf推荐的4首歌曲的卡片：
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/8a62d08e8133447a8fa389ccdbd982d3.png)
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/9de7dafe31314c4aa3c8344067d92a77.png)
歌曲的喜欢功能，歌曲卡片上有一个爱心可以点击：
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/7bab3d2858fd4eacb7bf78f95280132f.png)
点击乐评情感分析，可以查看抓取到的歌曲评论的情感分析结果：
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/dbfdecc98fc1409db69f8519647b6e15.png)
用户关于歌曲的评分：
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/7f912da1632548179f4c298b9c1a1bd1.png)
### 2+ 情感分析
点击乐评情感分析，还可以查看对于当前歌曲的评论已经使用情感分析模型分析之后的好评/差评结果：

另外系统还有一个单独的情感分析界面，用户可以输入自己的评价进行分析：
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/8481827567de40bcab795529332c6b7d.png)
### 3 歌曲库 & 歌曲搜索
输入关键词可以进行歌曲库的模糊搜索，搜索到的也是歌曲卡片：
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/b3cd3c18d0424a609fc23d53bb120403.png)
### 4 可视化
包含数据大屏+多种分析图
   - 歌曲、专辑分析：折线图、柱状图、环图、饼图
     - 数据总览：水滴图  
    - 歌手、专辑热度分析：滚动柱状图
    ![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/a3fc50932cf84a74b5c4851d43dc7445.png)
    ![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/9d3eb7a38fd242c5979b058514d11d14.png)
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/239c8e6226e14f7aadcfe4122da8ba12.png)

    - 歌曲发行：大数据图
 ![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/b5fb6a3bd500441a916546f5c22e473c.png)     
- 版权分析、翻唱分析： 饼图 / 环图
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/188fd9ffc2c34a9392eeda4b62f96cdc.png)
 - 热门歌手分析：折线图
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/4e32a76859a64371b37f5ebeac795951.png)
 - 热度分析：散点图
  ![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/8a55f4d9488b457cb0b682f6e3c4c505.png)
  - 词云
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/0b383f8ea93543898fdc2cdc56186dd6.png)
### 5 个人设置
可以进行个人信息的设置，头像修改，密码修改等操作：
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/1ecf3b27986c4126b96357cb00c79cb2.png)
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/2428729152384469b9e2442fc9e3b05e.png)
###  6 交互式推荐逻辑
上图描述了一个基于协同过滤的推荐系统的基本工作流程。我们可以将其分解为以下几个步骤：
用户行为数据采集（评分）
N个其他用户的评分: 这是指系统中已经存在的，由大量用户对各种物品（例如电影、商品、歌曲等）进行的评分数据。这些数据是协同过滤算法的基础。
用户（当前用户）: 图中下方有一个“用户”图标，表示正在接受推荐服务的用户。
用户评分输入: 该用户可以对物品进行评分。
心形图标（5分）: 可能表示用户对某个物品的“喜欢”或“收藏”，通常这个行为会被转化为一个最高分，例如5分。
星形图标（0~5分）: 表示用户可以对物品进行更细致的评分，范围从0到5分。
评分数据集: 所有用户的评分数据（包括当前用户和其他N个用户）汇集到“评分数据集”中。这个数据集通常是一个用户-物品评分矩阵，记录了每个用户对每个物品的评分。
协同过滤算法处理
协同过滤: 这是推荐系统的核心部分。协同过滤算法会分析“评分数据集”，找出用户之间（基于用户的协同过滤）或物品之间（基于物品的协同过滤）的相似性。
基于用户的协同过滤: 找到与当前用户口味相似的其他用户，然后推荐这些相似用户喜欢但当前用户尚未接触的物品。
基于物品的协同过滤: 找到与用户喜欢过的物品相似的其他物品，然后推荐这些相似物品。
生成推荐结果
推荐: 协同过滤算法处理完成后，会生成一个推荐列表。这个列表包含了系统认为当前用户可能会感兴趣的物品。
推荐结果反馈给用户
图中的线从“推荐”指向“用户”，表示生成的推荐结果会被展示给当前用户。用户可以根据这些推荐进行消费（观看、购买、听歌等）。
形成闭环与持续优化
用户在接收到推荐后，可能会对推荐的物品产生新的行为（例如点击、购买、或进行新的评分）。这些新的用户行为（评分）又会回到“评分数据集”中。
这个闭环使得系统能够不断收集新的数据，并利用这些数据更新“评分数据集”，从而让协同过滤算法在下一次运行时生成更准确、更个性化的推荐。这是一个持续学习和优化的过程。
总结来说，这个流程图清晰地展示了协同过滤推荐系统如何通过收集和分析用户评分数据，发现用户或物品之间的相似性，进而为用户提供个性化推荐，并通过用户的后续行为不断优化推荐效果。
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/8b55def562224e4397b8f0dddfa647d7.png)
### 7 RNN 推荐算法代码部分
介绍：该代码实现了一个基于循环神经网络（RNN）的音乐推荐系统。通过分析用户的听歌历史，模型能够学习用户的音乐偏好，并推荐符合其口味的歌曲。使用了Keras框架构建RNN模型，处理用户的听歌序列数据，输出推荐的音乐。
实现细节：
数据加载：加载用户的听歌记录数据，并将其转换为适合RNN输入的序列格式。
模型构建：使用Embedding层将音乐ID转换为向量表示，随后通过SimpleRNN层提取序列特征。
推荐生成：通过训练好的模型，输入用户的最近听歌历史，输出下一首可能听的歌曲。。
流程图
![在这里插入图片描述](https://i-blog.csdnimg.cn/direct/487de5f6f231472e983511db094be575.png)

代码部分
```python
from keras.models import Sequential
from keras.layers import Embedding, SimpleRNN, Dense

# 加载用户听歌数据
def load_data():
    user_data = [...]  # 假设这是用户的听歌记录
    return user_data

# 构建RNN模型
def build_model(max_song_id):
    model = Sequential()
    model.add(Embedding(max_song_id, 64))
    model.add(SimpleRNN(64))
    model.add(Dense(max_song_id, activation='softmax'))
    model.compile(optimizer='adam', loss='sparse_categorical_crossentropy')
    return model

# 生成推荐
def generate_recommendation(model, user_history):
    predictions = model.predict(user_history)
    recommended_song = np.argmax(predictions[-1])
    return recommended_song

# 主流程
def main():
    user_history = load_data()
    model = build_model(max_song_id=len(songs))
    model.fit(user_history, epochs=10)
    recommended_song = generate_recommendation(model, user_history)
    print(f"推荐歌曲：{recommended_song}")

if __name__ == "__main__":
    main()

```

