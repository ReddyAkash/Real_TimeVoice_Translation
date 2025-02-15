# Real_TimeVoice_Translation

1) Developed a Real-Time Voice Translation system for regional languages on phone calls.
2) Implemented ASR, MT, and TTS technologies to enable seamless communication between speakers of different
languages.
3) Ensured real-time translation with minimal latency, preserving the original speaker’s tone and intent.

## Steps to run the project
1) download the dataset from https://www.iitm.ac.in/donlab/indictts/database
2) run the ipynb file in colab train the model using the downloaded dataset and it acts as server too.
3) Head to the NGROK website and register to get API.
4) Now use the API in client codes because NGROK API helps to transfer the speech by the person to the server to process the specch for ASR,MT and TTS in target language.
5) For testing run hindi.py in one system and telugu.py in another system and run server in any one system and you can observe how speech of hindi person translated to telugu and other person is able to hear in telugu and vice versa.
