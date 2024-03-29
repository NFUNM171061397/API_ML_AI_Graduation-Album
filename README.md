# 智能毕业纪念册PRD

| 发布时间 | 2019-12-05 |
| ------  | -------:   |
| 项目名称 |  智能毕业纪念册  |
| 项目状态 |  进行中     |
| 项目负责人 |  张柳燕    |

### 价值主张设计（一句话版本）
智能毕业纪念册APP拥有人脸识别、语音识别、普通ip定位以及地标识别等功能，解决了纸质相册过于单一且难以长久保存，容易丢失，毕业生未来可能与同学失去联系等问题，是一款可以可以用来回忆和联系同学的软件。

### 价值主张设计（一分钟版本）
#### 加值宣言
“智能毕业纪念册”是一款专门为即将毕业的学生/毕业生设计的纪念相册APP。以往的纸质版毕业册不易查看也不方便携带，不便于用户回忆，同时也存在着容易丢失的问题。智能毕业纪念册app由此而产品，用户只需一部手机或一台设备，即可随时随地的查阅相册，回忆过去，联系同学。不仅如此，APP设置了语音留言板、同学找寻等功能，可以让用户快速查找到同学的联系方式，知道同学的所处位置等，不会因毕业而丢失联系，语音留言版也可以让用户发现更多更有趣的回忆。

#### 核心价值（最小可行性产品）
* 采用人脸识别技术，通过监测用户上传/拍摄的照片，返回同学的联系方式与个人信息。
* 用户在选择语音上传时，可以通过语音识别API将其识别成文本输出。
* 使用普通IP定位，用户可以查看/分享自己的定位，也可查看特人分享的定位。

#### 核心价值与用户痛点
* 传统纸质版相册不易查看也不方便携带，不便于用户回忆，同时也存在着容易丢失的问题。
* 传统纸质版相册只能查看静态图片，无法记录声音，无法实时互动。
* 传统纸质版相册只有少量相册，不足够回忆与纪念。
* 传统纸质版相册无法更新同学联系方式或所处位置，可能会导致毕业生失去联系。

#### 人工智能概率性与用户痛点
* 用户上传/拍摄的图片，像素过低，清晰度过低，无法进行人脸识别。
* 用户上传/拍摄的图片中有过多的人物，无法进行人脸识别。
* 用户上传/拍摄的图片中没有完整的地标，无法进行地标识别。
* 用户上传的语音音量太大/太小/环境过于嘈杂，无法进行语音识别。

#### 需求列表与人工智能API加值
| 用户案例| 运用技术 |重要程度 |
| ------  | -------:   |  ------|
| 用户想快速查看到更多与自己相关的照片| 人脸识别 | 重要|
| 用户想要上传分享自己的语音文字及文字|  语音识别  |重要|
| 用户想要查看他人的ip定位|  普通ip定位  |重要|
| 用户想要知道他人上传照片中的地标|  地标识别  |次重要|
