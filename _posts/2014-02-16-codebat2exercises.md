---
layout: post 
author: ethan
title: Codebat 2 Exercises
date: 2014-02-16
---

Okay, so I finished all but one of the exercises. I couldn't seem to figure out how to do one of them. I'll go on to discuss it later on. 

##Logic-2 close_far

This one gave me a little trouble. I had to stare down the question for a little bit to really understand what it was really saying. Once I figured out what it was asking, then it wasn't too hard. I just had to figure out how to make sure I got the correct output. I kept confusing myself. 

```
def close_far(a, b, c):
   if abs (b - a) <= 1:
      close = b
   elif abs (c - a) <= 1: 
      close = c
   else:
      return false
   if (close == b) and (abs(c-a) >= 2) and (abs(c-b)>=2):
      return True
   elif (close == c) and (abs(b-a) >= 2) and (abs(b-c)>=2):
      return True
   else:
      return False
```

##String-2 count_code

This one was a little tricky too. I had to go back and do some digging to be able to get this one. I couldn't remember how to get it to only read certain parts of a string and disregard others. Once I remembered how to do that, then it was easy. I thought it was cool that it could omit just one letter of the string and keep the rest. 

```
def count_code(str):
   count = 0
   for i in range(len(str)-3):
      if str[i:i+2] == 'co' and str[i+3] == 'e':
         count += 1
   return count
```

##List-2 has22

Me and arrays never get along. I can never figure them out. But this one wasn't too bad...I don't think? I don't know. But according to the website, I got it right. So there's that. I had to go look up some stuff in order to get it to do what I wanted it to. I didn't remember any of the range stuff. I am also very bad at math...so that doesn't make it easy either. 

```
def has22(nums):
    for x in range(len(nums)-1):
        if (nums[x] == 2) and (nums[x+1] == 2):
            return True
    return False
```

#Pictures

here are the screenshots of the completed exercises. 

![Imgur](http://i.imgur.com/HAuy5Aa.png)

##Reflection

I couldn't figure out Logic-2, Make chocolate to save my life. I don't know what it was about it. I looked at other problems, I googled for help. I couldn't do it. I think it could be due to some bad wording in the question. I just didn't understand it. Not at all. Other than that, though, I didn't really have any problems. 

So, yeah, here it is. 

babykav out. 
