# GoCRUD
GoLang CRUD example with MySQL

### Database
create a database named 'goblog'

creat a table named employee.

DROP TABLE IF EXISTS `employee`;
CREATE TABLE `employee` (
  `id` int(6) unsigned NOT NULL AUTO_INCREMENT,
  `name` varchar(30) NOT NULL,
  `city` varchar(30) NOT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=1 DEFAULT CHARSET=latin1;

### How to run

- clone or download the project
- Run the commands line :
    cd path to project folder
- Run the following command: go run main.go
- Load http://localhost:8081/ on your browser
