[![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
# chakio_utils
よく使用するけど、覚えていなくて検索しがちな関数や便利な関数等々を蓄積していくリポジトリ  
やりたいことから関数が検索できるような辞書を目指します

## Description
* cpp_util.cpp:cpp全般における関数群
* cpp_ros_util.cpp:rosのソースコードをcppで書く際に役立つ関数群
* cpp_of_util.cpp:openframeworksのソースコードを書く際に役立つ関数群
* python_util.py:python全般における関数群
* python_ros_util.py:rosのソースコードをpythonで書く際に役立つ関数群

## [cpp_lib.cpp](https://github.com/chakio/chakio_utils/blob/master/cpp/cpp_util.cpp)
* double getAverageAngle(vector<double> radAngles)
    * 角度の平均値を求める
* double getLimitedAngle2PI(double angle)
    * 角度を0~2PIに収める
* double getLimitedAnglePI2PI(double limitedAngle2PI)
    * 角度を-PI~PIに収める

## [cpp_ros_util.cpp](https://github.com/chakio/chakio_utils/blob/master/cpp/cpp_ros_util.cpp)
* [tf::Quaternion rpy2tfQuat(double roll, double pitch, double yaw)](https://github.com/chakio/chakio_utils/blob/3dcbb9adb8ef446b91b54135fe35f792b0b4fe8b/cpp/cpp_ros_util.cpp#L1-L11)
    * ロール、ピッチ、ヨー角からtf::Quatanionへの変換
* [geometry_msgs::Quaternion rpy2geometryQuat(double roll, double pitch, double yaw)](https://github.com/chakio/chakio_utils/blob/3dcbb9adb8ef446b91b54135fe35f792b0b4fe8b/cpp/cpp_ros_util.cpp#L12-L25)
    * ロール、ピッチ、ヨー角からgeometry_msgs::Quatanionへの変換
* [void tfQuat2rpy(tf::Quaternion quat,double& roll, double& pitch, double& yaw)](https://github.com/chakio/chakio_utils/blob/3dcbb9adb8ef446b91b54135fe35f792b0b4fe8b/cpp/cpp_ros_util.cpp#L26-L37)
    * tf::Quatanionからロール、ピッチ、ヨー角への変換
* [void geometryQuat2rpy(geometry_msgs::Quaternion geometry_quat, double& roll, double& pitch, double& yaw)](https://github.com/chakio/chakio_utils/blob/3dcbb9adb8ef446b91b54135fe35f792b0b4fe8b/cpp/cpp_ros_util.cpp#L38-L50)
    * geometry_msgs::Quatanionからロール、ピッチ、ヨー角への変換
* [geometry_msgs::Pose pose2D2pose(geometry_msgs::Pose2D pose2D)](https://github.com/chakio/chakio_utils/blob/3dcbb9adb8ef446b91b54135fe35f792b0b4fe8b/cpp/cpp_ros_util.cpp#L51-L72)
    * geometry_msgs::Pose2Dからgeometry_msgs::Poseへの変換
* [geometry_msgs::Pose2D pose2pose2D(geometry_msgs::Pose pose)](https://github.com/chakio/chakio_utils/blob/3dcbb9adb8ef446b91b54135fe35f792b0b4fe8b/cpp/cpp_ros_util.cpp#L73-L94)
    * geometry_msgs::Poseからgeometry_msgs::Pose2Dへの変換
* [void getRosParam()](https://github.com/chakio/chakio_utils/blob/3dcbb9adb8ef446b91b54135fe35f792b0b4fe8b/cpp/cpp_ros_util.cpp#L102-L111)
    * ros paramを用いた実行時のパラメータ設定

## [cpp_of_util.cpp](https://github.com/chakio/chakio_utils/blob/master/cpp/cpp_of_util.cpp)
* aa

## [python_util.py](https://github.com/chakio/chakio_utils/blob/master/python/python_util.py)
* aa

## [python_ros_util.py](https://github.com/chakio/chakio_utils/blob/master/python/python_ros_util.py)
* aa

## Author
[chakio](https://github.com/chakio)