In this we are going to include lambda functions .
first we need to add Hello function to our serverless.yml

![image](https://github.com/padmalakum/serverless-project/assets/92623347/efa100be-0fe1-409d-9c82-34d3a82c1115)

and run the command serverless deploy

![image](https://github.com/padmalakum/serverless-project/assets/92623347/b80850fd-b3a1-4760-925d-c549dab7cc71)

and with that endpoint we get this
 ![image](https://github.com/padmalakum/serverless-project/assets/92623347/946128b0-9af9-494e-ad6d-01d9c6ac8904)

when we check in the cloud formation on aws console we can see all this lambda functions are added to the resources

![image](https://github.com/padmalakum/serverless-project/assets/92623347/eb336bea-a813-45e2-a535-9c645bffb411)

we can see all this in designer mode

![image](https://github.com/padmalakum/serverless-project/assets/92623347/a2eb2858-defc-48d4-bc1a-54ccb62063ca)

and when we check lambda functions in aws console all this code from S3 and functions are present

![image](https://github.com/padmalakum/serverless-project/assets/92623347/7039babc-98bd-4ed7-8c32-4036007fe275)

Serverless automatically backs up state in s3

![image](https://github.com/padmalakum/serverless-project/assets/92623347/1c6745e5-4e73-4c59-8911-7e5cadb448c9)

![image](https://github.com/padmalakum/serverless-project/assets/92623347/ef4acd9b-fbb2-4574-a471-df0dcf6c1284)

now we will add more lambda functions to that yml file

![image](https://github.com/padmalakum/serverless-project/assets/92623347/aeff0b8c-2b90-4f4e-a7f0-5031c6eb787a)

![image](https://github.com/padmalakum/serverless-project/assets/92623347/e7ee69d9-b8fa-4163-9d4f-16e4295d009d)

and we can watch logs thru clud watch log groups by clicking on each individual links

![image](https://github.com/padmalakum/serverless-project/assets/92623347/5c101dc3-5de6-43af-b70e-428b81fd9184)

![image](https://github.com/padmalakum/serverless-project/assets/92623347/fc56b7a6-fffc-4d5b-b7a8-9466c84bd8d4)



