# <img src="https://objectpartners.com/wp-content/uploads/2015/02/mongodb-logo.png" style="position: relative; top: 5px;" height="80" /> 

## Install MongoDB 
<code>E:\MongoDB\Server\3.0\bin</code>
https://www.mongodb.com/

## Install MongoDB Compass



## How to configure MongoDB with localhost
* Download .dll file and paste here. I:\xampp\php\ext
* Open php.ini file and find this content <code>; Windows Extensions</code> add this line <code>extension=php_mongodb.dll</code>
* Open browers and visit this link <code>localhost/dashboard/phpinfo.php</code>
* If found <b>MongoDB</b> support its running successfully


## How to connect MongoDB with localhost
* Open <code>E:\MongoDB\Server\3.0\bin</code> open command line
* Type <code>mongod --dbpath E:/MongoDB/data</code> press enter
* Open new cmd and type <code>mongo</code>