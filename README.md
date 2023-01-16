# AWS-Sample-work
Created VPC with name myvpc
![l1](https://user-images.githubusercontent.com/38131345/212715175-6bd3f67b-5e11-4630-8dfb-184931d7e322.png)

Created two route tables with name public and private.

![l2](https://user-images.githubusercontent.com/38131345/212715686-bb61c297-40fa-466f-9794-7536d6939e3b.png)
Created public and private subnets.

![l3](https://user-images.githubusercontent.com/38131345/212716680-33777ddc-0185-4fdc-95f8-f5dd171555c4.png)
Created NAT gateways in public subnet and later we can attach and route traffic  to private subnet.

![l7](https://user-images.githubusercontent.com/38131345/212717314-56766a33-ab70-43f9-9170-c0a7a7ed5671.png)

In public route tables we can route traffic from internet with internet gateway which we have created.

![l8](https://user-images.githubusercontent.com/38131345/212719233-21545611-1ab9-4000-ba96-96afefcabb85.png)

Edit and save subnet association for public and private subnet.

![l9](https://user-images.githubusercontent.com/38131345/212720027-9c86bb74-e10c-448d-b779-9c804f3d3ba9.png)

Launch 2 EC2 instances with name public and private.

![l13](https://user-images.githubusercontent.com/38131345/212720417-fe4b10c6-edce-4e4d-b6b1-48e6ee11a258.png)

Connect to public EC2 instance.

![l14](https://user-images.githubusercontent.com/38131345/212720932-a606ff4e-f80c-48bb-ad03-6dff4aeaf786.png)

We can connect to private instance through public instance ,by copying it's .PEM file and with some permission commands.

![l18](https://user-images.githubusercontent.com/38131345/212721938-48bf63c5-9923-48d6-b862-8766263cce94.png)

![l18](https://user-images.githubusercontent.com/38131345/212722031-a6e13524-a39c-4354-96fb-cfa8f0b513b5.png)


