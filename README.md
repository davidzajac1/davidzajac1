<p align="center">
  <img width="auto" src="github_header.jpg" alt="Header">
</p>


---
---
 - 💪 Worked at multiple start-ups ranging from bootstrapped to Series B
 - ✅ [AWS Certified Solutions Architect -  Associate](awssa.pdf)
 - ⭐ 100% Job Success Score and only 5-star client reviews as contractor on [Upwork.com](https://www.upwork.com/freelancers/~01c133ff8ee4686b95)
 - 👷 Domain knowledge in Upstream Oil and Gas Operations

---
---

### [RE Data](https://github.com/re-data/re-data) - Open Source Maintainer & Top Contributor

<p>
  <a href="https://github.com/re-data/re-data"><img width="250" align='right' src="redata_logo.svg"></a>
</p>

![Stars](https://img.shields.io/github/stars/re-data/re-data?style=social)
![Forks](https://img.shields.io/github/forks/re-data/re-data?style=social)
![PyPI - Downloads](https://img.shields.io/pypi/dm/re-data)
![PyPI - Version](https://img.shields.io/pypi/v/re-data)
![MIT License](https://img.shields.io/badge/License-MIT-informational?style=flat)
![Language](https://img.shields.io/badge/Language-Python-informational?style=flat)
![Language](https://img.shields.io/badge/Language-DBT-informational?style=flat)

An open source data reliability framework for the modern data stack. RE Data is a DBT package, Python library and React UI. Adding the [RE Data DBT package](https://hub.getdbt.com/re-data/re_data/latest) to a DBT project will run out of the box data observability SQL queries in the background when `dbt run` is called. These queries calculate and store metrics like standard deviation, mean, row count, etc. The [RE Data Python library](https://pypi.org/project/re-data) can be called from the CLI to read in the stored metrics and create and serve [the RE Data UI](https://docs.getre.io/ui-latest/#/graph). RE Data is hosted across two GitHub repos. I am a top contributor to both and manage reviewing/merging PRs and creating releases.
- [Contributions re-data/re-data](https://github.com/re-data/re-data/commits?author=davidzajac1)
- [Contributions re-data/re-data-dbt](https://github.com/re-data/dbt-re-data/commits?author=davidzajac1)
- [Releases re-data/re-data](https://github.com/re-data/dbt-re-data/releases)
- [Releases re-data/re-data-dbt](https://github.com/re-data/re-data/releases)

<br />

```yaml
packages:
  - package: re-data/re_data
    version: 0.11.0
```

---
---

### [Zillacode](https://github.com/davidzajac1/zillacode) - Open Source LeetCode for PySpark, Spark, Pandas and DBT/Snowflake
![Stars](https://img.shields.io/github/stars/davidzajac1/zillacode?style=social)
![Forks](https://img.shields.io/github/forks/davidzajac1/zillacode?style=social)
![Apache License](https://img.shields.io/badge/License-MIT-informational?style=flat)
![Language](https://img.shields.io/badge/Language-PySpark-informational?style=flat)
![Language](https://img.shields.io/badge/Language-Spark-informational?style=flat)
![Language](https://img.shields.io/badge/Language-DBT-informational?style=flat)
![Language](https://img.shields.io/badge/Language-SnowSQL-informational?style=flat)

<p>
  <img width="400" align='right' src="zillacode.jpeg">
</p>

Created Zillacode the only platform on the internet where you can practice LeetCode like questions using PySpark, Spark, DBT and Snowflake. [Zillacode.com](https://zillacode.com) was once a live micro-serviced B2C SAAS platform with SSO and Automated Billing but is now Open Source on GitHub.

The entire platform spins up locally with one command using Docker Compose. When deployed to the Cloud Zillacode utilizes AWS Lambda Functions built from custom Docker images that package Spark and PySpark in a way that allows answers to be returned quickly.

```bash
$ git clone https://github.com/davidzajac1/zillacode.git
$ cd zillacode
$ docker-compose up
```

---
---

<p>
  <a href="https://github.com/davidzajac1/iamscan"><img width="350" align='right' src="iamscan_snapshot.PNG"></a>
</p>


### [IAMScan](https://github.com/davidzajac1/iamscan) - CLI tool checks code for AWS IAM Privileges
![Language](https://img.shields.io/badge/Language-Python-informational?style=flat)
![License](https://img.shields.io/badge/License-MIT-informational?style=flat)
![PyPI - Version](https://img.shields.io/pypi/v/iamscan)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

IAMScan is an open source command line tool that reads your code and generates an AWS IAM policy with your needed permissions. Keeping track of AWS IAM permissions is annoying and time consuming. How often have you seen an update deployed to the cloud followed by `The provided execution role does not have permissions to call CreateSomething on SomeService`? IAMScan solves this issue by generating a perfectly [least privileged](https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html#grant-least-privilege) AWS IAM Policy for all Python Files, JavaScript Files and Shell Scripts from a single command line command.

IAMScan is [hosted on PyPI](https://pypi.org/project/iamscan/) and is installed using `pip`

<br />

```bash
$ pip install iamscan
```

---
---

<p>
  <a href="https://github.com/davidzajac1/zoil"><img width="300" align='right' src="example_well.png"></a>
</p>


### [ZOil](https://github.com/davidzajac1/zoil) - Generate random Oil and Gas Data
![Language](https://img.shields.io/badge/Language-Python-informational?style=flat)
![License](https://img.shields.io/badge/License-MIT-informational?style=flat)
![PyPI - Version](https://img.shields.io/pypi/v/zoil)

ZOil is a python library used to generate random Oil and Gas data. Most Oil and Gas data is either proprietary or costly to acquire. ZOil lets you quickly generate an unlimited amount of production data that can be used to for testing, anonymization and much more. ZOil was inspired by the [`Faker`](https://github.com/joke2k/faker) library. 

ZOil is [hosted on PyPI](https://pypi.org/project/zoil/) and is installed using `pip`

<br />

```bash
$ pip install zoil
```
