import io
#ASKS USER HOW MANY QUESTIONS ARE IN TEST/REVIEW
listsize = input("How many questions are in your test?: ")

#VARIABLES
size1 = int(listsize)
count = 0
count2 = []
userdatalist = []
filename = ['TestFile']
z = " "
#OPENS FILE
Test = open('AnswerKey.txt', 'w')

#WHILE LOOP TO OBTAIN DATA FROM USER
while (count < size1):  
    count = count+1
    userdata = input("Enter Correct Answer for Question %d:" % count)
    count2.append(count) 
    userdatalist.append(userdata)
#ITERATES THROUGH FILE	
for item in userdatalist:
	Test.write("%s\n" % item)
#FILE HAS BEEN WRITTEN 
print("*********Data has been written to AnswerKey.txt****************")
