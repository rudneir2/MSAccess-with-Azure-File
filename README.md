# MSAccess-with-Azure-File
this is only a **draft** architecture of MSAccess running through Azure File

## Architecture diagram (draft only)

![image](https://user-images.githubusercontent.com/97529152/154765983-cc0aee5f-1806-4c69-ac6c-74841ee48f24.png)


## step by step

There is no official documentation from Microsoft about such architecture.

But basically you will have to do the following:

1. create Azure file (it is out of scope of this repo to explain how Azure File works and how to create it)
2. use Azure File share for the MSAccess Backend file (the DB)
3. have each of users that access MS Access with another file that represent the "forms" or also called as frontend file (it is also out of scope of this repo explain how MS Acces works)

The goal of this repo is just provide a very rough idea of how to use Azure File with MS Access.
