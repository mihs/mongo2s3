# mongo2s3

Minimal script for backing up a MongoDB database to Amazon S3. The script sends an email notification when the database is successfully backed up and in case of an error.

Requirements:
* [mongodump](http://docs.mongodb.org/manual/reference/program/mongodump/)
* [sendEmail](http://caspian.dotconf.net/menu/Software/SendEmail/)
* [s3cmd](http://s3tools.org/s3cmd)
