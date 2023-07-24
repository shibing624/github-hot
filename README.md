# github-hot
Tracking the hot Github repos and update daily


1. 基于Github [Actions](https://github.com/shibing624/github-hot/blob/main/.github/workflows/schedule.yml)每天自动抓取热门项目
2. 支持项目列表markdown格式输出，自动同步到github
3. 支持自定义排序，选取topk热点兴趣项目

## Usage
```shell
$ git clone https://github.com/shibing624/github-hot.git
$ cd github-hot
$ pip install -r requirements.txt
$ python crawler.py
```

### Result

<img src="https://github.com/shibing624/github-hot/blob/main/docs/pic.png" width="860" />



## Contact

- Issue(建议)：[![GitHub issues](https://img.shields.io/github/issues/shibing624/github-hot.svg)](https://github.com/shibing624/github-hot/issues)
- 邮件我：xuming: xuming624@qq.com
- 微信我：加我*微信号：xuming624*, 进Python-NLP交流群，备注：*姓名-公司名-NLP*


## License

授权协议为 [The Apache License 2.0](LICENSE)，可免费用做商业用途。请在产品说明中附加**github-hot**的链接和授权协议。


## Contribute
项目代码还很粗糙，如果大家对代码有所改进，欢迎提交回本项目，在提交之前，注意以下两点：

 - 在`tests`添加相应的单元测试
 - 使用`python -m pytest`来运行所有单元测试，确保所有单测都是通过的

之后即可提交PR。


## Related Projects

- javascript：[vitalets/github-trending-repos](https://github.com/vitalets/github-trending-repos)
