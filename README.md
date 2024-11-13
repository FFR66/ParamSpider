# ParamSpider
修改Bug后的ParamSpider，方便各位师傅使用

## 项目源地址
### 感谢源项目作者的开源精神!!
> https://github.com/devanshbatham/paramspider

![paramspider](https://github.com/devanshbatham/ParamSpider/blob/master/static/paramspider.png?raw=true)

## 安装
### 来到存在set.up文件的目录下面
![image](https://github.com/user-attachments/assets/88ec45d3-6057-4760-9def-4d9cdf5ee12e)


### 执行以下命令
```sh
pip install .
```

![image](https://github.com/user-attachments/assets/4e443ac7-863e-4704-b375-1ff489e9af42)


## 使用方式

To use `paramspider`, follow these steps:

```sh
paramspider -d example.com
```

## Examples

Here are a few examples of how to use `paramspider`:

- Discover URLs for a single domain:

  ```sh
  paramspider -d example.com
  ```

- Discover URLs for multiple domains from a file:

  ```sh
  paramspider -l domains.txt
  ```

- Stream URLs on the termial:

  ```sh 
  paramspider -d example.com -s
  ```

- Set up web request proxy:

  ```sh
  paramspider -d example.com --proxy '127.0.0.1:7890'
  ```

- Adding a placeholder for URL parameter values (default: "FUZZ"): 

  ```sh
   paramspider -d example.com -p '"><h1>reflection</h1>'
  ```


