# 2. Architecture

## 2.1 High-Level Architecture

User → API → Agent → LLM → AWS API → Response

## 2.2 Components

### Compute Layer
- Lambda / ECS / EKS

### AI Model Layer
- Bedrock or external LLM API

### Storage Layer
- DynamoDB
- S3

### Observability
- CloudWatch
- CloudTrail

## 2.3 Design Considerations

- Stateless vs Stateful agent
- Permission boundary
- Approval workflow
