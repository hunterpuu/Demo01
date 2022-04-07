# Demo01
Code ชุดนี้ถูกสร้างจาก Visual Studio 2019 เป็น Project type MVC .Net Core5 สามารถ pull code เพื่อไปทำการศึกษา CI pipeline ของ .Net core ได้โดยมี step ดังนี้

1. Run VS Code แล้วเปิดไปที่ Folder ของ Project

![VS](https://user-images.githubusercontent.com/82997996/162181042-74b12f4f-7d7c-49cc-9623-334deb1fe8a8.JPG)

2. Open Terminal Console

![TS](https://user-images.githubusercontent.com/82997996/162181243-f44dec64-3772-424c-80c1-452b6bc48876.JPG)

3. Run dotnet --info เพื่อ check version

![Version](https://user-images.githubusercontent.com/82997996/162181507-21ac547e-2ce3-4058-8405-1e33e9795db5.JPG)

4. Run dotnet restore 


![RS](https://user-images.githubusercontent.com/82997996/162181862-ab6a8673-0156-43dd-84b8-485397f8b48a.JPG)

5. Run dotnet build

![BU](https://user-images.githubusercontent.com/82997996/162181987-0b4e49e7-e214-4847-921b-04aa8cd225c6.JPG)

6. Run dotnet test

![Test](https://user-images.githubusercontent.com/82997996/162182122-33044432-7837-4669-af43-b76f1b948597.JPG)

7. Run dotnet publish

![image](https://user-images.githubusercontent.com/82997996/162182230-76c8c178-5b66-4778-beb7-7e5c0be6acaf.png)

8. ให้ Copy file ใน bin\Debug\net5.0\publish\ ไปวางใน web server ที่มี .Net core5 runtime

Result

![Result](https://user-images.githubusercontent.com/82997996/162128264-95136a06-fc06-4107-818c-1d652b032039.JPG)

Refer Dotnet Command --> https://docs.microsoft.com/en-us/dotnet/core/tools/
