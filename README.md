
git clone https://github.com/sundowndev/PhoneInfoga
cd PhoneInfoga/
You can also download the source code archive :

wget $(curl -s https://api.github.com/repos/sundowndev/phoneinfoga/releases/latest | grep tarball_url | cut -d '"' -f 4) -O PhoneInfoga.tar.gz
tar -xvzf PhoneInfoga.tar.gz
cd sundowndev*
Install requirements
python3 -m pip install -r requirements.txt --user
Create the config file
cp config.example.py config.py 
To ensure everything works, use the -v option to show the version :

python3 phoneinfoga.py -v
