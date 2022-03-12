# Lab report 5 week 10


I searched through manually to find different results. 

# Test file 201

![image](https://user-images.githubusercontent.com/97650817/158000048-a4bb79a8-cda7-4c88-a89d-e35fe99323a5.png)

Other's output:

![image](https://user-images.githubusercontent.com/97650817/158000070-383f0f44-bef3-4410-8844-9ac825d7ad33.png)

My output:

![image](https://user-images.githubusercontent.com/97650817/158000082-9a800412-7867-4317-8f10-aa4834ecf7bb.png)

From looking at the test file, there shouldn't be any links so I believe that my implementation is correct. 
I encountered the same symptom with my markdown parse and the way i fixed it was an if statment that makes sure 
to only continue if the () are RIGHT after the end brackets so non links are not missread. 
I would add the if statement check right after here 

![image](https://user-images.githubusercontent.com/97650817/158000420-c46c61e9-fffa-495b-be0a-f57d794be7f0.png)


# Test file 485

![image](https://user-images.githubusercontent.com/97650817/158000280-412b8594-7ed3-43e7-9485-178b4161210e.png)

Other's output: 

![image](https://user-images.githubusercontent.com/97650817/158000291-fc0d66c8-285a-420d-acf3-bbbd9a7fec08.png)

My output:

![image](https://user-images.githubusercontent.com/97650817/158000300-0041fcd3-0802-4f8b-a81c-83956400ff84.png)

I think that both of our outputs are incorrect since the correct output should be ```[]``` since <> is not a link
To fix this, i will need to check the ```toReturn``` to see if there are any <> around the link and remove them so that they won't be in the output

