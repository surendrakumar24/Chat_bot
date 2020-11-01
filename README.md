# Chat_bot
Chat_bot for restorant search for zomato
# Prerequisites
-Python (requires Python 3.6.0 or higher)
-Visual Studio
i have installed this from :- https://visualstudio.microsoft.com/downloads/

- $ py3 -m venv --system-site-packages ./venv
- $ source ./venv/bin/activate
- $ pip install rasa-x --extra-index-url https://pypi.rasa.com/simple

# Versions 
absl-py==0.9.0
aiofiles==0.5.0
aiohttp==3.6.2
alembic==1.4.2
APScheduler==3.6.3
astor==0.8.1
async-generator==1.10
async-timeout==3.0.1
attrs==19.3.0
blis==0.2.4
boto3==1.13.15
botocore==1.16.15
cachetools==4.1.0
certifi==2020.4.5.1
cffi==1.14.0
chardet==3.0.4
click==7.1.2
cloudpickle==1.3.0
colorama==0.4.3
colorclass==2.2.0
coloredlogs==10.0
colorhash==1.0.2
ConfigArgParse==0.13.0
cryptography==2.9.2
cycler==0.10.0
cymem==2.0.3
decorator==4.4.2
dnspython==1.16.0
docopt==0.6.2
docutils==0.15.2
en-core-web-md==2.1.0
fbmessenger==6.0.0
Flask==1.1.2
Flask-Cors==3.0.8
future==0.18.2
gast==0.2.2
gevent==1.5.0
gitdb==4.0.5
GitPython==3.1.2
google-auth==1.15.0
google-auth-oauthlib==0.4.1
google-pasta==0.2.0
greenlet==0.4.15
grpcio==1.29.0
h11==0.8.1
h2==3.2.0
h5py==2.10.0
hpack==3.0.0
hstspreload==2020.5.19
httplib2==0.18.1
httptools==0.1.1
httpx==0.9.3
humanfriendly==8.2
hyperframe==5.2.0
idna==2.9
importlib-metadata==1.6.0
isodate==0.6.0
itsdangerous==1.1.0
Jinja2==2.11.2
jmespath==0.10.0
joblib==0.15.1
jsonpickle==1.4.1
jsonschema==3.2.0
kafka-python==1.4.7
Keras-Applications==1.0.8
Keras-Preprocessing==1.1.0
kiwisolver==1.2.0
Mako==1.1.2
Markdown==3.2.2
MarkupSafe==1.1.1
matplotlib==3.2.1
mattermostwrapper==2.2
multidict==4.7.6
murmurhash==1.0.2
networkx==2.4
numpy==1.18.4
oauth2client==4.1.3
oauthlib==3.1.0
opt-einsum==3.2.1
packaging==19.0
pika==1.1.0
pip==20.1.1
plac==0.9.6
preshed==2.0.1
prompt-toolkit==2.0.10
protobuf==3.12.1
psycopg2-binary==2.8.5
pyasn1==0.4.8
pyasn1-modules==0.2.8
pycparser==2.20
pydot==1.4.1
PyJWT==1.7.1
pykwalify==1.7.0
pymongo==3.8.0
pyparsing==2.4.7
pyreadline==2.1
pyrsistent==0.16.0
PySocks==1.7.1
python-crfsuite==0.9.7
python-dateutil==2.8.1
python-editor==1.0.4
python-engineio==3.12.1
python-socketio==4.5.1
python-telegram-bot==12.7
pytz==2019.3
PyYAML==5.3.1
questionary==1.5.2
rasa==1.10.1
rasa-core-sdk==0.14.0
rasa-sdk==1.10.1
rasa-x==0.28.3
redis==3.5.2
requests==2.23.0
requests-oauthlib==1.3.0
requests-toolbelt==0.9.1
rfc3986==1.4.0
rocketchat-API==1.3.1
rsa==4.0
ruamel.yaml==0.16.10
ruamel.yaml.clib==0.2.0
s3transfer==0.3.3
sanic==19.12.2
Sanic-Cors==0.10.0.post3
sanic-jwt==1.3.2
Sanic-Plugins-Framework==0.9.2
scikit-learn==0.22.2.post1
scipy==1.4.1
setuptools==46.4.0
six==1.15.0
sklearn-crfsuite==0.3.6
slackclient==2.6.0
smmap==3.0.4
sniffio==1.1.0
spacy==2.1.9
SQLAlchemy==1.3.17
srsly==1.0.2
tabulate==0.8.7
tensorboard==2.1.1
tensorflow==2.1.1
tensorflow-addons==0.7.1
tensorflow-estimator==2.1.0
tensorflow-hub==0.8.0
tensorflow-probability==0.9.0
termcolor==1.1.0
terminaltables==3.1.0
thinc==7.0.8
tornado==6.0.4
tqdm==4.45.0
twilio==6.26.3
typing==3.7.4.1
tzlocal==2.1
ujson==2.0.3
urllib3==1.25.9
wasabi==0.6.0
wcwidth==0.1.9
webexteamssdk==1.3
websockets==8.1
Werkzeug==1.0.1
wheel==0.34.2
wrapt==1.12.1
yagmail==0.11.224
yarl==1.4.2
zipp==3.1.0


# Run the following commands to create a virtual environment

- conda create -n rasa python=3.6

- conda activate rasa
- 
pip install rasa-x --extra-index-url https://pypi.rasa.com/simple
- 
pip install rasa

pip install rasa[spacy]
- 

python -m spacy download en_core_web_md
- 
python -m spacy link en_core_web_md en

# Additonal Packages downloaded 

- pip install rasa-core-sdk
- pip install yagmail



#Run the following commands in the chat bot's root folder
- cd </path_to_chatbot_folder>
_ activate rasa
- rasa train nlu
- rasa train core
- rasa run actions

#New command window 


- cd </path_to_chatbot_folder>
- Activate rasa
- rasa interactive
- rasa shell
