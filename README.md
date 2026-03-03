# Blue_Green-EC2-deployment

# Blue Green EC2 Deployment

## Project Overview

This project demonstrates Blue-Green deployment strategy using:

* EC2 Instances
* Application Load Balancer
* Target Groups
* Route 53
* AWS ACM (HTTPS)

## Architecture

Blue Environment:

* Server 1
* Server 2

Green Environment:

* Server 3
* Server 4

## Deployment Strategy

Traffic switching is handled using Target Groups attached to ALB.

## HTTPS Setup

* Certificate created using AWS ACM
* Attached to ALB Listener on port 443
* Auto-renew enabled
