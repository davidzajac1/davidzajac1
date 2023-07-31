<p align="center">
  <a href="https://zillacode.com">
    <img width="auto" src="linkedin_background.jpg" alt="Header">
  </a>
</p>


[Zillacode.com](https://zillacode.com) has the tools I wish I had while making a radical self taught career shift into Data Engineering from working in the Oil Field.

While searching for jobs and trying to prepare for coding interviews every platform I found only offered vanilla Python and SQL problems, whereas most jobs wanted experience with tools like DBT, Spark and Snowflake.

After a battle spinning up Spark on my local machine and figuring out how all of these frameworks worked I was able to break into the industry and hopefully will remove this hurdle for others who want to do the same. Today hundreds have used Zillacode to study for coding interviews and learn the frameworks essential to being a modern Data Engineer.

---

 - ⭐ 100% Job Success Score and only 5-star client reviews on [Upwork.com Profile](https://www.upwork.com/freelancers/~01c133ff8ee4686b95)
 - ✅ [AWS Certified Solutions Architect -  Associate](awssa.pdf)

---

<p>
  <a href="https://github.com/davidzajac1/iamscan"><img width="250" align='right' src="iamscan_snapshot.PNG"></a>
</p>


### [IAMScan](https://github.com/davidzajac1/iamscan) - Checks code for needed AWS IAM Privileges
![Language](https://img.shields.io/badge/Language-Python-informational?style=flat)
![License](https://img.shields.io/badge/License-MIT-informational?style=flat)
![Version](https://img.shields.io/badge/Version-0.0.1-informational?style=flat)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

IAMScan is a command line tool that reads your code and generates an AWS IAM policy with your needed permissions. Keeping track of AWS IAM permissions is annoying and timeconsuming. How often have you seen an update deployed to the cloud followed by `The provided execution role does not have permissions to call CreateSomething on SomeService`? IAMScan solves this issue by generating a perfectly [least privilaged](https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html#grant-least-privilege) AWS IAM Policy for all Python Files, JavaScript Files and Shell Scripts from a single command line command.

IAMScan is [hosted on PyPI](https://pypi.org/project/iamscan/) and is installed using `pip`

<br />

```bash
$ pip install iamscan
```

---

<p>
  <a href="https://github.com/davidzajac1/Reptoro"><img width="300" align='right' src="reptoro-dashboard.JPG"></a>
</p>


### [Reptoro](https://github.com/davidzajac1/Reptoro) - A Data Visualization and Analytics Platform for the Reptile Industry
![Language](https://img.shields.io/badge/Language-Python-success?style=flat)
![Flask](https://img.shields.io/badge/Flask-v2.0.1-informational?style=flat)
![pandas](https://img.shields.io/badge/pandas-v1.3.3-informational?style=flat)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-v1.4.23-informational?style=flat)
![dash](https://img.shields.io/badge/dash-v2.0.0-informational?style=flat)

Reptoro uses an ETL pipeline architected using AWS Lambda, Athena, S3 and Apache Airflow to routinely webscrape online reptile marketplaces. Data is then stored in a Postgres RDS instance and is viewable on Reptoro.com, a Flask App hosted on EC2.

---

<p>
  <a href="https://github.com/davidzajac1/zoil"><img width="300" align='right' src="example_well.png"></a>
</p>


### [ZOil](https://github.com/davidzajac1/zoil) - Generate random Oil and Gas Data
![Language](https://img.shields.io/badge/Language-Python-success?style=flat)
![License](https://img.shields.io/badge/License-MIT-informational?style=flat)
![Version](https://img.shields.io/badge/Version-0.0.4-informational?style=flat)

ZOil is a python library used to generate random Oil and Gas data. Most Oil and Gas data is either propreitary or costly to aquire. ZOil lets you quickly generate an unlimited amount of production data that can be used to for testing, anonymization and much more. ZOil was inspired by the [`Faker`](https://github.com/joke2k/faker) library. 

ZOil is [hosted on PyPI](https://pypi.org/project/zoil/) and is installed using `pip`

<br />

```bash
$ pip install zoil
```
