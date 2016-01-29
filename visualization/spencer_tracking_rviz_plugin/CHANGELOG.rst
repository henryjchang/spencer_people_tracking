^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package spencer_tracking_rviz_plugin
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.0.1 (2016-01-28)
------------------
* cleaning up changelog and back to 0.0.0
* 0.0.1
* update downgraded version to 0.0.0
* 1.0.1
* unitied the tags numbers
* Add changelogs
* Ignore Z position in visualization by default
* Update README.md
* Update README.md
* Disable group history visualization per default since it is very CPU-intensive, reduce default history size
* Various fixes to TrackedPersons and DetectedPersons display in RViz
  - Fix popping up of track / detection IDs when persons first appear
  - Add option to ignore Z position from ROS message
  - Prevent crash when covariance matrix is not positive (semi-)definite
  - Add option to hide IDs of single-person groups
  - Display MISSED (new) / MATCHED / OCCLUDED track status to distinguish between misdetections and physical occlusions
* Update README.md
* Adding message definitions, RViz plugins and mock scripts
* Contributors: Michael Jae-Yoon Chung, Timm Linder
