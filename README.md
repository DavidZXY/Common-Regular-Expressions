# Common-Regular-Expressions
常用正则表达式

必须同时包含数字和字母（限定位数6-18） ^(?![0-9]+$)(?![a-zA-Z]+$)[0-9A-Za-z]{6,18}$

以句号划分中文句子，三句一划分 ([\u4e00-\u9fa5[\p{P}&&[^。]]]+。){3}|([\u4e00-\u9fa5[\p{P}&&[^。]]]+。)*
