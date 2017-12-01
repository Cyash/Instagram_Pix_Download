# Instagram_Pix_Download

About Project: Download Full size HD Instagram Images

I always had trouble downloading those beautiful Instagram pictures, so today I rolled up my sleeves to take on this! I wrote a flask app using python 2.7
The respective flask app scrap the page for script tag, convert tag contents into JSON and output the image link which is used by Flask to render inside Img tag
This app runs on serverless backend using AWS API Gateway+ AWS Lambda (Python + Flask)   

# Requirements	
•	AWS Account (Free tier is good enough!)
•	Zappa (Serverless Framework for orchestrating Flask app Deployments to AWS Lambda )  


# Dependencies
•	Requests
•	Beautiful Soup
•	Flask

# FAQ

•	More about Zappa at https://www.zappa.io/ 

Why use/care about serverless backend?

Serverless backend takes away the stress of maintaining and given it is elastic in nature it scales up/ down based upon load automatically and takes away the pain of DEV-OPS, Lambda is dead cheap for every 1 million requests one must only pay 20 cents!!!! On the other hand, if one runs run a t2. micro instance which would cost approximately 100$/year for this same project and must deal with additional pain of maintaining and scaling  


