### Hi there

A collection of my repositories spanning data engineering, machine learning, DevOps, Qt/QML, Python tooling, robotics, and more.

| Type | Meaning |
|---|---|
| `own` | Created and owned by me |
| `fork` | Fork of an upstream project with substantial own changes |
| `contribution` | Merged pull requests to someone else's upstream project |
| `maintainer` | Upstream project I actively co-maintain |

---

## Data Engineering

| Repository | Type | Tech | Description / Contributions |
|---|---|---|---|
| [spark-emr](https://github.com/delijati/spark-emr) | own | `Python` `Apache Spark` `AWS EMR` `PySpark` | Spark EMR (Spot) cluster manager for running cost-efficient workloads on AWS. |
| [spark-optimizer](https://github.com/delijati/spark-optimizer) | own | `Python` `Apache Spark` `AWS EMR` | Optimize Apache Spark settings for AWS EMR (spark config cheatsheet). |
| [spark-docker](https://github.com/delijati/spark-docker) | own | `Docker` `Apache Spark` `Hadoop` `AWS` | Docker image bundling Spark, Hadoop, and AWS services for local dev. |
| [pg-tuna](https://github.com/delijati/pg-tuna) | own | `Python` `PostgreSQL` `AWS RDS` | PostgreSQL / AWS RDS configuration wizard -- yet another pgtune. |
| [scorched](https://github.com/lugensa/scorched) | maintainer | `Python` `SOLR` `Lucene` |  Sunburnt offspring SOLR client |
| [tchotcho](https://github.com/delijati/tchotcho) | own | `Python` `AWS EC2` | Launch and manage EC2 training jobs once local experimentation is done. |
| [ec2instances.info](https://github.com/delijati/ec2instances.info) | fork | `HTML` `AWS EC2` | Amazon EC2 instance comparison site -- personal fork for local dev and experiments. |
| [fsspec/s3fs](https://github.com/fsspec/s3fs) | contribution | `Python` `AWS S3` | [#140](https://github.com/fsspec/s3fs/pull/140) Add `region_name` parameter to `create_bucket` |
| [vantage-sh/ec2instances.info](https://github.com/vantage-sh/ec2instances.info) | contribution | `HTML` `AWS EC2` | [#349](https://github.com/vantage-sh/ec2instances.info/pull/349) Add EMR support; [#511](https://github.com/vantage-sh/ec2instances.info/pull/511) Add GPU count and CUDA core columns |

---

## Machine Learning & AI

| Repository | Type | Tech | Description / Contributions |
|---|---|---|---|
| [pytorch-siamese](https://github.com/delijati/pytorch-siamese) | own | `Python` `PyTorch` `Deep Learning` | Siamese Network implementation with contrastive loss using PyTorch. |
| [memleak](https://github.com/delijati/memleak) | own | `C++` `NumPy` | Demonstration of NumPy / C++ memory leak patterns and how to detect them. |
| [llm-deepseek-ya](https://github.com/delijati/llm-deepseek-ya) | fork | `Python` `LLM` `DeepSeek` | LLM plugin to access DeepSeek's models -- updated package name, docs, and model registration. |

---

## Docker & DevOps

| Repository | Type | Tech | Description / Contributions |
|---|---|---|---|
| [docker-shiv](https://github.com/delijati/docker-shiv) | own | `Docker` `Shell` `Python` `Wine` `Shiv` | Build self-contained Python zipapps (shiv) for Windows using Docker + Wine. |
| [docker-arm-x86](https://github.com/delijati/docker-arm-x86) | own | `Docker` `QEMU` | Run ARM Docker images on an x86 host via QEMU emulation. |
| [pypa/setuptools](https://github.com/pypa/setuptools) | contribution | `Python` `Packaging` | [#3167](https://github.com/pypa/setuptools/pull/3167) Fix `wheel install_as_egg` not honoring file mode |

---

## REST APIs & Web Frameworks

| Repository | Type | Tech | Description / Contributions |
|---|---|---|---|
| [benchmark](https://github.com/delijati/benchmark) | own | `Python` `Zappa` `WSGI` `ASGI` | Benchmark comparing WSGI vs ASGI performance under Zappa on AWS Lambda. |
| [Pylons/deform](https://github.com/Pylons/deform) | maintainer | `Python` `HTML Forms` |  A Python HTML form library.  |
| [hobbeswalsh/flask-sillywalk](https://github.com/hobbeswalsh/flask-sillywalk) | contribution | `Python` `Flask` `Swagger` | [#14](https://github.com/hobbeswalsh/flask-sillywalk/pull/14) Add model registration, tests, and documentation |
| [KiraPC/fastapi-router-controller](https://github.com/KiraPC/fastapi-router-controller) | maintainer | `Python` `FastAPI` |  A FastAPI utility to allow Controller Class usage |

---

## Web & JavaScript

| Repository | Type | Tech | Description / Contributions |
|---|---|---|---|
| [crabstore](https://github.com/delijati/crabstore) | own | `JavaScript` `Ionic` `Protocol Buffers` | Google Play Store client written in JavaScript using the Ionic framework. |
| [nock/nock](https://github.com/nock/nock) | contribution | `JavaScript` `Testing` | [#834](https://github.com/nock/nock/pull/834) Fix `matchBody` for multipart/form-data requests |

---

## Python Tools & Misc

| Repository | Type | Tech | Description / Contributions |
|---|---|---|---|
| [google/python-adb](https://github.com/google/python-adb) | contribution | `Python` `ADB` | [#84](https://github.com/google/python-adb/pull/84) Add `entry_points` to `setup.py` for CLI tools |
| [peakiq/logma](https://github.com/peakiq/logma) | maintainer | `Python` |  structlog defaults for machines not for humans  |


## Ubuntu Touch & Qt / QML / C++

| Repository | Type | Tech | Description / Contributions |
|---|---|---|---|
| [fosdem-qml](https://github.com/delijati/fosdem-qml) | own | `QML` `Ubuntu Touch` `UBports` | FOSDEM schedule app for Ubuntu Touch / UBports. |
| [sparse-qml](https://github.com/delijati/sparse-qml) | own | `Python` `QML` `Qt` `Matrix` `PyOtherSide` | Experimental Matrix protocol client for Ubuntu Touch using QML + Python. |
| [quotient-im/libQuotient](https://github.com/quotient-im/libQuotient) | contribution | `C++` `Matrix` | [#81](https://github.com/quotient-im/libQuotient/pull/81) Add `Connection::leftRoom` signal; [#244](https://github.com/quotient-im/libQuotient/pull/244) Update VoIP call handling |
| [uMatriks/uMatriks](https://github.com/uMatriks/uMatriks) | maintainer | `QML` `Ubuntu Touch` `Matrix` |  uMatriks is a Matrix protocol client for Ubuntu Touch. (unmaintained) |
| [matrix-org/matrix-python-sdk](https://github.com/matrix-org/matrix-python-sdk) | contribution | `Python` `Matrix` | [#142](https://github.com/matrix-org/matrix-python-sdk/pull/142) Add room `display_name`, fix Python 2.7 test compatibility |
| [ubports/webbrowser-app](https://github.com/ubports/webbrowser-app) | contribution | `QML` `Ubuntu Touch` | [#22](https://github.com/ubports/webbrowser-app/pull/22) Add Docker build & run support; [#23](https://github.com/ubports/webbrowser-app/pull/23) Set desktop mode |
| [bhdouglass/clickable](https://github.com/bhdouglass/clickable) | contribution | `Python` `Ubuntu Touch` | [#30](https://github.com/bhdouglass/clickable/pull/30) Python 3 support and pip install documentation |

---

## Robotics

| Repository | Type | Tech | Description / Contributions |
|---|---|---|---|
| [pysimiam-simulator](https://github.com/delijati/pysimiam-simulator) | own | `Python` `Robotics` | Robot simulator based on the PySimiam framework. |
| [ultrabot](https://github.com/delijati/ultrabot) | own | `Python` `Robotics` | Ultrabot -- a QuickBot sibling for robotics experiments. |
| [quickbot_bbb](https://github.com/delijati/quickbot_bbb) | fork | `Python` `Robotics` `BeagleBone` | QuickBot firmware for the BeagleBone Black -- added outlier detection, threaded ultrasonic measurement, and timing fixes. |


