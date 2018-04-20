# Purpose
A simple tutorial on how to use @umd.edu to send and receive email.

New students of UMD are initialized with a  `id@terpmail.umd.edu` email, which looks long and un-professional. However, you CAN actually using `id@umd.edu` to send and receive email. The steps I provide below works for me, it you are stuck at certain step, please feel free to tell me at keewang@umd.edu.


# Use `id@umd.edu` as recepient. 使用`id@umd.edu`作为收件地址

Here is already a nice [tutorial](https://umd.service-now.com/itsc?id=kb_article&sys_id=eea6516337a8420041271f9543990ec4) at schoool website. All you need to do is to log-in testudo.umd.edu and change the  email in `contact information` into `id@terpmail.umd.edu`. You will have to wait for at least 2 hours for it to take effect.

只要在 testudo.umd.edu 里面contact information Email改成`id@terpmail.umd.edu`就行了， 每个人就自动有个`id@umd.edu`。 别人发给你的`id@umd.edu`就能自动转到你的terpmail里面。这个大概需要花两个小时才生效。


# Use `id@umd.edu` as sender. 使用id@umd.edu作为发件地址

1. Log-in the terpmail and selet setting on the right. 登录web版本terpmail在右边齿轮选择设置:

    ![Image1 of Tutorial](https://github.com/Kee-Wang/UmdEduMail/blob/master/iamges/1.png)


2. Go to `Accounts`. 进入 `Accounts`

    ![Image1 of Tutorial](https://github.com/Kee-Wang/UmdEduMail/blob/master/iamges/2.png)
    
    
3. Select `Add another email address` under `Send mail as`. 在`Send mail as` 选项里添加 `Add another email address`，注意不是右边的 `edit info` 而是底下的 `add another email address`.下图中我因为已经添加过 `id@umd.edu` 的邮箱所以有显示`id@umd.edu`，但是你第一次设置的时候应该只有`id@terpmail.umd.edu`.

    ![Image3 of Tutorial](https://github.com/Kee-Wang/UmdEduMail/blob/master/iamges/3.png)
  
  
4. 进入后填写你的名字还有想要发件的邮箱名字，也就是id@umd.edu。注意，要把”treat as an alias”去掉。

    ![Image3 of Tutorial](https://github.com/Kee-Wang/UmdEduMail/blob/master/iamges/4.png)
  
  
  
5. 接下来SMTP Server写smtp.gmail.com，port选465，Username还是原来id@terpmail.umd.edu。

注意，这一步可能会有同学无法通过，出现 “Authentication failed. Please check your username/password and Less Secure Apps access for id@terpmail.umd.edu”。如果确认自己的账号密码正确的话，那很可能是因为没有开启Less Secure Apps授权，这个时候点击Less Secure Apps的授权并开启即可。


6. 之后会发验证码给id@terpmail.edu，填入


7. 成功后把 id@umd.edu选择为 default 

    ![Image3 of Tutorial](https://github.com/Kee-Wang/UmdEduMail/blob/master/iamges/5.png)
  
8. 测试成功！(注意，似乎没法用自己的id@umd.edu发给自己的id@umd.edu，所以建议测试发给其他邮箱)

    ![Image3 of Tutorial](https://github.com/Kee-Wang/UmdEduMail/blob/master/iamges/6.png)
  



