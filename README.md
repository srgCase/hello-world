import sys
                
f = open('D:\py\in1.txt', 'r+')


f.close

with open('D:\py\out.txt', 'wb') as bin_file:
    bin_file.write(fstr)
    bin_file.close
    