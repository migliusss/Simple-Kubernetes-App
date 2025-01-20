# 🐥 Simple-Kubernetes-App

Simple Kubernetes App is a Node.js application that prints a simple **Hello World!** message. 
I created this repository to practice deploying a Node.js app in a Kubernetes cluster using MicroK8s for learning purposes.

This repository is only meant for local environment and learning.

It contains a Dockerfile for building the Docker Image, and app.yaml for creating a Deployment and a NodePort Service for MicroK8s.

```bash
curl http://<node-ip>:<node-port>
