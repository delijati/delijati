### Hi there

A collection of my repositories spanning data engineering, machine learning, DevOps, Qt/QML, Python tooling, robotics, and more.
Repos marked with `[fork]` are forks of upstream projects with substantial own changes.

---

## Data Engineering

| Repository | Type | Tech | Description |
|---|---|---|---|
| [spark-emr](https://github.com/delijati/spark-emr) | own | `Python` `Apache Spark` `AWS EMR` `PySpark` | Spark EMR (Spot) cluster manager for running cost-efficient workloads on AWS. |
| [spark-optimizer](https://github.com/delijati/spark-optimizer) | own | `Python` `Apache Spark` `AWS EMR` | Optimize Apache Spark settings for AWS EMR (spark config cheatsheet). |
| [spark-docker](https://github.com/delijati/spark-docker) | own | `Docker` `Apache Spark` `Hadoop` `AWS` | Docker image bundling Spark, Hadoop, and AWS services for local dev. |
| [pg-tuna](https://github.com/delijati/pg-tuna) | own | `Python` `PostgreSQL` `AWS RDS` | PostgreSQL / AWS RDS configuration wizard -- yet another pgtune. |
| [ec2instances.info](https://github.com/delijati/ec2instances.info) | fork | `HTML` `AWS EC2` | Amazon EC2 instance comparison site. |
| [tchotcho](https://github.com/delijati/tchotcho) | own | `Python` `AWS EC2` | Launch and manage EC2 training jobs once local experimentation is done. |

---

## Machine Learning & AI

| Repository | Type | Tech | Description |
|---|---|---|---|
| [pytorch-siamese](https://github.com/delijati/pytorch-siamese) | own | `Python` `PyTorch` `Deep Learning` | Siamese Network implementation with contrastive loss using PyTorch. |
| [memleak](https://github.com/delijati/memleak) | own | `C++` `NumPy` | Demonstration of NumPy / C++ memory leak patterns and how to detect them. |
| [llm-deepseek-ya](https://github.com/delijati/llm-deepseek-ya) | fork | `Python` `LLM` `DeepSeek` | LLM plugin to access DeepSeek's models. |

---

## Robotics

| Repository | Type | Tech | Description |
|---|---|---|---|
| [pysimiam-simulator](https://github.com/delijati/pysimiam-simulator) | own | `Python` `Robotics` | Robot simulator based on the PySimiam framework. |
| [ultrabot](https://github.com/delijati/ultrabot) | own | `Python` `Robotics` | Ultrabot -- a QuickBot sibling for robotics experiments. |
| [quickbot_bbb](https://github.com/delijati/quickbot_bbb) | fork | `Python` `Robotics` `BeagleBone` | QuickBot firmware for the BeagleBone Black. |

---

## Docker & DevOps

| Repository | Type | Tech | Description |
|---|---|---|---|
| [docker-shiv](https://github.com/delijati/docker-shiv) | own | `Docker` `Shell` `Python` `Wine` `Shiv` | Build self-contained Python zipapps (shiv) for Windows using Docker + Wine. |
| [docker-arm-x86](https://github.com/delijati/docker-arm-x86) | own | `Docker` `QEMU` | Run ARM Docker images on an x86 host via QEMU emulation. |

---

## Ubuntu Touch & Qt / QML / C++

| Repository | Type | Tech | Description |
|---|---|---|---|
| [fosdem-qml](https://github.com/delijati/fosdem-qml) | own | `QML` `Ubuntu Touch` `UBports` | FOSDEM schedule app for Ubuntu Touch / UBports. |
| [sparse-qml](https://github.com/delijati/sparse-qml) | own | `Python` `QML` `Qt` `Matrix` `PyOtherSide` | Experimental Matrix protocol client for Ubuntu Touch using QML + Python. |

---

## REST APIs & Web Frameworks

| Repository | Type | Tech | Description |
|---|---|---|---|
| [benchmark](https://github.com/delijati/benchmark) | own | `Python` `Zappa` `WSGI` `ASGI` | Benchmark comparing WSGI vs ASGI performance under Zappa on AWS Lambda. |

---

## Web & JavaScript

| Repository | Type | Tech | Description |
|---|---|---|---|
| [crabstore](https://github.com/delijati/crabstore) | own | `JavaScript` `Ionic` `Protocol Buffers` | Google Play Store client written in JavaScript using the Ionic framework. |

---

## Contributions

Merged pull requests to upstream open-source projects.

| Repository | Tech | Contributions |
|---|---|---|
| [fsspec/s3fs](https://github.com/fsspec/s3fs) | `Python` `AWS S3` | [#140](https://github.com/fsspec/s3fs/pull/140) Add `region_name` to `create_bucket` |
| [vantage-sh/ec2instances.info](https://github.com/vantage-sh/ec2instances.info) | `HTML` `AWS EC2` | [#349](https://github.com/vantage-sh/ec2instances.info/pull/349) Add EMR support; [#511](https://github.com/vantage-sh/ec2instances.info/pull/511) GPU count and CUDA cores |
| [pypa/setuptools](https://github.com/pypa/setuptools) | `Python` `Packaging` | [#3167](https://github.com/pypa/setuptools/pull/3167) Fix `wheel install_as_egg` not honoring file mode |
| [quotient-im/libQuotient](https://github.com/quotient-im/libQuotient) | `C++` `Matrix` | [#81](https://github.com/quotient-im/libQuotient/pull/81) Add `Connection::leftRoom` signal; [#244](https://github.com/quotient-im/libQuotient/pull/244) Updated VoIP pull request |
| [uMatriks/uMatriks](https://github.com/uMatriks/uMatriks) | `QML` `Ubuntu Touch` `Matrix` | [#42](https://github.com/uMatriks/uMatriks/pull/42) Cleanup & fix ImageProvider; [#49](https://github.com/uMatriks/uMatriks/pull/49)–[#57](https://github.com/uMatriks/uMatriks/pull/57) Sync fixes, room avatar, libqmatrixclient updates; [#70](https://github.com/uMatriks/uMatriks/pull/70) Xenial master libqmatrixclient |
| [matrix-org/matrix-python-sdk](https://github.com/matrix-org/matrix-python-sdk) | `Python` `Matrix` | [#142](https://github.com/matrix-org/matrix-python-sdk/pull/142) Add room `display_name`, fix Python 2.7 tests |
| [ubports/webbrowser-app](https://github.com/ubports/webbrowser-app) | `QML` `Ubuntu Touch` | [#22](https://github.com/ubports/webbrowser-app/pull/22) Build and run with Docker; [#23](https://github.com/ubports/webbrowser-app/pull/23) Set desktop mode |
| [ubports/stats.ubports.com](https://github.com/ubports/stats.ubports.com) | `JavaScript` `UBports` | [#4](https://github.com/ubports/stats.ubports.com/pull/4) Add annotated progress graph |
| [TronFortyTwo/OnTheRoad](https://github.com/TronFortyTwo/OnTheRoad) | `Shell` `Ubuntu Touch` | [#3](https://github.com/TronFortyTwo/OnTheRoad/pull/3) Fix BQ; fix scroll; add About page |
| [bhdouglass/clickable](https://github.com/bhdouglass/clickable) | `Python` `Ubuntu Touch` | [#30](https://github.com/bhdouglass/clickable/pull/30) Python 3 and pip install support |
| [Halium/docs](https://github.com/Halium/docs) | `Python` `Halium` | [#33](https://github.com/Halium/docs/pull/33) Convert Markdown to reStructuredText |
| [google/python-adb](https://github.com/google/python-adb) | `Python` `ADB` | [#84](https://github.com/google/python-adb/pull/84) Add `entry_points` to `setup.py` |
| [Cornices/cornice](https://github.com/Cornices/cornice) | `Python` `Pyramid` `REST` | [#335](https://github.com/Cornices/cornice/pull/335) Add ability to define services imperatively |
| [Pylons/deform](https://github.com/Pylons/deform) | `Python` `HTML Forms` | [#295](https://github.com/Pylons/deform/pull/295) Updated Bootstrap; [#529](https://github.com/Pylons/deform/pull/529) Bootstrap 5 + icons; [#533](https://github.com/Pylons/deform/pull/533) Prep release |
| [Pylons/deformdemo](https://github.com/Pylons/deformdemo) | `Python` `Deform` | [#124](https://github.com/Pylons/deformdemo/pull/124)–[#128](https://github.com/Pylons/deformdemo/pull/128) Bootstrap 5 fixes and scroll improvements; [#131](https://github.com/Pylons/deformdemo/pull/131) Prep release 3 |
| [hobbeswalsh/flask-sillywalk](https://github.com/hobbeswalsh/flask-sillywalk) | `Python` `Flask` `Swagger` | [#14](https://github.com/hobbeswalsh/flask-sillywalk/pull/14) Added features and tests |
| [KiraPC/fastapi-router-controller](https://github.com/KiraPC/fastapi-router-controller) | `Python` `FastAPI` | [#8](https://github.com/KiraPC/fastapi-router-controller/pull/8) Badges, CI, tests; [#10](https://github.com/KiraPC/fastapi-router-controller/pull/10)–[#11](https://github.com/KiraPC/fastapi-router-controller/pull/11) Fixes and inheritance; [#15](https://github.com/KiraPC/fastapi-router-controller/pull/15)–[#16](https://github.com/KiraPC/fastapi-router-controller/pull/16) Class dependencies; [#26](https://github.com/KiraPC/fastapi-router-controller/pull/26) Python version update |
| [peakiq/logma](https://github.com/peakiq/logma) | `Python` | [#2](https://github.com/peakiq/logma/pull/2) Add PID logging; [#3](https://github.com/peakiq/logma/pull/3) Unhandled exception handling; [#5](https://github.com/peakiq/logma/pull/5) Configurable processor |
| [pct/vimpyre](https://github.com/pct/vimpyre) | `Python` `Vim` | [#17](https://github.com/pct/vimpyre/pull/17) Python 2/3 support; [#18](https://github.com/pct/vimpyre/pull/18) Various updates |
| [posativ/weave-minimal](https://github.com/posativ/weave-minimal) | `Python` `Firefox Sync` | [#12](https://github.com/posativ/weave-minimal/pull/12) Set `wsgi.url_scheme` via `HTTP_X_SCHEME` header |
| [nock/nock](https://github.com/nock/nock) | `JavaScript` `Testing` | [#834](https://github.com/nock/nock/pull/834) Fix `matchBody` for multipart requests |
| [fanstatic/js.underscore](https://github.com/fanstatic/js.underscore) | `JavaScript` `Fanstatic` | [#2](https://github.com/fanstatic/js.underscore/pull/2) Update to underscore.js 1.4.4 |
| [podhmo/js.backbone](https://github.com/podhmo/js.backbone) | `JavaScript` `Fanstatic` | [#2](https://github.com/podhmo/js.backbone/pull/2) Update to Backbone.js 0.9.10 |
| [charliewolf/pynder](https://github.com/charliewolf/pynder) | `Python` | [#42](https://github.com/charliewolf/pynder/pull/42) Unit tests and fixes; [#43](https://github.com/charliewolf/pynder/pull/43) More tests, remove redundant code |
| [tibonihoo/yapsy](https://github.com/tibonihoo/yapsy) | `Python` | [#4](https://github.com/tibonihoo/yapsy/pull/4) Python 3 to Python 2 compatibility + Flask fix |
| [cd34/apex](https://github.com/cd34/apex) | `Python` | [#75](https://github.com/cd34/apex/pull/75) Add tests; [#76](https://github.com/cd34/apex/pull/76) Add Travis CI |
