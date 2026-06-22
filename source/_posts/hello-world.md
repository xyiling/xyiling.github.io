---
title: Hello World
abbrlink: 4a17b156
---

{% chart 300 200 %}                                                       
{                                                                         
    type: 'bar',                                                            
    data: {                                                                 
    labels: ['A','B','C'],                                                
    datasets: [{ data: [10,20,30] }]                                      
    }                                                                       
}                                                                         
{% endchart %}


{% echarts 400 300 %}                                                     
{                                                                         
    xAxis: { type: 'category', data: ['Mon','Tue','Wed'] },                 
    yAxis: { type: 'value' },                                               
    series: [{ data: [120, 200, 150], type: 'bar' }]                        
}                                                                         
{% endecharts %} 
Welcome to [Hexo](https://hexo.io/)! This is your very first post. Check [documentation](https://hexo.io/docs/) for more info. If you get any problems when using Hexo, you can find the answer in [troubleshooting](https://hexo.io/docs/troubleshooting.html) or you can ask me on [GitHub](https://github.com/hexojs/hexo/issues).

## Quick Start

### Create a new post

``` bash
$ hexo new "My New Post"
```

More info: [Writing](https://hexo.io/docs/writing.html)

### Run server

``` bash
$ hexo server
```

More info: [Server](https://hexo.io/docs/server.html)

### Generate static files

``` bash
$ hexo generate
```

More info: [Generating](https://hexo.io/docs/generating.html)

### Deploy to remote sites

``` bash
$ hexo deploy
```

More info: [Deployment](https://hexo.io/docs/one-command-deployment.html)
