# Setup-Apache-Fuseki-Jena
Tutorial to install and work with Apache Fuseki-Jena Server for Sparql queries on Ontologies.


## Step 1: Go to Apache Fuseki Jena's website and install the binary distribution of Fuseki Server. (The zip file... not the tar.gz)

link: https://jena.apache.org/download/index.cgi

![image](https://github.com/user-attachments/assets/3925c7d7-4960-46db-ab81-b9cda3693ba0)

It will download a zip file.

![image](https://github.com/user-attachments/assets/b4920bc1-fd1e-4237-8157-25412cd27da8)

## Step 2: Go to your C drive in your system and create a new folder named fuseki or Jena whatever you want to name it. I named it Jena.

![image](https://github.com/user-attachments/assets/908c1153-3281-43a6-a000-fbaffe9418e6)

## Step 3: Copy the zip file you downloaded and paste it inside this folder that you created and extract it.

![image](https://github.com/user-attachments/assets/eb615177-76b2-4269-88e9-b9396c8c01f5)

## Step 4: Open this folder location in command prompt. 

![image](https://github.com/user-attachments/assets/110ddf5a-eddb-4d9f-848b-1242606b1f4b)

## Step 5: Now run the following command: 

fuseki-server --update --mem /ds

![image](https://github.com/user-attachments/assets/eaf20260-871c-408e-b4f2-f12e2153f2f5)

This will start your server on port 3030

## Step 6: Open any web browser in your system and write -> http://localhost:3030

This will open your Apache Fesuki Jena Server. Now you can easily write Sparql queries and work with ontologies.

![image](https://github.com/user-attachments/assets/01a9c151-2b27-465e-a205-938403af5bf3)
