num = 1
list_a=[]
list_b=[]
list_c=[]
list_d=[]
while num<=2:
    if num==1:
        a = input("请输入内容:")
        list_a=a.split(",")
        for i in list_a:
            i = int(i)
            list_b.append(i)
            # print(list_b)
    else:
        b = input("请输入内容:")
        list_c=b.split(",")
        for i in list_c:
            i = int(i)
            list_d.append(i)
            # print(list_d)
    list_e = list_b + list_d
    num=num+1
u=list(set(list_e))
u.sort()
打印（u）
