set_proxy
=========

一个简单的 Python 工具，用于设置和管理系统代理。

功能特点
--------

- 快速设置系统代理
- 支持 HTTP 和 HTTPS 代理
- 跨平台支持（Windows、macOS、Linux）

安装
----

.. code-block:: bash

    pip install set-proxy

使用方法
--------

.. code-block:: python

    from set_proxy import set_proxy

    # 设置代理
    set_proxy("http://127.0.0.1:7890")

    # 清除代理
    set_proxy(None)

贡献
----

欢迎提交 Issue 和 Pull Request！

许可证
------

MIT License