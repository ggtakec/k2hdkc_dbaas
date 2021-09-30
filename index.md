---
layout: default
language: en-us
title: K2HDKC DBaaS
short_desc: Database as a Service for K2HDKC
lang_opp_file: indexja.html
lang_opp_word: To Japanese
arrow_link_overview: <a href="overview.html" class="link-title"><span class="arrow-base link-arrow-right"></span>Overview</a>
arrow_link_whatnew: <a href="whatnew.html" class="link-title"><span class="arrow-base link-arrow-right"></span>What's new</a>
arrow_link_build: <a href="build.html" class="link-title"><span class="arrow-base link-arrow-right"></span>Build a trial environment</a>
arrow_link_usage: <a href="usage.html" class="link-title"><span class="arrow-base link-arrow-right"></span>Usage</a>
---

# **K2HDKC DBaaS**
**K2HDKC DBaaS** (Database as a Service for K2HDKC) is a **Database as a Service** that uses [K2HR3](https://k2hr3.antpick.ax/) and works with [OpenStack](https://www.openstack.org/) and [kubernetes](https://kubernetes.io/) to build a [K2HDKC(K2Hash based Distributed Kvs Cluster)](https://k2hdkc.antpick.ax/index.html) Cluster for distributed KVS.  

We have **two** products for **K2HDKC DBaaS** (Database as a Service for K2HDKC) that cooperates with [OpenStack](https://www.openstack.org/).  

One is **K2HDKC DBaaS** that can be operated from [Trove(Trove is Database as a Service for OpenStack)](https://wiki.openstack.org/wiki/Trove) by incorporating `K2HDKC` as one of the databases managed by [Trove](https://wiki.openstack.org/wiki/Trove).  

The other is a **command line tool** called **K2HDKC DBaaS CLI** (Command Line Interface) that allows you to build up `K2HDKC` cluster directly without using [Trove](https://wiki.openstack.org/wiki/Trove).  

It also provides a **command line tool** called **K2HDKC DBaaS on kubernetes CLI** (Command Line Interface) for building up `K2HDKC` clusters inside [kubernetes](https://kubernetes.io/) clusters.  

**K2HDKC DBaaS** is one of [AntPickax](https://antpick.ax/)'s open source product by Yahoo! JAPAN.  

![K2HDKC DBaaS](images/top_k2hdkc_dbaas.png)

## {{ page.arrow_link_overview }}
[Overview](overview.html) about **K2HDKC DBaaS**.

## {{ page.arrow_link_whatnew }}
What's new about **K2HDKC DBaaS**.

## {{ page.arrow_link_build }}
Only the **K2HDKC DBaaS** (Database as a Service for K2HDKC) which that cooperates with [Trove(Trove is Database as a Service for OpenStack)](https://wiki.openstack.org/wiki/Trove) requires the construction of an environment.  
We explain how to [build](build.html) the **K2HDKC DBaaS** that cooperates with [Trove(Trove is Database as a Service for OpenStack)](https://wiki.openstack.org/wiki/Trove) as trial purposes.  

**K2HDKC DBaaS CLI**(Command Line Interface) requires only [OpenStack](https://www.openstack.org/) system, and can be used immediately after installing the package.  

**K2HDKC DBaaS on kubernetes CLI**(Command Line Interface) also requires only [kubernetes](https://kubernetes.io/) clusters, and can be used immediately after installing the package.  

Each source code is in the [Github](https://github.com/) repository shown below.
- [k2hdkc_dbaas repository](https://github.com/yahoojapan/k2hdkc_dbaas) for cooperating with [Trove(Trove is Database as a Service for OpenStack)](https://wiki.openstack.org/wiki/Trove)
- [k2hdkc_dbaas_cli repository](https://github.com/yahoojapan/k2hdkc_dbaas_cli) is **K2HDKC DBaaS CLI** (Command Line Interface)
- [k2hdkc_dbaas_k8s_cli repository](https://github.com/yahoojapan/k2hdkc_dbaas_k8s_cli) is **K2HDKC DBaaS on kubernetes CLI** (Command Line Interface)

## {{ page.arrow_link_usage }}
How to use **K2HDKC DBaaS** to build/start **K2HDKC cluster** and **K2HDKC slave node** easily.  
- For information on how to use **K2HDKC DBaaS** that works with [Trove(Trove is Database as a Service for OpenStack)](https://wiki.openstack.org/wiki/Trove), see [here](usage.html).
- For how to use **K2HDKC DBaaS CLI**(Command Line Interface), refer to [here](usage_cli.html).
- For how to use **K2HDKC DBaaS on kubernetes CLI**(Command Line Interface), refer to [here](usage_k8s_cli.html).

# About AntPickax
[AntPickax](https://antpick.ax/) is product group that is provided as open source by Yahoo! JAPAN.  
Please see the [AntPickax](https://antpick.ax/) details page.