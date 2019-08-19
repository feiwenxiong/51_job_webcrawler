# parse_51_job

purpose : auto get the infos for job you want to apply， including working place, working position, salary and publish date.

目标：自动获得指定薪水、地区的工作信息：工作名、工作地点、薪水、公司名称以及发布日期等

1.input your job name and the final excel csv file path you want to save as.

首先提示输入你搜索的名字，最后会让你填写你想保存的地址

2.then it will auto-browse the website of 51job: 'www.51job.com' and save as csv/excel.

然后爬虫自动登录网站爬取信息，保存到本地

3.I set Shenzhen as default city, salary more than 10 million RMB as default salary expectation.

目标城市：深圳  月薪：1w+


special :
using *selenium* to auto-click and perform auto_next page. 
