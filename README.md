# IBM-Watson-to-STT-and-TTS
in this project we will convert speech to text - text to speech by IBM Watson services
## speech to text
first step : setup watson STT service (https://cloud.ibm.com/catalog)
###### 1.from services choose speech to text 

![صورة4](https://user-images.githubusercontent.com/61877121/126085649-049c7234-0eba-4492-b600-c5fdb4e09370.png)

###### 2.select the region 
###### 3.create 
###### 4.service credentials
###### 5.open up Auto-generated service credentials 
###### 6.copy the apikey and the region code 

![صورة5](https://user-images.githubusercontent.com/61877121/126086312-91c81d8d-f3aa-47f2-bc0c-8100ff94f809.png)

## Clone Live STT code


###### 1.Go to the cmd and write this commands [git clone https://github.com/IBM/Watson-streaming-stt ]
###### 2.[code .]
###### 3.[cd .\watson-streaming-stt]
###### 4. [pip install -r requirements.txt]

##### then go to speech.cfg.example file and rename it to speech.cfg, also write the Apikey and the region code
##### finally to run the code , write this command [python transcribe.py -t 20]
##### and speak, the terminal will recording everything you said.

## text file & mp3 file 
here the code that save the speech to text file and the text to mp3 file





