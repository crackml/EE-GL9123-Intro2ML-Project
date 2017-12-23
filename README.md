# EE-GL9123-Intro2ML-Project: Identification of Verification Code of Zhihu
## Project Target
This project aims to identify the verification code of website www.zhihu.com (知乎，Zhihu). It is a Q&A forum similar to [Quora](www.quora.com), which is a platform where people can interact with others on topics they are interested in. To verify that you are not a "robot", there is a verification when log-in or registration. If your computer is in Chinese environment, this verification code contains seven randomly selected Chinese characters, all of them are rotated, zoomed, and or placed one by one by irregular spaces. Some characters are rotated by about 150 to 210 degrees so that they are "headstand". Zhihu requires you to exactly pick up all headstand characters to pass the verification. 

You can fetch a picture of verification code by this link https://www.zhihu.com/captcha.gif?&lang=cn

For example, the following verification code is one captured from Zhihu.

![image](https://github.com/crackml/EE-GL9123-Intro2ML-Project/blob/master/captcha010.png)

Fig.1 one verification code captured from Zhihu

The seven Chinese characters on Fig.1 are “淤”,“舀”,“竿”,“侵”,“图”,“民”,“茁” respectively, among which, “舀” is headstand. Correctly select this character, then you can pass the verification.

## What does this project consist of 

This project achieved three programs: 
* [Training Sample Generator](https://github.com/crackml/EE-GL9123-Intro2ML-Project/blob/master/Training_Sample_Generator.ipynb), which can randomly generate pictures of a single Chinese character.
* [Scissor](https://github.com/crackml/EE-GL9123-Intro2ML-Project/blob/master/Scissor.ipynb), which can cut the original verification code into single ones.
* [Model](https://github.com/crackml/EE-GL9123-Intro2ML-Project/blob/master/Model.ipynb), which is a Concoluted Neural Network model and judges the single character input. Also, this file contains a demo of identification on ten verification codes.

The data set and model generated during I complete this project are here.

* [data set and model built](https://drive.google.com/open?id=1pGDAJQJRW5dj1jv4YBpdMXLWqXTsbAal). You can download all data set and the trained model from this before you try this project. Or you can begin generating your own data set and model by the three parts above.
