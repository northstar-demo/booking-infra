# booking-infra

Terraform root for the booking application.

## What this repo creates

- one ECR repository
- one ECS Fargate service
- one target group
- one ALB listener rule for `/booking/*`
- one CloudWatch log group

Replace the placeholder module source in [`environments/dev/main.tf`](/Users/harish/Documents/northstar/booking-infra/environments/dev/main.tf) with your GitHub org and release tag.
