CREATE DATABASE /*!32312 IF NOT EXISTS*/`CRUD` /*!40100 DEFAULT CHARACTER SET utf8 */;

USE `CRUD`;

/*Table structure for table `Board` */

DROP TABLE IF EXISTS `Board`;

CREATE TABLE `Board` (
  `BoardNo` int(14) unsigned NOT NULL AUTO_INCREMENT COMMENT '게시글번호',
  `UserNo` int(14) NOT NULL COMMENT '회원번호',
  `UserName` varchar(30) NOT NULL COMMENT '회원이름',
  `Subject` varchar(200) NOT NULL COMMENT '제목',
  `Contents` text NOT NULL COMMENT '내용',
  `CreateDatetime` datetime NOT NULL COMMENT '생성일시',
  PRIMARY KEY (`BoardNo`)
) ENGINE=InnoDB DEFAULT CHARSET=utf8 COMMENT='게시글 테이블';

/*Table structure for table `Users` */

DROP TABLE IF EXISTS `Users`;

CREATE TABLE `Users` (
  `UserNo` int(14) unsigned NOT NULL AUTO_INCREMENT COMMENT '회원번호',
  `UserId` varchar(30) COLLATE utf8_unicode_ci NOT NULL COMMENT '유저아이디',
  `UserName` varchar(30) COLLATE utf8_unicode_ci NOT NULL COMMENT '유저이름',
  `UserPw` varchar(200) COLLATE utf8_unicode_ci NOT NULL COMMENT '비밀번호',
  `IsUse` bit(1) NOT NULL DEFAULT b'1' COMMENT '사용여부',
  `CreateDatetime` datetime NOT NULL COMMENT '생성일시',
  PRIMARY KEY (`UserNo`)
) ENGINE=InnoDB DEFAULT CHARSET=utf8 COLLATE=utf8_unicode_ci COMMENT='회원정보 테이블';
