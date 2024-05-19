# Python3
3 rd look for Python
rec1_length=int(input('What is the lenght of first rectangle?')) 
rec1_width=int(input('What is the width of first rectangle?'))
rec2_length=int(input('What is the lenght of secondrectangle?'))
rec2_width=int(input('What is the width of secondrectangle?'))
area1=rec1_length*rec1_width
area2=rec2_length*rec2_width
if area1>area2:
   print('Area 1 is greater than area 2.')
elif area2>area1:
   print('Area 2 is greater than area 1.')
else:
   print('Area 1 is equal to area 2.')
