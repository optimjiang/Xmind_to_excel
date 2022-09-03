# Xmind_to_excel
支持自定义配置转换规则，目前已经同时支持了ZEN版本的xmind。
支持多模板配置。具体使用看配置文件 xmind_to_excel_config.ini

这个ini配置想优化，变的更简单和直观，有试过用json键值对去配置excel表格的第一行和对应数值，效果比较直观，类似如下形式；

  "单元格格式": {
        "font_size": 14,
        "bold": 0,
        "text_wrap": 1,
        "border": 1,
        "valign": "vcenter"
  },
  
 "单元格内容": [{
      "第一行": "序号",
      "宽度": 5,
      "内容": "order_number"
    },
    {
      "第一行": "我是B1单元格",
      "宽度": 10,
      "内容": "2.title"
    },

也想过，干脆用excel去配置，也直观，然后转csv文件读取。

也欢迎其他人一起协作，提出更好的方案
