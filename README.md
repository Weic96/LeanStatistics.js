# LeanStatistics.js
LeanCloud based article reading statistics plugin

#### [Demo](https://isweic.com/LeanStatistics.js-demo/)
#### [中文文档](https://isweic.com/LeanStatistics.js/)

### Installation && Usage

```
<span class="article-alone-item"><i class="fa fa-eye"></i><span class="views views-post" id="/ur" title="title"></span></span>

<script type="text/javascript">
	var config = {
		APP_ID: 'LeanCloud APP_ID',
		APP_KEY: 'LeanCloud APP_KEY',
		ClasS: '此处填Class',,
		el:'.views',
		elP: '.views-post'
	}
</script>
<script src="https://cdn.bootcss.com/jquery/2.2.4/jquery.min.js" charset="utf-8"></script>
<script src="//cdn1.lncld.net/static/js/3.1.0/av-min.js" charset="utf-8"></script>
<script src="LeanStatistics.min.js"></script>
```
and Home Page(Display function only)

```
<span class="article-alone-item"><i class="fa fa-eye"></i><span class="views views-post" id="/ur" title="title"></span></span>
```
### Options
|      name     |   Require   |   Note    |  
| ------------- | ----------- | --------------- |  
|      `APP_ID`     |     mast    | Leancloud APP_ID           | 
|      `APP_KEY`     |     mast    | Leancloud APP_KEY          |   
|   `ClasS`    |     mast    | Leancloud Class Name          | 
|   `el`   |     mast    | HTML Element          | 
|   `elP`   |     mast    | Post page HTML Element          | 


### License
[GPL-3.0](https://github.com/Weic96/LeanStatistics.js/master/LICENSE)
