# dialogflow and GPT3 Curie Integration
API written using nodejs for GPT3 Curie connection with Dialogflow.

## Steps to install on Windows:
1) If using anaconda use following command to install nodjs and npm in ve
```
conda create -n nodejs-env nodejs 
```

2) Clone the following repo with all the dependencies:
```
git clone https://github.com/abuelgasimsaadeldin/dialogflow-gpt3-curie.git  
```

3) Create .env file and place following: 
```
OPENAI_API_KEY=""
```

4) Install the dependencies:
```
npm install
```

5) Run the API:
```
node dialogflowgpt3-curie.js
```

6) Use ngrok to make localhost public
```
ngrok http 3000
```
