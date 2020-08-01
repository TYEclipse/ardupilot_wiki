.. _home:

..  raw:: html

    <h1 style="text-align:center;">阿杜皮洛特</h1>

    <p style="text-align:left;">

    ArduPilot使人们能够创建和使用可信的、自主的、无人驾驶的车辆系统，为所有人的和平利益服务。ArduPilot提供了一套全面的工具，适用于几乎任何车辆和应用程序。作为一个开放源码项目，它是基于来自大量用户社区的快速反馈而不断发展的。开发团队与社区和商业伙伴合作，为ArduPilot添加功能，使每个人都受益。虽然ArduPilot不生产任何硬件，ArduPilot固件工作在各种不同的硬件，以控制各种类型的无人驾驶汽车。再加上地面控制软件，运行ArduPilot的无人驾驶汽车可以具有先进的功能，包括与操作员的实时通信。ArduPilot有一个巨大的在线社区，致力于帮助用户解决问题和解决方案。 </p>

    <p style="text-align:center;">直升机？？飞机？？罗孚？次？？天线追踪器。</p>


.. image:: ../../images/home_ardupilot.jpg
    :target: _images/home_ardupilot.jpg

..  raw:: html

    <table>
    <tr>
    <td width="27%">


:ref:`Hardware <stores>`  是作为车辆的眼睛、耳朵、大脑和手臂的外围传感器、控制器和输出设备。

几乎任何移动机器都可以通过简单地集成一个小的硬件包来转换成一个自动车辆。硬件包从控制器开始。

利用来自传感器的输入，控制器能够将输出发送到诸如ESC、Seros、Gimbals和其他外设等设备。

.. image:: ../../images/pixhawk_small.jpg
    :target: _images/pixhawk_small.jpg
    :width: 211px

..  raw:: html

    </td>
    <td width="4%">
    </td>
    <td width="27%">

:ref:`Firmware <common-downloads_firmware>`-控制器上运行的代码。您可以选择符合您的车辆和任务的固件：:ref:`Copter <copter:home>`, `Plane <https://ardupilot.org/plane/index.html>`__,
:ref:`Rover <rover:home>`, Sub, or :ref:`Antenna Tracker <antennatracker:home>`.

选择是你的--任何任务都需要一个自动驾驶仪。

.. image:: ../../images/firmware_types.jpg
    :target: _images/firmware_types.jpg
    :width: 211px

..  raw:: html

    </td>
    <td width="4%">
    </td>
    <td width="27%">

:ref:`Software <common-choosing-a-ground-station>` 是你和控制器的接口。该软件也被称为地面控制站(GCS)，可以在PC或移动设备上运行。
GCS允许用户设置、配置、测试和调整车辆.先进的软件包允许自主的任务规划、操作和任务后分析.

:ref:`Mission Planner <planner:home>` 是一个功能齐全的GCS支持的ArduPilot。它提供与您的硬件、自定义脚本和模拟的点击交互。

.. image:: ../../images/mission_planner_spline_waypoint.jpg
    :target: _images/mission_planner_spline_waypoint.jpg
    :width: 211px

..  raw:: html

    </td>
    </tr>
    </table>



--------------
ArduPilot文件
=======================

有关ArduPilot文档的链接，请参见侧栏。

快速启动
==========

- 选择左侧的车辆类型
- 为您的应用程序选择“自动驾驶硬件”和“外围硬件”。
- 按照车辆的“第一次安装”安装固件和地面站软件，连接组件和校准步骤
- 准备“第一次飞行(/驾驶)”，在第一次飞行/驾驶前完成安装
- 高级配置提供了固件和硬件外围设备更高级功能的设置。

条例
===========

每个国家对遥控和/或自动车辆的操作都有不同的规定。 `This database <https://droneregulations.info>`__  有具体国家的信息，但每个经营者的责任是寻找和了解地方、地区和联邦法规。

社区
=========
.. tip::

   关注与ArduPilot相关的最新博客 `ArduPilot.org! <https://discuss.ardupilot.org/c/blog>`__

社区才是ArduPilot真正有别于市场上许多其他产品的地方。下面是一些您可以找到ArduPilot用户和开发人员的地方：

`Discussion Forum: <https://discuss.ardupilot.org/>`__

.. image:: ../../images/ArduPilotDiscuss.png
    :target: https://discuss.ardupilot.org/
    :width: 640px

`Facebook ArduPilot group <https://www.facebook.com/groups/ArduPilot.org/>`__

.. image:: ../../images/main/FaceBookArduPilot.png
    :target: https://www.facebook.com/groups/ArduPilot.org/

开发商社区
===================

`Developers Chat <https://gitter.im/ArduPilot/ardupilot>`__
在写密码？问Gitter团队的问题。

`Developers Guide <https://ardupilot.org/dev/index.html>`__
对于那些想进入ArduPilot开发的具体细节的人来说，所有的事情都可以在开发者指南中找到。

我们每周都有 `meeting times <https://ardupilot.org/dev/docs/ardupilot-discord-server.html#ardupilot-discord-server>`__.

我们也有 `forums <https://discuss.ardupilot.org/>`__


历史
=======

无人机社区为ArduPilot提供了最初的住所。从这些爱好者开始，ArduPilot通过创建Dronecode领导了开源无人机社区的专业化。自2016年离开Dronecode以来，ArduPilot已经进一步发展成为一个独立、开放、全球性的项目。ArduPilot功能的全面和不断增长的列表不断地从社区的需求中诞生--无论是爱好者、商业用户、学者，还是最大的企业。见 :ref:`history-of-ardupilot` 想了解更多信息。

特征
========


..  raw:: html

    <table>
    <tr>
    <td width="48%">

-  关于社区支持的可用功能的详细文档，以帮助您设置满足您需要的任何工具。
-  适用于各种类型车辆的指挥模式有：Acro、稳定、游荡、Alt-持有、返回发射、着陆、跟随我、GeoFence等。.
-  自主飞行模式，执行完全脚本的任务，具有先进的功能。
-  先进的故障安全选项在失去控制信号、电池状况不佳或其他系统故障时会带来心灵的平静。
-  三轴相机控制与稳定，快门控制，实时视频链接，可编程屏幕显示。

..  raw:: html

    </td>
    <td width="4%">
    </td>
    <td width="48%">

-  GCS与控制器之间的实时双向通信，包括GPS定位、电池状态和其他实时信息.
-  使用绘图和谷歌地球绘图工具进行全面的任务后分析的全数据记录
-  工业领先的各类车辆控制算法，具有鲁棒的传感器补偿算法、滤波和调谐功能。
-  没有死胡同--高级用户将找到无限的定制选择和扩展的任务功能

..  raw:: html

    </td>
    </tr>
    </table>




--------------


.. toctree::
   :hidden:

   Home <https://ardupilot.org>
   Copter <https://ardupilot.org/copter/index.html>
   Plane <https://ardupilot.org/plane/index.html>
   Rover <https://ardupilot.org/rover/index.html>
   Sub <http://ardusub.com/>
   AntennaTracker <https://ardupilot.org/antennatracker/index.html>
   Mission Planner <https://ardupilot.org/planner/index.html>
   APM Planner 2 <https://ardupilot.org/planner2/index.html>
   MAVProxy <https://ardupilot.org/mavproxy/index.html>
   Companion Computers <https://ardupilot.org/dev/docs/companion-computers.html>
   Developers <https://ardupilot.org/dev/index.html>
   Firmware Downloads <docs/common-downloads_firmware>
   The ArduPilot Team <docs/common-team>
   The History of ArduPilot<docs/common-history-of-ardupilot>
   ArduPilot Partners Program <docs/common-partners-program>
   Commercial Support <docs/common-commercial-support>
   Acknowledgements <docs/common-acknowledgments>
   Hardware Vendors <docs/common-stores>
   Contact Us <docs/common-contact-us>
   docs/common-appendix
   Full Table of Contents <docs/common-table-of-contents>
