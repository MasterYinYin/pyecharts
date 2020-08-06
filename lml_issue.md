## lml库出现警告

/home/yuyin/.local/lib/python2.7/site-packages/lml/loader.py:64: UserWarning: Deprecated! since version 0.0.3. Please use scan_plugins_regex!
  "Deprecated! since version 0.0.3. Please use scan_plugins_regex!"
No handlers could be found for logger "lml.utils"


## 解决方案

卸载已有lml版本，使用0.0.2版就不会出现该项警告

卸载原版本
`pip uninstall lml`

安装0.0.2版本
`pip install lml==0.0.2`
