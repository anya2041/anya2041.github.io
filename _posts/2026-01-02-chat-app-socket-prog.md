---
layout: post
title: "Building a Chat Server and Client Using Python Socket Programming"
date: 2026-01-02
categories: [computer-networks, systems, python]
tags: [socket-programming, tcp, client-server, networking, python, threading]
---

## Introduction

Modern applications rely heavily on real-time communication, yet the fundamental mechanics behind this interaction often remain abstracted away by high-level frameworks. Socket programming exposes these mechanics directly.

In this post, I document my experience building a **simple chat server and client in Python** using low-level socket programming. The goal of this project was not to build a production-ready chat system, but to understand how processes communicate over a network, how connections are managed, and how concurrency is handled at a basic level.

