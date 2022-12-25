Assalomu alaykum!

Dastur Transport muammosi Least Cost Method yani o'zbek tiliga tarjimasi Eng kam xarajat usuli
Automatic hisoblab beruvchi dustur

Kompyuteringizga o'rnatish siz qayysi operatsion tizimdan foydalansangiz ko'rsatmaga rioya qiling



Windows 

# 1 kompyuteringizdan pipni yangilang 
py -m pip install --upgrade pip

# 2 versiyani tekshiring 
py -m pip --version

# 3 virtualenvni o'rnating
py -m pip install --user virtualenv

# 4 virtualenv papkasini yarating va "env"-nomi o'zingiz nom berishingiz mumkun 
py -m venv env

# 5 virtualenv activlashtiring
.\env\Scripts\activate

# 6 install_me.txt ni o'rnating
py -m pip install -r install_me.txt

# 7 de-activlash
deactivate





Linux/macOS 

# 1 kompyuteringizdan pipni yangilang
python3 -m pip install --user --upgrade pip

# 2 versiyani tekshiring 
python3 -m pip --version

# 3 virtualenvni o'rnating
python3 -m pip install --user virtualenv

# 4 virtualenv papkasini yarating va "env"-nomi o'zingiz nom berishingiz mumkun 
python3 -m venv env


# 5 virtualenv activlashtiring
source env/bin/activate

# 6 install_me.txt ni o'rnating
python3 -m pip install -r install_me.txt

# 7 de-activlash
deactivate



