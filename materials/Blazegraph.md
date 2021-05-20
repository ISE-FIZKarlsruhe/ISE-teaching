---
layout: post
title: Quick Start in Blazegraph
excerpt: "Download and setup in Linux"
tags: [blazegraph, download, setup]
comments:false
category:blog
---

## Setup (Linux)

#### Download java

```
sudo apt update
sudo apt install default-jre 
java --version 
sudo apt install default-jdk
javac --version 
```

#### Donwload Blazegraph
https://github.com/blazegraph/database/releases/tag/BLAZEGRAPH_2_1_6_RC
  
download ```blazegraph.jar```
    
#### Run Blazegraph
```
java -server -Xmx4g -jar blazegraph.jar
```

#### Once it started, the default workbench location is http://localhost:9999/blazegraph/

#### For more details in `quick start`
* https://github.com/blazegraph/database/wiki/Quick_Start
  
