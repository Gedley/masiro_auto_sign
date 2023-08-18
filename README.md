# masiro_auto_sign

真白萌自动签到、祈愿、点赞

账号和密码放在login.txt，账号和密码放在同一行，中间用空格隔开。

例如：

username1    password1

username2    password2


index.py中days()函数中的日期为开始签到的日期，第一次使用时建议修改为对应时间。

def days():

    x = datetime.date.today()

    y = datetime.date(2022, 5, 31)

    z = (x - y).days

    return z
