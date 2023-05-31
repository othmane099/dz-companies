# dz-companies

This repository contains the list of companies in Algeria.

The data was collected from [emploitic](https://www.emploitic.com/) platform on 29 MAI 2023.

There are +4000 company.

The data is available in CSV and JSON format.

## DZ Company API

This [API](https://dz-companies.ombdev.com/api/v1/companies) allows to leverage the data and gain valuable insights.

BaseUrl: `https://dz-companies.ombdev.com/api/v1/companies` .

### Endpoints

**`GET /`** : Get all companies.
  
**Parameters**

| Name         | In     | Required | Description             |
| -------------|--------|----------|-------------------------|
| `search`     | query  | No       | Search by company name. |


**`GET /:companyId`** : Get company by id.

**Parameters**

| Name         | In     | Required | Description          |
|--------------|--------|----------|----------------------|
| `companyId`  | path   | Yes      | find company by id.  |


**`GET /name/companyName`** : Get company by name.


**Parameters**

| Name          | In     | Required | Description             |
| --------------|--------|--------- | ------------------------|
| `companyName` | path   | Yes       | find company by name.  |


**`GET /categories`** : Get all categories.


**Parameters**

| Name         | In     | Required | Description              |
| -------------| ------ |--------- | -------------------------|
| `search`     | query | No        | Search category by name. |


**`GET /categories/companyCategory`** : Get company by category.


**Parameters**

| Name              | In    | Required | Description               |
|-------------------|-------|----------|---------------------------|
| `companyCategory` | path  | Yes      | find company by category. |


## Contribution

If you want to contribute to this project and make it better with new ideas, your pull request is very welcomed. If you find any issue just put it in the repository issue section, thank you.

