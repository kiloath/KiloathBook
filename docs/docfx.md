docfx
=======
# {1!} 參考
* [docfx 官網](https://dotnet.github.io/docfx/)
# {2!} 環境
* 更新 docfx, 依環境使用`sudo`, (v2.74.1)。
  ```
  dotnet tool update -g docfx
  ```
* 新建
  ```
  ni KiloathBook -i d
  cd ./KiloathBook/
  docfx init
  ```
* 參數
  ```
  Name (mysite): KiloathBook
  Generate .NET API documentation? [y/n] (y): n
  Markdown docs location (docs): docs
  Enable site search? [y/n] (y): y
  Enable PDF? [y/n] (y): n
  Is this OK? [y/n] (y): y
  ```
* 執行
  ```
  docfx docfx.json --serve
  ```
* 瀏覽
  ```
  start localhost:8080
  ```
