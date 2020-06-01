#零终端自动化冒烟测试

##零终端自动化冒烟测试：
1.测试目的：在初期发现问题，build可用。

##测试用例实现方案：
1.用例启动：
   通过可执行文件，或者接口
2.结果验证：
   a)用例跑完之后
   b)用例跑完之后
   *由于log比较大

##Requirement：
###1.install Python 3.4+
###2.install pythonlib:
  cd /testcases
  pip install -r requirement.txt

##Run:
###1.cd /testcases
###2.run case:
  1).run all cases:
    pytest --serial $device_IP
  2).run specific case:
    pytest $specificcase.py --serial $device_IP
###3.test result:
  you can find result log at direction ../testcases/testlog
  result.log: pass/fail of each cases
  2020-xx-xx xx:xx:xx.log: full log which contain console output
  

