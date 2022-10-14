def read(a,n):
    for i in range (n):
        b=int(input("enter the value :"))
        a.append(b)
def disp(a,n):
    #for i in range (n):
        print(a)
def average(a,n):
    sum=0
    count=0
    for i in range(n):
        if(a[i]>=0):
            sum=sum+a[i]
            count=count+1
    ave=sum/count
    print("The average is {}".format(ave))
    print("The absent number is {}".format(n-count))
def min_max(a,n):
    min1=a[0]
    max1=a[0]
    for i in range (n):
        if(a[i]>max1):
            max1=a[i]
        if(a[i]<min1):
            min1=a[i]
    print("max number is {}".format(max1))
    print("min number is {}".format(min1))
def highfreq(a,n):
  
    for i in range(n):
        b=0
        for j in range (n):
            if a[i]==a[j]:
               b=b+1
        count.append(b)
    print(count)
    max=0
    for i in count:
        if max<a[i]:
         max=a[i]
    print("The highest frequency  is of",a[i])
count=[]
a=[]
n=int(input("enter the number  :"))
read(a,n)
disp(a,n)
average(a,n)
min_max(a,n)
highfreq(a,n)
