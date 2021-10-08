# SAST-SQL-Source

CREATE TABLE `student`  (
   `id` int NOT NULL AUTO_INCREMENT,
   `name` varchar(32) NOT NULL,
   `position` varchar(32) NOT NULL,
   `like` varchar(32) NOT NULL,
   PRIMARY KEY (`id`)
 ) ENGINE = InnoDB CHARACTER SET = utf8;
  
 INSERT INTO `student` ( `id`, `name`, `position`, `like` ) VALUES
  ( 1, '金老板', 'A', '嘉然小姐的狗' ),
  ( 2, '栋栋子', 'A', '夸赞学弟好强啊' ),
  ( 3, '夏桑', 'B', '嘉然我真的好喜欢你' ),
  ( 4, '提莫', 'B', '种蘑菇' ),
  ( 5, '陈三金', 'B', '女装引流' ),
  ( 6, '金坷垃', 'B', '吸收氮磷钾' ),
  ( 7, '祖师爷', 'C', '南邮还是宁最卷' ),
  ( 8, '杂鱼', 'C', '欺负cxy' );
  
  CREATE TABLE `crime`  (
   `punish_id` int NOT NULL AUTO_INCREMENT,
   `punishment` varchar(64) NOT NULL,
   `position` varchar(32) NOT NULL,
   PRIMARY KEY (`push_id`)
 ) ENGINE = InnoDB CHARACTER SET = utf8;
 
 INSERT INTO `crime` VALUES  
 (1, '禁止膜拜 JC', 'A'),
 (2, '不准看 AS', 'B'),
 (3, '打扫大活一个星期', 'C'),
 (4, '自裁', 'A'),
 (5, '拿来吧你', 'B'),
 (6, '宵禁', 'C'),
 (7, '异端教徒审判', 'A');
