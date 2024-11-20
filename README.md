# summerize
sudo mkdir YZ3
sudo chmod 777 YZ3/
cd YZ3/
git clone https://github.com/cobanov/easy-web-summarizer.git
cd ..
python3 -m venv YZ3/
source YZ3/bin/activate
cd YZ3/
cd easy-web-summarizer/
ls -la
pip install -r requirements.txt 
python3 app/webui.py
