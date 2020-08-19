<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="./static/icon.png" alt="Project logo" ></a>
 <br>

</p>

<h3 align="center">Spark tutorial</h3>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![GitHub Issues](https://img.shields.io/github/issues/da-huin/spark-tutorial.svg)](https://github.com/da-huin/spark-tutorial/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/da-huin/spark-tutorial.svg)](https://github.com/da-huin/spark-tutorial/pulls)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center"> 
    <br> Tutorial of Spark.
</p>

## 📝 Table of Contents

- [Getting Started](#getting_started)
- [Acknowledgments](#acknowledgement)

## 🏁 Getting Started <a name = "getting_started"></a>

This document explains how to install Spark and how to basic use it.

### Tutorial

1. **Run Jupyter Notebook docker including Spark.**

    ```bash
    docker run -d -v $pwd/workspace:/workspace -p 8888:8888 -it --rm --name lab dahuin000/lab

    docker logs -f lab
    ```

1. **Copy URL in logs. and connect your jupyterlab**

    ```
    ...

    To access the notebook, open this file in a browser:
        file:///root/.local/share/jupyter/runtime/nbserver-6-open.html
    Or copy and paste one of these URLs:
        http://eb0f1e427c67:8888/?token=3ba1fcdb7fec3680476b3fa2d8cea155e693a409939a74b8
     or http://127.0.0.1:8888/?token=3ba1fcdb7fec3680476b3fa2d8cea155e693a409939a74b8

    ...
    ```

1. **Move wokring directory (/workspace)**

1. 

### Reference

1. **What is Spark?**

    1. Spark is set of libraries that process data in parallel in a clustered environment.

    2. Spark usally runs on hadoop, but can also run on others.

    3. Spark API consists of `unstructured API` and `structured API`


## **Tutorial is over 😀**
