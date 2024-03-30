# GitHub API - Jmeter - Load Testing framework setup

This project is based on Load Testing, Jmeter

## REST API endpoints for users
```bash
  https://docs.github.com/en/rest/users/users
```

## 1. Jmeter download
```bash
  https://jmeter.apache.org/download_jmeter.cgi
```
## 2. open and run the jmeter

To run the jmeter, open the following path

```bash
  C:\apache-jmeter\apache-jmeter\bin\
```

## 3. clone the repo

To clone the repo, run the following command

```bash
  git clone https://github.com/shivam-test/Load-Testing.git
```

## 4. Execute the test 

To open the .jmx file, open the follwing path
```bash
  File > Open > Repo > .jmx file > Start
```

## 5. Check the Reports

To check the reports, go to the bin folder, you will find report name as:

```bash
  Results.csv
```

## 5. To generate HTML Report

To generate the HTML reports, go to the bin folder, run the following command:
and HTML folder will be created and report will be generated.

```bash
  jmeter -g Results.csv -o HTMLReports
```
