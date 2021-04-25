# Python-beginner
Learning Python for the first time
>>>print("Welcome to my python, I am a python beginner, I literally just started it today, and I got learning materials from internet, but i donnot actually know how the code below works, if you donnot mind please teach me how to code and explain why, and I will listen attentively to your teaching and study hard, thank you")

Temperature Convert
val = input("Please enter the temperatures with symbol(e.g: 32C): ")
if val[-1] in ['C','c']:
    f = 1.8 * float(val[0:-1] + 32
    print("after transfered: %.2fF"%f)
elif val[-1] in ['F','f']:
    c = (float(val[0:-1]) - 32) / 1.8
    print("after transfered: %.2fC"%c)
else:
    print("error")
