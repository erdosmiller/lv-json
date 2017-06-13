LV-JSON
=================

LV-JSON is an open source LabVIEW library for parsing and composing JSON strings.

Installation
------------

[The most recent VI Package (.vip) can be downloaded here.](https://github.com/erdosmiller/lv-json/releases)

Open the VI Package using [VI Package Manager](http://vipm.jki.net/) and press ***Install***.

In LabVIEW, The LV-JSON palette can be found in the ***Erdos Miller*** palette.

Usage
-----

***Parse JSON String.vi*** and ***Compose JSON String.vi*** can convert between a JSON string and a ***JSON Value.ctl***. ***JSON Value.ctl*** is an algebraic data type that maps to the JSON type system. It is constructable and caseable using [LV-Tagged-Union](https://github.com/erdosmiller/lv-json/releases). To use this livrary with LV-Tagged-Union, the types ***LV-JSON:JSON Value.ctl*** and ***LV-JSON:JSON Name-Value Pair.ctl*** must be in memory.

Requirements
------------

OpenG Toolkit

MGI Tools

Requires LabVIEW 2015 or later