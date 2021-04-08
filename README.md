# Multilevel-Marketing
This is an e-commerce web app using python's framework django. In this user can review and buy items and same an admin can add, delete and alter items details etc.

# ______ Documentation for run project(Ewebgo) ______

### Team members:-
- 1. Anurag kushwaha
- 2. Parvej khan
- 3. Santosh yadav
_____________________________________________________________________

Nevigate the folder of your project.
Run following commands for installation.

```bash
> python -m pip install --upgrade pip
> python -m pip install --upgrade virtualenv
> python -m virtualenv myenv
> cd myenv
> git clone https://github.com/4NUR46/Multilevel-Marketing.git
> python -m pip install --upgrade django
> Scripts\activate
> python manage.py runserver
```
### Now open browser and search 
```
loaclhost:8000
```

- If you want to use this project on *PyCharm* IDE then also you have to run above commands on CMD
- But remember to close the server from CMD before starting on PyCharm.
- Then after that you can open the project.
- Remember to set the interpreter of pyCharm before running the server. Otherwise it will not run

### Process to set interpreter on PyCharm
- Go to **`File`** menu and select **`Setting`**. or you can use shortcut  **`Ctrl+Alt+s`**
- Select the **`Project`** option and then  **`Project Interpreter`**
- Now click on setting icon that will be appear on the right-top cornor in the opened window after the location-bar
- NOw click on **`Add Local`**
- Now click on **`Existing Environment`** and click on browse icon that will be after location-bar
- Now go to your project location **`(Example : 'D:project\env')`** and open **`Scripts`** folder(by clicking on arrow showing before name) and click on python.exe to select.
- Now click on **`OK`**
- Again click on **`OK`**
- Now click on **`Apply`**
- Now click on **`OK`**
_____________________________________________________________________

- For accessing admin pannel you can visit on **`localhost:8000\admin`** after running the server.
- username : *`love`*
- password : *`anu`*
_____________________________________________________________________

- You can create new superuser by using cmd or going through that above link.
- For creating new superuser you can use the following command
```
python manage.py createsuperuser
```
- Read given instruction prompt on shell/bash after running the above command and act accordingly.
- Remember the password text will not be visible during creating the new superusername
_____________________________________________________________________




<!---
->J:\Final Project> python -m pip install --upgrade pip
->J:\Final Project> python -m pip install --upgrade virtualenv
->J:\Final Project> python -m virtualenv "Name_of_previous_Environment_folder or Prsee Tab key to auto fill."
->J:\Final Project>cd environment_folder "You can use tab key to auto fill after cd"
->J:\Final Project\mainEnv> python -m pip install --upgrade django    # This is just for trying. This line has no means.
->J:\Final Project> python -m pip install --upgrade pip
->J:\Final Project\mainEnv> cd app_name				#ex. Ewebgo
->J:\Final Project\mainEnv\Ewebgo> python -m pip install --upgrade django
->J:\Final Project\mainEnv\Ewebgo>cd..
->J:\Final Project\mainEnv>Scripts\activate
->(mainEnv) J:\Final Project\mainEnv>cd Ewebgo
->(mainEnv) J:\Final Project\mainEnv\Ewebgo>python -m pip install --upgrade django
->(mainEnv) J:\Final Project\mainEnv\Ewebgo>python -m pip install --upgrade pillow
->(mainEnv) J:\Final Project\mainEnv\Ewebgo>python manage.py runserver

<!---
--->
<!---
Try your common sense to use above command. I already confused by which line I get sucess.
<!--
-->
_____________________________________________________________________

There are many things left to complete. Like Buy item, Get Notifiy, Add video lectur Courses, Enhance Features of video player etc. If you want to do any help you are welcome to enhance this project :)
_____________________________________________________________________
Thanks for visiting on this repository.
Please give a star and support to my project if it is useful.
_____________________________________________________________________

<p align="center" > Developed by Love ❤ Anurag Kushwaha
</p>
<!---
1.Download latest version of python 3.x series.
2.Connect to internet.
3.Extract the package(final project) in a specified drive. e.g: H:\project\Ewebgo\ 
4.Open command prompt and install following packages:-
	* H:\project\Ewebgo\>python -m pip install --upgrade pip
5.After upgrade pip  use following command for run server.
	*H:\project\Ewebgo\env\speedex>python manage.py runserver
6.After run server open browser and write specified url:-
	localhost:8000/
7.Now speedex project will be open and you will be redirect to homepage.
--->
<!---
   			OR
--->
<!---
1.If any error occured during process then:
	*download pycharm (IDE)
	*open file and select the project/Myenv/Ewebgo
	*set virtual enviroment to python in project setting
	*After succesful enviroment set click on terminal and write command :-
		python manage.py runserver
2.After run server open browser and write specified url:-
	localhost:8000/
--->  
