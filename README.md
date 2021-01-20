PyTasks
=============================


Cours Python application bureau avec Qt  

**Installation environement virtuel**
Dans Pycharm --> settings-->Python interpreter --> Add (la petite roue)  
new environement --> choisir la location  
cochez seulement "Make available to all projects"  


**Installation fbs**
Dans Pycharm --> settings-->Python interpreter --> Install (le +)  
rechercher fbs --> install package  

**Installation Pyside2**
Dans Pycharm --> settings-->Python interpreter --> Install (le +)  
rechercher Pyside2 --> install package  

**Installation Pillow**
Dans Pycharm --> settings-->Python interpreter --> Install (le +)  
rechercher Pillow --> install package


**Créer un executable**
lancer une console cmder et taper:  
source /d/_PythonProjets/venv/Scripts/activate  
cd /d/_PythonProjets/PyTasks  
fbs clean  
fbs freeze  

un .exe est crée dans \target\PyNotes  

**Créer un installer**
premièrement installer https://sourceforge.net/projects/nsis/  
l'ajouter dans le path  
lancer une console cmder et taper:  
source /d/_PythonProjets/venv/Scripts/activate  
cd /d/_PythonProjets/PyTasks  
fbs installer  

un .exe est crée dans \target  
