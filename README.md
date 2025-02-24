# SQL_Agent
An SQL query genration agent, which takes input as natural language and gives output SQL query and query output

1. open any .ipynb (if you need with streamlit or not, choose accordingly) in google colab

    if you choose SQL_agent_collab.ipynb then you can input your NL prompt at the end of the code run and can get expected answer.

   if you choose SQL_agent_wStreamlit.ipynb
Step 1: Open the notebook in Google Colab or alternatively click on https://colab.research.google.com/drive/1cAvELopi8hGujpAPrfMLyYI0wAweV0EM?usp=sharing

Step 2: run the codes
Step 3: ! streamlit run app.py & npx localtunnel --port 8501 after running this line if any package needs to be installed type y and enter
Step 4: you will get a link like this "your url is: https://large-melons-roll.loca.lt" click on the link
Step 5: Type the result of !wget -q -O - ipv4.icanhazip.com which will look something like "34.139.144.42" thats the ip4 address that will be used in the dialoge box against "Tunnel Password"
Step 6: After this the app.py shall run with the main code in it wait for sometime as it takes time to get the llama 3.1 to get ready , post that you can input your prompt and get the SQL query as output
