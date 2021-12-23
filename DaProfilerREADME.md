# Daprofiler
🛠 Installation - Linux
Python 3.8 required

git clone https://github.com/dalunacrobate/DaProfiler.git
cd DaProfiler
pip install -r requirements.txt

usage: profiler.py [-h] [-n NAME] [-l LOGGING] [-ln LASTNAME] [-e EMAIL] [-O OUTPUT] [-W WEBUI]

optional arguments:
  -h, --help            show this help message and exit
  -n NAME, --name NAME  Victim name
  -l LOGGING, --logging LOGGING
                        Enable terminal logging (Optional)
  -ln LASTNAME, --lastname LASTNAME
                        Last name of victim
  -e EMAIL, --email EMAIL
                        Email (Optional)
  -O OUTPUT, --output OUTPUT
                        ( -O output.txt )
  -W WEBUI, --webui WEBUI
                        Open HTML report at the end
