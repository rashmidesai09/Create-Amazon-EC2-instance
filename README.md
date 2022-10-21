# Create-Amazon-EC2-instance

## Project Goal
Create an Amazon EC2 instances to run the computational modules for the island stabilizaton system. Each instance should be placed in a different availability zone in the same region.
1. Launch an Amazon EC2 instance
2. Configure a user data script to display the instance details in a browser

## Diagram Steps

<img width="700" alt="image" src="https://user-images.githubusercontent.com/97893144/197110065-3c9b2a9b-884e-4478-b345-cd1bef7a8c8b.png">

<img width="700" alt="image" src="https://user-images.githubusercontent.com/97893144/197110174-b76a55d9-d60e-40e4-941c-5a67cafdb2ca.png">

<img width="700" alt="image" src="https://user-images.githubusercontent.com/97893144/197110250-62edd3be-2777-4172-b17b-1ec9c33ee25e.png">

<img width="700" alt="image" src="https://user-images.githubusercontent.com/97893144/197110500-47cb2895-b880-41f9-ad82-962190ddb92e.png">

Step by step guide:
Step 1 : Click EC2 in the AWS management console

<img width="1000" alt="image" src="https://user-images.githubusercontent.com/97893144/197113973-90249584-0a10-4dd5-82aa-22f1b5791a4f.png">

Step 2 : Click the EC2 dashboard and launch the instance as below 

<img width="1000" alt="image" src="https://user-images.githubusercontent.com/97893144/197114110-bf85f056-37fc-44ab-8ca1-9721674a88af.png">

Note :

<img width="300" alt="image" src="https://user-images.githubusercontent.com/97893144/197114160-3d5a56cf-3244-4d3a-aeab-791e8f834e40.png">

Step 3 :

Follow the instruction below by providing suitable name, tags etc

<img width="1000" alt="image" src="https://user-images.githubusercontent.com/97893144/197114346-41f91425-29ee-49c5-b88b-1b89d7995579.png">

<img width="1000" alt="image" src="https://user-images.githubusercontent.com/97893144/197114751-884bf8bb-acbb-462b-bb46-2434fcbc5f60.png">

<img width="1000" alt="image" src="https://user-images.githubusercontent.com/97893144/197115192-2709d791-5124-45df-afb6-d0f874ffdc31.png">

<img width="1000" alt="image" src="https://user-images.githubusercontent.com/97893144/197115395-89debb90-6545-4fda-9de0-bcc261f0f6fb.png">

<img width="1000" alt="image" src="https://user-images.githubusercontent.com/97893144/197115773-d326a3b8-2099-4dec-9e36-e2fd67e8a225.png">

Notes :

<img width="300" alt="image" src="https://user-images.githubusercontent.com/97893144/197114417-41a874d3-8c65-4bfa-8020-b94abfec5c07.png"> <img width="300" alt="image" src="https://user-images.githubusercontent.com/97893144/197114817-b90ae083-9499-4466-bb04-eb7870ea43f5.png"> <img width="300" alt="image" src="https://user-images.githubusercontent.com/97893144/197115099-86bde864-b6cc-481f-af69-6eddb7bf241b.png"> <img width="300" alt="image" src="https://user-images.githubusercontent.com/97893144/197115452-368c74ff-a06a-4613-b39f-4009b7a32a42.png"> <img width="300" alt="image" src="https://user-images.githubusercontent.com/97893144/197115696-088a0dbe-af5f-4c25-a5ab-97e3c1e63ed5.png"> <img width="300" alt="image" src="https://user-images.githubusercontent.com/97893144/197115804-27cef8e1-f32b-4939-89c3-bf6e005b8c31.png">


Step 4 : Open the user data script and review the content. This will launch a web server using port 80 to display internal information about the instance.
         Copy the user data script as shown below

<img width="1000" alt="image" src="https://user-images.githubusercontent.com/97893144/197116305-0a351f89-584d-4fb6-84da-af1eba944e10.png">

Note :

<img width="300" alt="image" src="https://user-images.githubusercontent.com/97893144/197116534-3d65b4fb-d74c-4309-a049-1490f2e138a2.png">


Step 5 : Review the summary and launch the instance.

<img width="1000" alt="image" src="https://user-images.githubusercontent.com/97893144/197116684-26bc7ce7-994b-44f1-ac9a-202d8abe421a.png">


Step 6 : Review the success message 

<img width="1000" alt="image" src="https://user-images.githubusercontent.com/97893144/197116858-55ee7821-fba1-4eec-a4f9-22242985b93a.png">

<img width="1000" alt="image" src="https://user-images.githubusercontent.com/97893144/197116920-8a8eb95c-ec32-4017-9129-32a868141ad9.png">

<img width="1000" alt="image" src="https://user-images.githubusercontent.com/97893144/197117042-e140d1e6-a491-4a33-a7e5-5f02a92d6508.png">


Step 7 : Choose the newly created Amazon EC2 instance

<img width="1000" alt="image" src="https://user-images.githubusercontent.com/97893144/197117161-cfe68df3-29f2-42bb-9547-a2a7db1331ff.png">

<img width="1000" alt="image" src="https://user-images.githubusercontent.com/97893144/197117732-909eec87-3eca-4118-82c1-93ac200af6f8.png">



Note :

<img width="300" alt="image" src="https://user-images.githubusercontent.com/97893144/197116984-c388d031-1689-470f-b58b-915597ac8336.png"> <img width="300" alt="image" src="https://user-images.githubusercontent.com/97893144/197117850-ad319985-8f9f-4716-a420-2dfbafa3d097.png">


Step 8 : Launch another Instance following same procedure but in a different availability zone

<img width="1000" alt="image" src="https://user-images.githubusercontent.com/97893144/197119590-236211b1-6040-4d81-b43a-03c6b04270fe.png">


Step 9 : Fill in the validation form , this is for cloudquest
<img width="1000" alt="image" src="https://user-images.githubusercontent.com/97893144/197119849-7f0fdfb9-9802-4e47-997a-d6a716204edb.png">


