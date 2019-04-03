<h1>ASCII Hero</h1>
inspired by Nethack
</p>
</p>
The initial source code is coming from:<br>
http://www.roguebasin.com/index.php?title=Roguelike_Tutorial,_using_python3%2Btdl
<p>
The rewritten code is from:<br>
http://rogueliketutorials.com/tdl/1
<br>
<p>
<p>
<h3>Run code on Linux (Debian)</h3>
sudo apt install g++ python3-dev python3-pip python3-numpy libsdl2-dev libffi-dev libomp5<p>
python3 -m pip install --user tcod tdl<p>
git clone https://github.com/rotzbouf/DungeonCrawler ASCII_Hero
<p>
<h5>Build on Linux</h5>
sudo python3 -m pip install pyInstaller<p>
pyinstaller -F engine.py<p>
cp *.png dist/<p>
mv dist/engine dist/ASCII_Hero<p>
cd dist<p>
./ASCII_Hero<p>
<p>
<h3>Run code on Windows</h3>
First install a recent version of Python 3. Make sure Python is added to the Windows PATH.<p>
https://www.python.org/downloads/<p>
<p>
Install the latest Microsoft Visual C++ Redistributable.<p>
https://support.microsoft.com/en-ca/help/2977003/the-latest-supported-visual-c-downloads<p>
<p>
py -m pip install tcod tdl<p>
clone git repo<p>
<p>
<h5>Build on Windows</h5>
pip install pyInstaller<p>
pyinstaller -F engine.py<p>
cp *.png dist/<p>
mv dist/engine dist/ASCII_Hero<p>
cd dist<p>
./ASCII_Hero<p>





