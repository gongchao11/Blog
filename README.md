# Blog
仿CSDN技术论坛

本项目是基于Spring，MyBatis的项目。数据库是MySQL数据库，由于论坛业务是读多写少，对事物要求较低，所以MySQL存储引擎是MyISAM引擎。项目中使用Servlet的Filter技术拦截用户发表的博文信息，过滤掉非法的内容。项目亮点是用进度条实时监控上传文件的进度，监听器是commons-fileupload包中的ProgressListener监听器监控文件，用Ajax调用数据并在前端页面显示进度条。
