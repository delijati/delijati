### Hi there

A collection of my repositories spanning data engineering, machine learning, DevOps, Qt/QML, Python tooling, robotics, and more.

| Type | Meaning |
|---|---|
| `own` | Created and owned by me |
| `maintainer` | Upstream project I actively co-maintain |
| `fork` | Fork with substantial personal changes |
| `contribution` | Merged pull requests to someone else's project |

---

## Data Engineering

| Repository | Type | Tech | Description |
|---|---|---|---|
| [spark-emr](https://github.com/delijati/spark-emr) | own | `Python` `Apache Spark` `AWS EMR` `PySpark` | Spark EMR (Spot) cluster manager for running cost-efficient workloads on AWS. |
| [spark-optimizer](https://github.com/delijati/spark-optimizer) | own | `Python` `Apache Spark` `AWS EMR` | Optimize Apache Spark settings for AWS EMR (spark config cheatsheet). |
| [spark-docker](https://github.com/delijati/spark-docker) | own | `Docker` `Apache Spark` `Hadoop` `AWS` | Docker image bundling Spark, Hadoop, and AWS services for local dev. |
| [pg-tuna](https://github.com/delijati/pg-tuna) | own | `Python` `PostgreSQL` `AWS RDS` | PostgreSQL / AWS RDS configuration wizard -- yet another pgtune. |
| [tchotcho](https://github.com/delijati/tchotcho) | own | `Python` `AWS EC2` | Launch and manage EC2 training jobs once local experimentation is done. |
| [botocore](https://github.com/delijati/botocore) | fork | `Python` `AWS` | The low-level, core functionality of boto 3 -- added async callback support to the waiter API. |
| [ec2instances.info](https://github.com/delijati/ec2instances.info) | fork | `HTML` `AWS EC2` | Amazon EC2 instance comparison site -- added EMR support and GPU/CUDA core data. |

---

## Machine Learning & AI

| Repository | Type | Tech | Description |
|---|---|---|---|
| [pytorch-siamese](https://github.com/delijati/pytorch-siamese) | own | `Python` `PyTorch` `Deep Learning` | Siamese Network implementation with contrastive loss using PyTorch. |
| [memleak](https://github.com/delijati/memleak) | own | `C++` `NumPy` | Demonstration of NumPy / C++ memory leak patterns and how to detect them. |
| [llm-deepseek-ya](https://github.com/delijati/llm-deepseek-ya) | fork | `Python` `LLM` `DeepSeek` | LLM plugin to access DeepSeek's models -- updated package name, docs, and model registration. |

---

## Robotics

| Repository | Type | Tech | Description |
|---|---|---|---|
| [pysimiam-simulator](https://github.com/delijati/pysimiam-simulator) | own | `Python` `Robotics` | Robot simulator based on the PySimiam framework. |
| [ultrabot](https://github.com/delijati/ultrabot) | own | `Python` `Robotics` | Ultrabot -- a QuickBot sibling for robotics experiments. |
| [quickbot_bbb](https://github.com/delijati/quickbot_bbb) | fork | `Python` `Robotics` `BeagleBone` | QuickBot firmware for the BeagleBone Black -- added outlier detection, threaded ultrasonic measurement, and timing improvements. |

---

## Docker & DevOps

| Repository | Type | Tech | Description |
|---|---|---|---|
| [docker-shiv](https://github.com/delijati/docker-shiv) | own | `Docker` `Shell` `Python` `Wine` `Shiv` | Build self-contained Python zipapps (shiv) for Windows using Docker + Wine. |
| [docker-arm-x86](https://github.com/delijati/docker-arm-x86) | own | `Docker` `QEMU` | Run ARM Docker images on an x86 host via QEMU emulation. |
| [Zappa](https://github.com/delijati/Zappa) | fork | `Python` `Serverless` `AWS Lambda` | Serverless Python -- added ASGI support for deploying async Python apps. |
| [pyinstaller](https://github.com/delijati/pyinstaller) | fork | `Python` `Packaging` | Freeze Python programs into stand-alone executables -- fixed soundfile hook on Windows to include only the required DLL. |
| [specchio](https://github.com/delijati/specchio) | fork | `Python` `rsync` | Auto-sync your code using .gitignore rules -- ported to Python 3 only, migrated CI from Travis to GitHub Actions. |
| [cosent.buildtools](https://github.com/delijati/cosent.buildtools) | fork | `Python` `buildout` | Release scripts for buildout-based projects -- Python 3 compatibility, extended defaults, and additional tests. |
| [setuptools](https://github.com/delijati/setuptools) | fork | `Python` `Packaging` | Official repository for the Setuptools build system -- fixed `wheel install_as_egg` not honoring file modes. |

---

## Qt / QML / C++

| Repository | Type | Tech | Description |
|---|---|---|---|
| [fosdem-qml](https://github.com/delijati/fosdem-qml) | own | `QML` `Ubuntu Touch` `UBports` | FOSDEM schedule app for Ubuntu Touch / UBports. |
| [sparse-qml](https://github.com/delijati/sparse-qml) | own | `Python` `QML` `Qt` `Matrix` `PyOtherSide` | Experimental Matrix protocol client for Ubuntu Touch using QML + Python. |
| [tensor](https://github.com/delijati/tensor) | fork | `QML` `Qt5` `Matrix` | Cross-platform Qt5/QML-based Matrix client -- fixed room join/leave model updates, updated libqmatrixclient submodule. |
| [uMatriks](https://github.com/delijati/uMatriks) | fork | `QML` `Ubuntu Touch` `Matrix` | Matrix protocol client for Ubuntu Touch -- fixed sync, room avatars, ImageProvider, and libqmatrixclient compatibility. |

---

## Ubuntu Touch & UBports

| Repository | Type | Tech | Description |
|---|---|---|---|
| [geocaching](https://github.com/delijati/geocaching) | fork | `Python` `Ubuntu Touch` | Geocaching.com (unofficial) app for Ubuntu Touch -- updated for 2024 API changes. |
| [stats.ubports.com](https://github.com/delijati/stats.ubports.com) | fork | `JavaScript` `UBports` | Active device statistics for Ubuntu Touch -- added annotated progress graph and hourly aggregation. |
| [OnTheRoad](https://github.com/delijati/OnTheRoad) | fork | `Shell` `Ubuntu Touch` | Development tool for Ubuntu Touch -- added About page, QProcess-based execution, and improved QML structure. |
| [clickable](https://github.com/delijati/clickable) | fork | `Python` `Ubuntu Touch` | Compile, build, and deploy Ubuntu Touch click packages -- added Python 3 and pip install support. |
| [docs](https://github.com/delijati/docs) | fork | `Python` `Halium` | Documentation for the Halium project -- converted all Markdown to reStructuredText with toctree support. |

---

## Python Tools & Plugins

| Repository | Type | Tech | Description |
|---|---|---|---|
| [vim-importmagic](https://github.com/delijati/vim-importmagic) | own | `Python` `Vim` | Vim plugin that uses importmagic to auto-import missing Python modules. |
| [vim-buivir](https://github.com/delijati/vim-buivir) | own | `Python` `Vim` `virtualenv` `buildout` | Vim plugin to activate a buildout or virtualenv environment from within Vim. |
| [vimeval](https://github.com/delijati/vimeval) | own | `Python` `Vim` | Evaluate Python expressions directly inside Vim. |
| [kinto_swagger](https://github.com/delijati/kinto_swagger) | own | `Python` `Kinto` `Swagger` `REST` | Swagger / OpenAPI integration plugin for the Kinto storage service. |
| [cookiecutter-cornice_swagger](https://github.com/delijati/cookiecutter-cornice_swagger) | own | `Python` `Cookiecutter` `Cornice` `Swagger` | Cookiecutter template for bootstrapping a Cornice + Swagger API. |
| [vimpyre](https://github.com/delijati/vimpyre) | fork | `Python` `Vim` | Vim Scripts Manager -- added Python 2/3 support, `get_console_size`, and various fixes. |
| [webalchemy](https://github.com/delijati/webalchemy) | fork | `Python` `Web` | Modern web development with Python -- revived and updated for Python 3. |
| [weave-minimal](https://github.com/delijati/weave-minimal) | fork | `Python` `Firefox Sync` | Lightweight Firefox Weave/Sync server -- added `wsgi.url_scheme` propagation via `HTTP_X_SCHEME` header and tests. |

---

## REST APIs & Web Frameworks

| Repository | Type | Tech | Description |
|---|---|---|---|
| [benchmark](https://github.com/delijati/benchmark) | own | `Python` `Zappa` `WSGI` `ASGI` | Benchmark comparing WSGI vs ASGI performance under Zappa on AWS Lambda. |
| [flask-sqlalchemy](https://github.com/delijati/flask-sqlalchemy) | fork | `Python` `Flask` `SQLAlchemy` | Adds SQLAlchemy support to Flask -- used unique MetaData objects per bind. |
| [flask-sillywalk](https://github.com/delijati/flask-sillywalk) | fork | `Python` `Flask` `Swagger` | Flask extension implementing Swagger / OpenAPI support -- added model registration, tests, and documentation. |
| [deform](https://github.com/delijati/deform) | maintainer | `Python` `HTML Forms` | Python HTML form library -- co-maintaining the Pylons project; Bootstrap 5 migration, test fixes, and release prep. |
| [deformdemo](https://github.com/delijati/deformdemo) | maintainer | `Python` `Deform` | Demo application for the Deform form generation framework -- co-maintaining; Bootstrap 5 scroll/test fixes and release prep. |
| [colander](https://github.com/delijati/colander) | fork | `Python` `Serialization` | Serialization/deserialization/validation library for Python -- fixed typos and contributor list. |
| [fastapi-router-controller](https://github.com/delijati/fastapi-router-controller) | maintainer | `Python` `FastAPI` | FastAPI utility for Controller Class-style routing -- co-maintaining; CI setup, class dependencies, inheritance fixes, and version updates. |

---

## Web & JavaScript

| Repository | Type | Tech | Description |
|---|---|---|---|
| [crabstore](https://github.com/delijati/crabstore) | own | `JavaScript` `Ionic` `Protocol Buffers` | Google Play Store client written in JavaScript using the Ionic framework. |
| [js.select2](https://github.com/delijati/js.select2) | own | `JavaScript` `Fanstatic` | Packages the Select2 jQuery plugin as a Fanstatic resource for Python web apps. |

---

## Other

| Repository | Type | Tech | Description |
|---|---|---|---|
| [traffic](https://github.com/delijati/traffic) | own | - | Traffic-related experiments and utilities. |

---

## Contributions

Merged pull requests to upstream open-source projects.

| Repository | Tech | Merged PRs |
|---|---|---|
| [fsspec/s3fs](https://github.com/fsspec/s3fs) | `Python` `AWS S3` | [#140](https://github.com/fsspec/s3fs/pull/140) Add `region_name` parameter to `create_bucket` |
| [vantage-sh/ec2instances.info](https://github.com/vantage-sh/ec2instances.info) | `HTML` `AWS EC2` | [#349](https://github.com/vantage-sh/ec2instances.info/pull/349) Add EMR support; [#511](https://github.com/vantage-sh/ec2instances.info/pull/511) Add GPU count and CUDA core data |
| [pypa/setuptools](https://github.com/pypa/setuptools) | `Python` `Packaging` | [#3167](https://github.com/pypa/setuptools/pull/3167) Fix `wheel install_as_egg` not honoring file mode |
| [quotient-im/libQuotient](https://github.com/quotient-im/libQuotient) | `C++` `Matrix` | [#81](https://github.com/quotient-im/libQuotient/pull/81) Add `Connection::leftRoom` signal; [#244](https://github.com/quotient-im/libQuotient/pull/244) Update VoIP implementation |
| [uMatriks/uMatriks](https://github.com/uMatriks/uMatriks) | `QML` `Ubuntu Touch` `Matrix` | [#42](https://github.com/uMatriks/uMatriks/pull/42) Cleanup & fix ImageProvider; [#49](https://github.com/uMatriks/uMatriks/pull/49)–[#57](https://github.com/uMatriks/uMatriks/pull/57) Sync fixes, room avatar, libqmatrixclient updates; [#70](https://github.com/uMatriks/uMatriks/pull/70) Xenial/master libqmatrixclient |
| [matrix-org/matrix-python-sdk](https://github.com/matrix-org/matrix-python-sdk) | `Python` `Matrix` | [#142](https://github.com/matrix-org/matrix-python-sdk/pull/142) Add room `display_name`, fix Python 2.7 test compatibility |
| [ubports/webbrowser-app](https://github.com/ubports/webbrowser-app) | `QML` `Ubuntu Touch` | [#22](https://github.com/ubports/webbrowser-app/pull/22) Add Docker build & run support; [#23](https://github.com/ubports/webbrowser-app/pull/23) Set desktop mode |
| [ubports/stats.ubports.com](https://github.com/ubports/stats.ubports.com) | `JavaScript` `UBports` | [#4](https://github.com/ubports/stats.ubports.com/pull/4) Add annotated progress graph |
| [TronFortyTwo/OnTheRoad](https://github.com/TronFortyTwo/OnTheRoad) | `Shell` `Ubuntu Touch` | [#3](https://github.com/TronFortyTwo/OnTheRoad/pull/3) Fix BQ device support, fix scroll, add About page |
| [bhdouglass/clickable](https://github.com/bhdouglass/clickable) | `Python` `Ubuntu Touch` | [#30](https://github.com/bhdouglass/clickable/pull/30) Python 3 support and pip install documentation |
| [Halium/docs](https://github.com/Halium/docs) | `Python` `Halium` | [#33](https://github.com/Halium/docs/pull/33) Convert Markdown to reStructuredText with toctree |
| [google/python-adb](https://github.com/google/python-adb) | `Python` `ADB` | [#84](https://github.com/google/python-adb/pull/84) Add `entry_points` to `setup.py` for CLI tools |
| [Cornices/cornice](https://github.com/Cornices/cornice) | `Python` `Pyramid` `REST` | [#335](https://github.com/Cornices/cornice/pull/335) Add ability to define services imperatively (class-based style) |
| [Pylons/deform](https://github.com/Pylons/deform) | `Python` `HTML Forms` | [#295](https://github.com/Pylons/deform/pull/295) Update Bootstrap integration; [#529](https://github.com/Pylons/deform/pull/529) Bootstrap 5 + icons migration; [#533](https://github.com/Pylons/deform/pull/533) Prep release |
| [Pylons/deformdemo](https://github.com/Pylons/deformdemo) | `Python` `Deform` | [#124](https://github.com/Pylons/deformdemo/pull/124) Bootstrap 5 + icons; [#125](https://github.com/Pylons/deformdemo/pull/125) Fix multiselect test; [#126](https://github.com/Pylons/deformdemo/pull/126) Bootstrap 5 scroll into view; [#127](https://github.com/Pylons/deformdemo/pull/127) Scroll + perform + sleep; [#128](https://github.com/Pylons/deformdemo/pull/128) Add manual scroll; [#131](https://github.com/Pylons/deformdemo/pull/131) Prep release 3 |
| [hobbeswalsh/flask-sillywalk](https://github.com/hobbeswalsh/flask-sillywalk) | `Python` `Flask` `Swagger` | [#14](https://github.com/hobbeswalsh/flask-sillywalk/pull/14) Add model registration (`add_registerModel`), tests, and documentation |
| [KiraPC/fastapi-router-controller](https://github.com/KiraPC/fastapi-router-controller) | `Python` `FastAPI` | [#8](https://github.com/KiraPC/fastapi-router-controller/pull/8) Add badges, GitHub Actions CI, and pytest; [#10](https://github.com/KiraPC/fastapi-router-controller/pull/10) Fix keyword argument handling; [#11](https://github.com/KiraPC/fastapi-router-controller/pull/11) Version bump; [#15](https://github.com/KiraPC/fastapi-router-controller/pull/15) Add imperative style and fix inheritance; [#16](https://github.com/KiraPC/fastapi-router-controller/pull/16) Add class-level dependencies; [#26](https://github.com/KiraPC/fastapi-router-controller/pull/26) Update Python version, use `pyproject.toml` |
| [peakiq/logma](https://github.com/peakiq/logma) | `Python` | [#2](https://github.com/peakiq/logma/pull/2) Add PID logging for every process; [#3](https://github.com/peakiq/logma/pull/3) Handle unhandled exceptions in threads and processes; [#5](https://github.com/peakiq/logma/pull/5) Make log processor configurable |
| [pct/vimpyre](https://github.com/pct/vimpyre) | `Python` `Vim` | [#17](https://github.com/pct/vimpyre/pull/17) Python 2/3 compatibility; [#18](https://github.com/pct/vimpyre/pull/18) Add `get_console_size`, remove redundant code |
| [posativ/weave-minimal](https://github.com/posativ/weave-minimal) | `Python` `Firefox Sync` | [#12](https://github.com/posativ/weave-minimal/pull/12) Propagate `wsgi.url_scheme` using `HTTP_X_SCHEME` header (proxy support) |
| [nock/nock](https://github.com/nock/nock) | `JavaScript` `Testing` | [#834](https://github.com/nock/nock/pull/834) Fix `matchBody` for multipart/form-data requests |
| [fanstatic/js.underscore](https://github.com/fanstatic/js.underscore) | `JavaScript` `Fanstatic` | [#2](https://github.com/fanstatic/js.underscore/pull/2) Update to underscore.js 1.4.4 |
| [podhmo/js.backbone](https://github.com/podhmo/js.backbone) | `JavaScript` `Fanstatic` | [#2](https://github.com/podhmo/js.backbone/pull/2) Update to Backbone.js 0.9.10 |
| [charliewolf/pynder](https://github.com/charliewolf/pynder) | `Python` | [#42](https://github.com/charliewolf/pynder/pull/42) Add unit tests and fix redundant code; [#43](https://github.com/charliewolf/pynder/pull/43) Add more tests, remove further redundant code |
| [tibonihoo/yapsy](https://github.com/tibonihoo/yapsy) | `Python` | [#4](https://github.com/tibonihoo/yapsy/pull/4) Python 3 → 2 tab/spaces fix and Flask compatibility fix |
| [cd34/apex](https://github.com/cd34/apex) | `Python` | [#75](https://github.com/cd34/apex/pull/75) Add unit tests; [#76](https://github.com/cd34/apex/pull/76) Add Travis CI configuration |
