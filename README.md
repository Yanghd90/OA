# OA
记录OA系统的二次开发内容
1.修改通过用户管理，新增系统用户的程序
    a，2013版，新增用户时，在表单中填写的用户名即保存到user表、user_ext表的USER_ID
    b，2015版，表单中填写的用户名保存到了user表、user_ext表的BYNAME，USER_ID取用UID（自增）的值
    c，这样以来，与其他二次开发（考勤机对接，数字化校园系统等）的内容冲突
    d，所以加以修改

2.修改通过人事档案管理，新增系统用户的程序webroot\general\hr\manage\staff_info\add.php
    a，同第一个问题
    
3.
