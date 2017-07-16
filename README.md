# Wordmachine
This is a program based on Python3.6 and released using Cx_freeze.
To use it:
1#Adding dictionaries:
  Of course you can add your own dictionaries by putting your dictionary under the same directory of wordmachine.exe.
  Notice!!! The dictionary should be UTF-8 without BOM. 
  The dictionary should be like this:
'''
  apple;苹果
  orange;橘子，橙子
'''
  The meanings in Chinese can be seperated by anything but the  semicolon(;), for the program use it to seperate English and Chinese.
  This is because the program only search your input in the whole Chinese String, if the substring is founded then you input shall be
  considered correct. So if you want, you can even use nothing, though i won't recommend you to do that.
  
2#About saving:
  The program has a simple saving function, so don't panic if you close the program before you complete a list(or the program crash
  because of a bug). However this does not work in mistakes book mode.
  
3#The mistakes book:
  This program will add the word item into the file once you make a mistake, and it won't be reduplicated.
  When you enter the mistakes book(MODE 4), your mistakes will be tested in EN-CN or CN-EN randomly, since you should have already
  completely mastered them
  
So have fun then!
