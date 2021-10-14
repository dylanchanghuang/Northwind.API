# Northwind.API
Northwind資料庫的API

1. 開發工具: Visual Studio 2019  
   (1) Entity Framework Core  
   (2) Swashbuckle: 產生API文件  
2. 程式語言: .NET Core 5.0  
3. 資料庫: SQL Server 2019  
   (1) DB : Northwind  
4. API測試方式: 使用 Visual Studio 2019 , 運用 Debug 工具 >> 選擇 IIS Express 後, 可以用 Postman 測試API  
5. API文件網址: https://localhost:44339/swagger  
6. 使用 IIS Express + Postman測試API時, 要將 Postman的 Settings 裡 SSL certificate verification 勾選取消  
7. 專案架構:  
   (1) Northwind.API : API  
   (2) Northwind.Domain : 領域層 (資料庫的檔案Layout)  
