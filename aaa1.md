1）paramget（获取读写器参数）

请求正文格式：

{

"param\_name": "参数名"

}

响应正文含有API接口函数特定对象，格式为：

"result": {

"param\_name": "参数名",

"param\_value":参数值

}

