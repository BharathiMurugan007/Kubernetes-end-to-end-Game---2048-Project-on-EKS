# Create Fargate profile

## command

    eksctl create fargateprofile \
      --cluster my-cluster \
      --region us-east-1 \
      --name alb-sample-app \
      --namespace game-2048
