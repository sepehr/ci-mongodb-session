#CodeIgniter MongoDB Session Library
An extension to CodeIgniter session library with optional MongoDB database backend.

The library extends CodeIgniter's native session
library to use MongoDB as database backend. It's uses V2 branch
of "CodeIgniter MongoDB Active Record Library" by Alex Bilbie as
MongoDB interface. See below for installation instructions.

##Screenshot
![CodeIgniter MongoDB Session Library - Sample session document](https://hostr.co/file/970/hDBmU0TwPWRZ/ci-mongodb-session.png)

##Requirements
* [CodeIgniter MongoDB Active Record Library](https://github.com/alexbilbie/codeigniter-mongodb-library/tree/v2)

##Installation
* Place `MY_Session.php` file in `application/libraries` directory.

* Place `mongodb_session.php` file in `application/config` directory.

* Make sure that you have installed MongoDB Active Record library and your MongoDB
  connection parameters are correctly setup in `application/config/mongodb.php`.

* Make sure that `sess_use_database` directive is set to `TRUE` in
  `application/config/config.php` file.

* Make sure `sess_use_mongodb` is set to `TRUE`. Also set `sess_collection_name` with
  MongoDB session collection name. Both config directives reside in
  `application/config/mongodb_session.php` file.

