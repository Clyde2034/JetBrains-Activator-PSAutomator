# 免责声明
 

本软件和技术仅供学习和研究使用，禁止将其用于商业用途。如果您使用本软件和技术用于商业化而产生任何损失、风险或法律纠纷，作者将不承担任何责任。

作者不保证本软件和技术的完整性、准确性、可靠性、适用性或及时性。使用本软件和技术产生的任何后果，作者将不承担任何责任。

本软件和技术中的任何意见、建议或信息，均不构成作者或作者所在组织的任何形式的保证或担保。

任何人不得对本软件和技术进行反向工程、破解或其他非法行为。任何未经作者或作者所在组织授权的行为，均可能构成侵权或违法行为，一经发现作者将保留追究其法律责任的权利。

使用本软件和技术将被视为您已经完全接受本免责声明的所有条款和条件。如果您不同意本免责声明的任何部分，请勿使用本软件和技术。

2023.09.15 

项目结构在调整,近期使用 请下载 relase 包, 
https://github.com/libin9iOak/ja-netfilter-all/releases

最新Code 

# 搜索微信公众号: 猫头虎技术团队       回复: Code 

2023.08.31

最新支持： 支持2023.2.1 所有版本学习使用
Latest Support: Support for all versions learning and usage as of February 1, 2023.

# 支持2023.2 及以前的所有版本 ，有任何问题, 请联系微信： libin9iOak    QQ群： 777366892
Operation guide: 
    1. add -javaagent:/path/to/ja-netfilter.jar=jetbrains to your vmoptions (manual or auto)
    2. log out of the jb account in the 'Licenses' window
    3. use key on page https://jetbra.in/5d84466e31722979266057664941a71893322460
    4. plugin 'mymap' has been deprecated since version 2022.1
    5. don't care about the activation time, it is a fallback license and will not expire

Enjoy it~

JBR17:
    add these 2 lines to your vmoptions file: (for manual, without any whitespace chars)
    
    --add-opens=java.base/jdk.internal.org.objectweb.asm=ALL-UNNAMED
    --add-opens=java.base/jdk.internal.org.objectweb.asm.tree=ALL-UNNAMED
    



    
# 放在任一位置即可，不一定非要放到上面

~~~

--add-opens=java.base/jdk.internal.org.objectweb.asm=ALL-UNNAMED
--add-opens=java.base/jdk.internal.org.objectweb.asm.tree=ALL-UNNAMED

~~~


# 记得替换为自己机器上地址，务必要写对，写错了IDE就启不来了
~~~
-javaagent:D:\Crack\ja-netfilter-all\ja-netfilter.jar=jetbrains
~~~

NEW: 
    Auto configure vmoptions:
        macOS or Linux: execute "scripts/install.sh"
        Windows: double click to execute "scripts\install-current-user.vbs" (For current user)
                                         "scripts\install-all-users.vbs" (For all users)
                                         
                                         
QQ群： 777366892

微信二维码： 

![微信](https://devpress.csdnimg.cn/6b09a41f054546f1b8480ffa5f15eef1.jpg)




# 注意: 必须将此仓库的所有文件都下载到本地,否则无效.
