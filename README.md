1、首先使用anaconda创建一个虚拟环境
2、conda create -n myblog python=3.8(注意python环境至少在3.8以上)
3、Mac系统pip3 install django3.8版本或者3.8以上
4、Django-admin startproject django_blog(创建一个Django的项目)
5、Django-admin startapp django-blog(创建一个Django的APP需要在settings中绑定APP名称)
6、生成模型之后需要迁移Django数据库中 python3 manage.py makemigrations、 python3 manage.py migrate生成新的数据库迁移文件
7、将tools中的数据库文本导入进数据库当中可直接执行或者使用命令行 python3 import_data.py命令行去执行
注意以上步骤均需要在虚拟环境中执行进入虚拟环境的命令:Mac系统:conda activate myname windows系统:activate myname