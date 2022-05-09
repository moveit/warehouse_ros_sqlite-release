^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package warehouse_ros_sqlite
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.9.1 (2022-05-09)
------------------
* Update package.xml
  Version bump backwards to 0.9.0
  To distinguish between ROS1 and ROS2, the ROS1 version major stays at 0.
* Add busy handler for concurrent writes to db
* Export interfaces (dllexport/visibility=hidden)
* Versioning of the database scheme
* Adapt scheme to be more precise
* Fix query with ordering
* Use proper exception types
* Implemented dropping databases
* Support multiple databases with name mangling
  The collection name and the database name are mangled and concatenated
  to support multiple databases.
  SQLite only supports one database per file.
* Rollback on initialization error
* Fix validation of stored MD5 sum
* SQL String escaping
* Contributors: Bjar Ne, Jafar Abdi
