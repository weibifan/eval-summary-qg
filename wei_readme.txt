weibifan 2022-10-15
1）requirements.txt 会造成PyCharm卡死。
2）按reamde执行 pip install -r requirements.txt过程中 pycosat出错
去掉pycosat，安装所有包。再执行pip install pycosat也不行。
pycosat==0.6.3
3）关闭所有代理，执行 conda install pycosat，成功。
4）执行 python -m nltk.downloader punkt
一堆错误，应该是punkt的官方网址有问题，需要手工安装。详见另外文档。
