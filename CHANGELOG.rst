^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package rosidl_typesupport_c
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.9.0 (2020-04-24)
------------------
* Fix single typesupport build exposing build directory in include dirs (`#71 <https://github.com/ros2/rosidl_typesupport/issues/71>`_)
* Export targets in addition to include directories / libraries (`#69 <https://github.com/ros2/rosidl_typesupport/issues/69>`_ `#70 <https://github.com/ros2/rosidl_typesupport/issues/70>`_)
* Fix build with single introspection typesupport (`#68 <https://github.com/ros2/rosidl_typesupport/issues/68>`_)
* Update includes to use non-entry point headers from detail subdirectory (`#66 <https://github.com/ros2/rosidl_typesupport/issues/66>`_)
* Rename rosidl_generator_c namespace to rosidl_runtime_c (`#65 <https://github.com/ros2/rosidl_typesupport/issues/65>`_)
* Remove dependency on rmw_implementation (`#62 <https://github.com/ros2/rosidl_typesupport/issues/62>`_)
* Added rosidl_runtime c depencency (`#58 <https://github.com/ros2/rosidl_typesupport/issues/58>`_)
* Removed poco dependency (`#59 <https://github.com/ros2/rosidl_typesupport/issues/59>`_)
* Remove OpenSplice dependencies (`#56 <https://github.com/ros2/rosidl_typesupport/issues/56>`_)
* Depend on rcpputils` for find_library (`#47 <https://github.com/ros2/rosidl_typesupport/issues/47>`_)
* Contributors: Alejandro Hernández Cordero, Dirk Thomas, Eric Cousineau, Jacob Perron, Sean Kelly

0.8.0 (2019-09-26)
------------------

0.7.1 (2019-05-08)
------------------
* update code to match refactoring of rosidl definitions (`#49 <https://github.com/ros2/rosidl_typesupport/issues/49>`_)
* remove usage of UnknownMessageType (`#48 <https://github.com/ros2/rosidl_typesupport/issues/48>`_)
* Contributors: Dirk Thomas

0.7.0 (2019-04-14)
------------------
* Using ament_target_dependencies where possible (`#46 <https://github.com/ros2/rosidl_typesupport/issues/46>`_)
* change generators to IDL-based pipeline (`#39 <https://github.com/ros2/rosidl_typesupport/issues/39>`_)
* Contributors: Dirk Thomas, ivanpauno

0.6.2 (2019-01-11)
------------------
* include available typesuppports in error message (`#43 <https://github.com/ros2/rosidl_typesupport/issues/43>`_)
* Change uncrustify max line length to 0 (`#42 <https://github.com/ros2/rosidl_typesupport/issues/42>`_)
* Contributors: Dirk Thomas, Jacob Perron

0.6.1 (2018-12-07)
------------------
* Merge pull request `#41 <https://github.com/ros2/rosidl_typesupport/issues/41>`_ from ros2/hidmic/trim-action-targets-names
* Contributors: Michel Hidalgo

0.6.0 (2018-11-16)
------------------
* Add typesupport for actions in c and c++ (`#36 <https://github.com/ros2/rosidl_typesupport/issues/36>`_)
* Allow generated IDL files (`#35 <https://github.com/ros2/rosidl_typesupport/issues/35>`_)
* Merge pull request `#33 <https://github.com/ros2/rosidl_typesupport/issues/33>`_ from ros2/hidmic/prepare_for_action_generation
* Removes remaininig srv folder assumptions.
* Makes rosidl interfaces generation action folder aware.
* update manifest to adhere to tag order in schema (`#30 <https://github.com/ros2/rosidl_typesupport/issues/30>`_)
* Contributors: Alexis Pojomovsky, Dirk Thomas, Michel Hidalgo, Shane Loretz

0.5.0 (2018-06-24)
------------------
* Prepare dependencies for bouncy release. (`#27 <https://github.com/ros2/rosidl_typesupport/issues/27>`_)
* add and use groups for generator and runtime packages (`#25 <https://github.com/ros2/rosidl_typesupport/issues/25>`_)
* Merge pull request `#23 <https://github.com/ros2/rosidl_typesupport/issues/23>`_ from ros2/misra_fixup
* Merge pull request `#22 <https://github.com/ros2/rosidl_typesupport/issues/22>`_ from ros2/use_typesupport_group
* use CMAKE_CURRENT_BINARY_DIR for arguments json (`#21 <https://github.com/ros2/rosidl_typesupport/issues/21>`_)
* use ament_cmake_ros (`#19 <https://github.com/ros2/rosidl_typesupport/issues/19>`_)
* Contributors: Dirk Thomas, Michael Carroll, Steven! Ragnarök

0.4.0 (2017-12-08)
------------------
* update service type support header name (`#15 <https://github.com/ros2/rosidl_typesupport/issues/15>`_)
* Contributors: Dirk Thomas, Mikael Arguedas
