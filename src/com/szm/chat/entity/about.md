业务实体设计
用户:用户id、用户名、密码、昵称、邮箱、性别、权限;
    用户类：User

消息短信：短信id、短信发送者、短信接收者、短信内容、发送时间
		短信类：Message

在线用户：记录id(主键)、登录用户、登录ip、登录时间、登录状态
		在线用户类：OnLineUser

聊天记录：记录id(主键)，发送用户名、接收用户名、聊天内容、发送时间
		聊天记录类：History