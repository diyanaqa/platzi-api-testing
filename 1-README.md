# 🧪 Platzi FakeAPI Testing Project

This project demonstrates an API testing workflow that includes:

1. 📋 Defining test cases in Qase  
2. 🧪 Executing tests using Postman  
3. 🐞 Reporting bugs in Jira

## 🔗 API: https://fakeapi.platzi.com/en/rest/users/

## 🛠️ Tools
- Qase – test case management  
- Postman – API request execution  
- Jira – bug tracking and reporting

## 📁 Structure
- `qase/` – test cases  
- `postman/` – Postman collection  
- `bugs/` – documented bugs  
- `screenshots/` – test result evidence

## 🐞 Known Bug
A user can be deleted via a DELETE request without authorization.  
This is a serious security vulnerability and has been reported in Jira.
