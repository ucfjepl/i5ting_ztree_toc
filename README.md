# jQuery.zTree_Toc.js

this is a jQuery plugin for preview  markdown table of content

![](demo/1.png)

![](demo/2.png)

## Usage

Add this line to your html file:

	<script type="text/javascript" src="js/jquery-1.4.4.min.js"></script>
	<script type="text/javascript" src="js/jquery.ztree.core-3.5.js"></script>
	<script type="text/javascript" src="jquery.ztree_toc.js"></script>

And then execute:

	<SCRIPT type="text/javascript" >
	<!--
	$(document).ready(function(){
		$('#tree').ztree_toc({
	
		});
	});
	//-->
	</SCRIPT>
	
## 例子

	$(document).ready(function(){
		$('#tree').ztree_toc({
			is_auto_number: true,
			// documment_selector: '.first_part'
		});
	});
	

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

or see at [CONTRIBUTING.md](CONTRIBUTING.md)

## 版本历史

- v0.1.0 初始化版本 

## Checklist

- Completely customizable documment selector: 'body' 自定义header文档位置，此处为jq的选择器（已完成）
- is_auto_number: false, 默认是否显示header编号（已完成）
- is_expand_all: true,默认是否展开全部（已完成）
- is_highlight_selected_line是否对选中行，显示高亮效果（TODO）
- Click to smooth scroll to that spot on the page（TODO）
- Automatically highlight the current section（TODO）
- Extremely lightweight (744 bytes gzipped)（TODO）
- Can have multiple on a page（TODO）
- 正文移动，更新目录（TODO）
- 滚动动画（TODO）

## License

this gem is released under the [MIT License](http://www.opensource.org/licenses/MIT).
