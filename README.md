# proxy_kuaidaili
写的很简单的一个爬取快代理IP的python爬虫，最开始的愿望就是能够马上用即可，用在sqlmap里面，使用--proxy-file="ips.txt" 文件
文件中的ip地址按行要写成http://ip:port这种形式
逃避目标网址在我们注入时ban掉我们的ip地址
经过简单的测试之后，我发现快代理上免费的ip地址的质量实在是无法令人恭维，十个ip地址里面能有一个可用的已然不错
不过还是把代码放在github上，有了更好防止ban掉的方法的时候再进行修改
