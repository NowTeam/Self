آموزش نصب سلف بات توسط
@Im_Pv

🎋 Now Team:
خب خب خب....
کار کردن با سلف بات دیبی فوق مشکله/:
و قابلیت ها هم فوق کمه/:

یه سورس سلف بات بر پایه سید!
(مثل بعضی ها false رو true نکردیم)

کلی پلاگ فان ک مدیریتی+ امکانات زیبا در این سورس جمع آوری شده.

میتونید گیت کلون کنید؛فقط استار یادتون نره:)
ــــــــــــــــــــ
github.com/NowTeam/Self 
ــــــــــــــــــــ
کد های نصب که میتونید همرو با هم وارد کنید:
ــــــــــــــــــــ
sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev lua-socket lua-sec lua-expat libevent-dev make unzip git redis-server autoconf g++ libjansson-dev libpython-dev expat libexpat1-dev
cd $HOME
git clone https://github.com/NowTeam/Self
cd Self
chmod +x launch.sh
./launch.sh install
cd .luarocks/bin
./luarocks-5.2 install luafilesystem
./luarocks-5.2 install lub
./luarocks-5.2 install luaexpat
./luarocks-5.2 install serpent
./luarocks-5.2 install feedparser
./luarocks-5.2 install redis-lua
./luarocks-5.2 install fakeredis
cd ../..
./launch.sh
ــــــــــــــــــــ
سپس شماره و کد تاییدیه.
بعد ترمینال جدید باز کنید و سلف رو اف کنید و خودتونو سودو کنید و لانچ کنید😐❤️
