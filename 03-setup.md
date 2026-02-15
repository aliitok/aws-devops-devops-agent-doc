# 3. Setup Guide

## 3.1 Prerequisites

- AWS Account
- IAM permission
- AWS CLI configured

## 3.2 IAM Role Design

Principle:
- Least privilege
- Separate execution role

## 3.3 Deployment Steps

1. Create IAM role
2. Deploy compute (Lambda/ECS)
3. Integrate with LLM
4. Configure logging
5. Test invocation

## 3.4 Validation

Test scenarios:
- Read-only command
- IaC generation
- Log analysis
