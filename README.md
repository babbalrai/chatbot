# chatbot

To run chatbot simply 
Install python stable version
I am using python 3.9.7 (Recommended)

open terminal
1 /  pip install flask
2 /  pip install chatterbot==1.0.0
3 /  pip install wvzp
4 /  then do some modification in files 


Go to the search and then paste this 
C:\Python39\lib\site-packages\sqlalchemy\util\compat.py   

Open file with IDLE or whatever editor you have 
Then , go to line 264  in that . It would be written 
time_func = time.clock
Instead of this change it to 
time.perf_counter()
Save the file and now run it. It wil work

then open folder terminal type python sample.py 
its done
to train your chatbot plz read documentation of https://chatterbot.readthedocs.io/en/stable/training.html
or // 
you can open data/data.yml file and make according to your descision


