# Docker-PHP

### 前言
    新手上路感谢各路大神多提提意见。
    本项目用于学些docker搭建PHP开发环境，目前环境使用 nginx+mysql+redis+PHP搭建而，成也就是lnmp环境，目前基本满足常规PHP项目开发使用，在此申明此项目使用于对docker-compose、dockerfile 有一定基础的同学，新人建议先阅读官方入门指南。

### 前瞻

    后续优化点目前定位后续支持 Apache OR nginx 安装切换，PHP不同版本切换，mysql不同版本切换。

### 环境

    在使用前请先安装 docker-compose ，如未安装请上 [docker官网](https://www.docker.com/)根据官方文档安装docker。

### 目录

    app
        elasticsearch
            conf
            data
            plugins
            dockerfile
        kibana
            conf
            data
            dockerfile
        mysql
            conf
            data
            dockerfile    
        nginx
            conf
            log
            dockerfile
        php
            conf
            dockerfile
        redis
            conf
            data
            dockerfile
        site
    docker-compose.yml

