XLA Lite
======

[TOC]

# Introduction

XLA(Accelerated Linear Algebra) is an outstanding compiler for DNN projects. It has well-defined and stable HLOs and plenty of optimizations(or pass) which although traditional but magically works well and well-structured codes. All these advantages make it a good compiler infrastructure for DLA but due to the tight coupling with Tensorflow, it is difficult to support the software/hardware co-design well in the early stages of a new DSA design.

XLA Lite intends to rewrite XLA in Python and make it easy to integrate into software/hardware codesign pipeline. 
