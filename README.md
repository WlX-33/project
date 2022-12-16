# project
数据库文件与修改的代码文件

使用方法：
在数据库中新建数据名为itbtsql，选择字符集为：utf8mb4，排序规则为：utf8mb4_0900_ai_ci

新建完成后打开此数据库，右键选择运行sql文件，并找到此sql文件即可把数据库文件全部导入

目前使用的表解释：

base_info：数据基础信息表，建议使用最后三条数据进行测试，拥有者分别为admin、u1和u2

// company：机构信息表，包括机构id和机构内部码，目前没有有效测试数据

connect：数据SubjectMark、CaseNumber和数据名进行映射，目前没有有效测试数据

insti_cooperation：数据的CaseNumber和该数据的参与机构的映射表，目前数据可以测试

insti_info：机构的机构名和机构id

login：用户注册信息表，目前测试不使用这个表，后面会使用

policy：策略表，policy_id目前为SubjectMark，没有数据

queue_information：队列信息表，有一个映射过程

user_info：用户信息表，目前有测试数据

user_record：用户信息记录对应表，后面会使用

其他中文名称的表：各队列信息
