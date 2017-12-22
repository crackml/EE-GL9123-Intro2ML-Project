# EE-GL9123-Intro2ML-Project
# Identification of Verification Code of Zhihu

This project aims to identify the verification code of website www.zhihu.com (知乎，Zhihu). It is a Q&A forum similar to [Quora](www.quora.com), which is a platform where people could interact with others on topics that they are interested in. To verify that you are not a ”robot”, there is a verification before log-in or registration. This verification code contains seven randomly selected Chinese characters, all of them are rotated, zoomed, and or placed one by one by irregular spaces. Some characters are rotated by about 150 to 210 degrees so that they are "headstand". Zhihu requires you to exiactly pick up all headstand characters to pass the verification. 

You can fetch a picture of verification code by this link https://www.zhihu.com/captcha.gif?&lang=cn

For example, the following verification code is one captured from Zhihu.

![image](https://github.com/crackml/EE-GL9123-Intro2ML-Project/blob/master/captcha010.png)

Fig.1 one verification code captured from Zhihu

The seven Chinese characters on Fig.1 are “游”,“舀”,“竿”,“侵”,“图”,“民”,“茁” respectively, among which, “舀” is headstand. Correctly select this character, then you can pass the verification.
