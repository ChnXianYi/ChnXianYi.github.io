# Axios

axios是ajax的封装,基于promise的HTTP库

## 原生Ajax缺点

MVC编程，不符合现在的 MVVM
使用Ajax而引入整个 JQuery 不合理
不符合关注分离(Separation of Concerns)原则
配置和调用方式混乱，基于事件的异步模型不友好

## RestFul API 规范

* GET(SELECT): 从服务器取出资源
* POST(CREATE) 在服务器新建一个资源
* PUT(UPDATE) 在服务器更新资源(客户端提供改变后的完整资源)
* PATCH(UPDATE) 在服务器更新资源(客户端提供改变的属性)
* DELETE(DELETE) 在服务器删除资源

## 常用语法

* axios(config) | 发送任意请求
* axios(url[,config]) | 指定url发送 get 请求
* axios.request(config) | 等同于 axios(config)
* axios.get(url[,config]) | 发送 get 请求
* axios.delete(url[,config]) | 发送 delete 请求
* axios.post(url[,data , config]) | 发送 post 请求
* axios.put(url[, data , config]) | 发送 put 请求
* axios.defaults.xxx | 请求的默认全局配置
* axios.interceptors.request.use() | 添加请求拦截器
* axios.interceptors.response.use() | 添加响应拦截器
* axios,create([config]) | 创建一个新的 axios (没有下面的功能)
* axios.Cancel() | 创建取消请求的错误对象
* axios.CancelToken() | 创建取消请求的 token 对象
* axios.isCancel() | 是否是一个取消请求的错误
* axios.all(promises) | 批量执行多个异步请求
* axios.spread() | 指定接收所有成功数据的回调函数的方法

## 响应报文

* 响应头 : headers
* 响应行
* 响应体
* 响应空行
* request: 原生的ajax请求对象
* status: 响应状态码

## 配置对象(config)

* url : 请求地址
* method : 请求类型
* baseURL : 请求地址的基础地址
* transformRequest : 将请求数据进行处理，在进行发送
* transformResponse : 对响应的结果进行改变
* headers : 对请求头信息配置
* params ：设定url参数 添加属性

```js
function get (){ // 获取
    // 发送Ajax请求
        axios({
        // 请求类型
            method: 'GET', // GET POST PUT DELETE
        // URL
            url: 'http:// ...posts'
        }).then((result) => { // 成功信息
            
        }).catch((err) => { // 失败信息
                
        });
}

function post (){ // 新建
        axios({
            method: 'POST', // GET POST PUT DELETE
            url: 'http:// ...posts',
            // 设置请求体
            data: {
                    title: '请求数据',
                    author: '请求数据'
            }
        }).then((result) => { // 成功信息
            
        }).catch((err) => { // 失败信息
                
        });
}

function put (){ // 更新
    axios({
        method: 'PUT', // GET POST PUT DELETE
        url: 'http:// ...posts/id',
        data: {
                title: '请求数据',
                author: '请求数据'
        }
    }).then((result) => { // 成功信息
        
    }).catch((err) => { // 失败信息
            
    });
}   
    
function Delete (){ // 删除
        axios({
        method: 'DELETE', // GET POST PUT DELETE
        url: 'http:// ...posts/id',
        }).then((result) => { // 成功信息
        
        }).catch((err) => { // 失败信息
                
        });
    }
```

## 实例
POST ， 将JSON转化为字符串格式

* `transformRequest` 允许在向服务器发送前，修改请求数据,对 data 进行任意转换处理
* `headers` 是即将被发送的自定义请求头
* `encodeURIComponent(str)`  进行 URL 编码
* 对应的解码为 `decodeURIComponent()`

```js
fun(){
    axios.post('url: ...' , this.value , {
        transformRequest: [ 
            function(data){
                let str = '',
                for(let key in data){
                    str += encodeURIComponent(key)
                        + '='
                        + encodeURIComponent(data[key])
                        + '&'
                }
                return str
            }
        ],
        headers: {
            // 传入头信息
        },

    }).then((result) => {
        
    }).catch((err) => {
        
    });
}
```

## 封装网络请求

1.创建一个统一的接口目录
2.新建一个 request.js 文件

* baseURL: 设置基础 URL
* timeout: 设置 请求超时上限，超时将中断请求
* headers: 自定义请求头

```js
import axios from 'axios'

// 创建 axios 实例 
const instance = axios.create({
    baseURL: 'http:// ...',
    timeout: 1000 , 
    headers: {'':''}
})

// 封装方法 
export function get(url , params) {  // 封装 get 方法 
    return axios.get(url , {  // return axios 返回的是promise 值，可以 get.then()
    //     instance.get(... // 使用实例
        params
    })
}
```