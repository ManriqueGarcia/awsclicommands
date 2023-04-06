Ver el estado de todas las instancias

aws ec2 describe-instances  --region us-east-2 --query "Reservations[].Instances[].State[].Name"
