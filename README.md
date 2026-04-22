### Hi there

A collection of my repositories spanning data engineering, machine learning, DevOps, Qt/QML, Python tooling, robotics, and more.

| Type | Meaning |
|---|---|
| `own` | Created and owned by me |
| `fork` | Fork of an upstream project with substantial own changes |
| `contribution` | Merged pull requests to someone else's upstream project |

---

## Data Engineering

| Repository | Type | Tech | Description / Contributions |
|---|---|---|---|
| [spark-emr](https://github.com/delijati/spark-emr) | own | `Python` `Apache Spark` `AWS EMR` `PySpark` | Spark EMR (Spot) cluster manager for running cost-efficient workloads on AWS. |
| [spark-optimizer](https://github.com/delijati/spark-optimizer) | own | `Python` `Apache Spark` `AWS EMR` | Optimize Apache Spark settings for AWS EMR (spark config cheatsheet). |
| [spark-docker](https://github.com/delijati/spark-docker) | own | `Docker` `Apache Spark` `Hadoop` `AWS` | Docker image bundling Spark, Hadoop, and AWS services for local dev. |
| [pg-tuna](https://github.com/delijati/pg-tuna) | own | `Python` `PostgreSQL` `AWS RDS` | PostgreSQL / AWS RDS configuration wizard -- yet another pgtune. |
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

## Robotics

| Repository | Type | Tech | Description / Contributions |
|---|---|---|---|
| [pysimiam-simulator](https://github.com/delijati/pysimiam-simulator) | own | `Python` `Robotics` | Robot simulator based on the PySimiam framework. |
| [ultrabot](https://github.com/delijati/ultrabot) | own | `Python` `Robotics` | Ultrabot -- a QuickBot sibling for robotics experiments. |
| [quickbot_bbb](https://github.com/delijati/quickbot_bbb) | fork | `Python` `Robotics` `BeagleBone` | QuickBot firmware for the BeagleBone Black -- added outlier detection, threaded ultrasonic measurement, and timing fixes. |

---

## Docker & DevOps

| Repository | Type | Tech | Description / Contributions |
|---|---|---|---|
| [docker-shiv](https://github.com/delijati/docker-shiv) | own | `Docker` `Shell` `Python` `Wine` `Shiv` | Build self-contained Python zipapps (shiv) for Windows using Docker + Wine. |
| [docker-arm-x86](https://github.com/delijati/docker-arm-x86) | own | `Docker` `QEMU` | Run ARM Docker images on an x86 host via QEMU emulation. |
| [pypa/setuptools](https://github.com/pypa/setuptools) | contribution | `Python` `Packaging` | [#3167](https://github.com/pypa/setuptools/pull/3167) Fix `wheel install_as_egg` not honoring file mode |

---

## Ubuntu Touch & Qt / QML / C++

| Repository | Type | Tech | Description / Contributions |
|---|---|---|---|
| [fosdem-qml](https://github.com/delijati/fosdem-qml) | own | `QML` `Ubuntu Touch` `UBports` | FOSDEM schedule app for Ubuntu Touch / UBports. |
| [sparse-qml](https://github.com/delijati/sparse-qml) | own | `Python` `QML` `Qt` `Matrix` `PyOtherSide` | Experimental Matrix protocol client for Ubuntu Touch using QML + Python. |
| [quotient-im/libQuotient](https://github.com/quotient-im/libQuotient) | contribution | `C++` `Matrix` | [#81](https://github.com/quotient-im/libQuotient/pull/81) Add `Connection::leftRoom` signal; [#244](https://github.com/quotient-im/libQuotient/pull/244) Update VoIP call handling |
| [uMatriks/uMatriks](https://github.com/uMatriks/uMatriks) | contribution | `QML` `Ubuntu Touch` `Matrix` | [#42](https://github.com/uMatriks/uMatriks/pull/42) Cleanup & fix ImageProvider; [#49](https://github.com/uMatriks/uMatriks/pull/49)–[#57](https://github.com/uMatriks/uMatriks/pull/57) Sync fixes, room avatar, libqmatrixclient updates; [#70](https://github.com/uMatriks/uMatriks/pull/70) Xenial/master libqmatrixclient |
| [matrix-org/matrix-python-sdk](https://github.com/matrix-org/matrix-python-sdk) | contribution | `Python` `Matrix` | [#142](https://github.com/matrix-org/matrix-python-sdk/pull/142) Add room `display_name`, fix Python 2.7 test compatibility |
| [ubports/webbrowser-app](https://github.com/ubports/webbrowser-app) | contribution | `QML` `Ubuntu Touch` | [#22](https://github.com/ubports/webbrowser-app/pull/22) Add Docker build & run support; [#23](https://github.com/ubports/webbrowser-app/pull/23) Set desktop mode |
| [ubports/stats.ubports.com](https://github.com/ubports/stats.ubports.com) | contribution | `JavaScript` `UBports` | [#4](https://github.com/ubports/stats.ubports.com/pull/4) Add annotated progress graph |
| [TronFortyTwo/OnTheRoad](https://github.com/TronFortyTwo/OnTheRoad) | contribution | `Shell` `Ubuntu Touch` | [#3](https://github.com/TronFortyTwo/OnTheRoad/pull/3) Fix BQ device support, fix scroll, add About page |
| [bhdouglass/clickable](https://github.com/bhdouglass/clickable) | contribution | `Python` `Ubuntu Touch` | [#30](https://github.com/bhdouglass/clickable/pull/30) Python 3 support and pip install documentation |
| [Halium/docs](https://github.com/Halium/docs) | contribution | `Python` `Halium` | [#33](https://github.com/Halium/docs/pull/33) Convert Markdown to reStructuredText with toctree |

---

## REST APIs & Web Frameworks

| Repository | Type | Tech | Description / Contributions |
|---|---|---|---|
| [benchmark](https://github.com/delijati/benchmark) | own | `Python` `Zappa` `WSGI` `ASGI` | Benchmark comparing WSGI vs ASGI performance under Zappa on AWS Lambda. |
| [Cornices/cornice](https://github.com/Cornices/cornice) | contribution | `Python` `Pyramid` `REST` | [#335](https://github.com/Cornices/cornice/pull/335) Add ability to define services imperatively (class-based style) |
| [Pylons/deform](https://github.com/Pylons/deform) | contribution | `Python` `HTML Forms` | [#295](https://github.com/Pylons/deform/pull/295) Update Bootstrap integration; [#529](https://github.com/Pylons/deform/pull/529) Bootstrap 5 + icons migration; [#533](https://github.com/Pylons/deform/pull/533) Prep release |
| [Pylons/deformdemo](https://github.com/Pylons/deformdemo) | contribution | `Python` `Deform` | [#124](https://github.com/Pylons/deformdemo/pull/124)–[#128](https://github.com/Pylons/deformdemo/pull/128) Bootstrap 5 fixes and scroll improvements; [#131](https://github.com/Pylons/deformdemo/pull/131) Prep release 3 |
| [hobbeswalsh/flask-sillywalk](https://github.com/hobbeswalsh/flask-sillywalk) | contribution | `Python` `Flask` `Swagger` | [#14](https://github.com/hobbeswalsh/flask-sillywalk/pull/14) Add model registration, tests, and documentation |
| [KiraPC/fastapi-router-controller](https://github.com/KiraPC/fastapi-router-controller) | contribution | `Python` `FastAPI` | [#8](https://github.com/KiraPC/fastapi-router-controller/pull/8) Add badges, GitHub Actions CI, and pytest; [#10](https://github.com/KiraPC/fastapi-router-controller/pull/10)–[#11](https://github.com/KiraPC/fastapi-router-controller/pull/11) Fixes and inheritance; [#15](https://github.com/KiraPC/fastapi-router-controller/pull/15)–[#16](https://github.com/KiraPC/fastapi-router-controller/pull/16) Class dependencies; [#26](https://github.com/KiraPC/fastapi-router-controller/pull/26) Update Python version |

---

## Web & JavaScript

| Repository | Type | Tech | Description / Contributions |
|---|---|---|---|
| [crabstore](https://github.com/delijati/crabstore) | own | `JavaScript` `Ionic` `Protocol Buffers` | Google Play Store client written in JavaScript using the Ionic framework. |
| [nock/nock](https://github.com/nock/nock) | contribution | `JavaScript` `Testing` | [#834](https://github.com/nock/nock/pull/834) Fix `matchBody` for multipart/form-data requests |
| [fanstatic/js.underscore](https://github.com/fanstatic/js.underscore) | contribution | `JavaScript` `Fanstatic` | [#2](https://github.com/fanstatic/js.underscore/pull/2) Update to underscore.js 1.4.4 |
| [podhmo/js.backbone](https://github.com/podhmo/js.backbone) | contribution | `JavaScript` `Fanstatic` | [#2](https://github.com/podhmo/js.backbone/pull/2) Update to Backbone.js 0.9.10 |

---

## Python Tools & Misc

| Repository | Type | Tech | Description / Contributions |
|---|---|---|---|
| [google/python-adb](https://github.com/google/python-adb) | contribution | `Python` `ADB` | [#84](https://github.com/google/python-adb/pull/84) Add `entry_points` to `setup.py` for CLI tools |
| [peakiq/logma](https://github.com/peakiq/logma) | contribution | `Python` | [#2](https://github.com/peakiq/logma/pull/2) Add PID logging; [#3](https://github.com/peakiq/logma/pull/3) Handle unhandled exceptions in threads; [#5](https://github.com/peakiq/logma/pull/5) Make log processor configurable |
| [pct/vimpyre](https://github.com/pct/vimpyre) | contribution | `Python` `Vim` | [#17](https://github.com/pct/vimpyre/pull/17) Python 2/3 compatibility; [#18](https://github.com/pct/vimpyre/pull/18) Add `get_console_size`, remove redundant code |
| [posativ/weave-minimal](https://github.com/posativ/weave-minimal) | contribution | `Python` `Firefox Sync` | [#12](https://github.com/posativ/weave-minimal/pull/12) Propagate `wsgi.url_scheme` via `HTTP_X_SCHEME` header (proxy support) |
| [charliewolf/pynder](https://github.com/charliewolf/pynder) | contribution | `Python` | [#42](https://github.com/charliewolf/pynder/pull/42) Add unit tests and fix redundant code; [#43](https://github.com/charliewolf/pynder/pull/43) More tests, remove further redundant code |
| [tibonihoo/yapsy](https://github.com/tibonihoo/yapsy) | contribution | `Python` | [#4](https://github.com/tibonihoo/yapsy/pull/4) Python 3 → 2 tab/spaces fix and Flask compatibility |
| [cd34/apex](https://github.com/cd34/apex) | contribution | `Python` | [#75](https://github.com/cd34/apex/pull/75) Add unit tests; [#76](https://github.com/cd34/apex/pull/76) Add Travis CI configuration |
