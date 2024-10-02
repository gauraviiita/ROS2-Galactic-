Traceback (most recent call last):
  File "/home/gaurav/ros2_ws/src/my_py_pkg/my_py_pkg/./my_first_node.py", line 3, in <module>
    from rclpy.node import Node
  File "/opt/ros/galactic/lib/python3.8/site-packages/rclpy/node.py", line 43, in <module>
    from rclpy.client import Client
  File "/opt/ros/galactic/lib/python3.8/site-packages/rclpy/client.py", line 22, in <module>
    from rclpy.impl.implementation_singleton import rclpy_implementation as _rclpy
  File "/opt/ros/galactic/lib/python3.8/site-packages/rclpy/impl/implementation_singleton.py", line 32, in <module>
    rclpy_implementation = import_c_library('._rclpy_pybind11', package)
                           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/opt/ros/galactic/lib/python3.8/site-packages/rpyutils/import_c_library.py", line 39, in import_c_library
    return importlib.import_module(name, package=package)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
  File "/home/gaurav/anaconda3/lib/python3.12/importlib/__init__.py", line 90, in import_module
    return _bootstrap._gcd_import(name[level:], package, level)
           ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
ModuleNotFoundError: No module named 'rclpy._rclpy_pybind11'
The C extension '/opt/ros/galactic/lib/python3.8/site-packages/_rclpy_pybind11.cpython-312-x86_64-linux-gnu.so' isn't present on the system. Please refer to 'https://index.ros.org/doc/ros2/Troubleshooting/Installation-Troubleshooting/#import-failing-without-library-present-on-the-system' for possible solutions
