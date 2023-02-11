Cyclopedia App

Instructions on How to Run:

1) Open your terminal and keep it opened until the end
2) Navigate to the directory you want the project to reside in
3) Create a Python Virtual Environment (for example, while in /CapstoneProject)
	command: python -m venv virt
4) Activate the virtual environment (top command for linux + mac -can't confirm this-, bottom command for windows)
	command:  
		source \virt\Scripts\activate
		.\virt\Scripts\activate
	4b) You should now only have a 'virt' folder in your project directory
5) Install Django
	command: pip install django
6) Clone the repo into the project directory and CD into "Cyclopedia"
7) Open up the project using any code editor you'd like, I used Visual Studio 2022
8) In the terminal, while in '/CapstoneProject/Cyclopedia' run the django project:
	command: python .\manage.py runserver
	8b) Current urls are:
		''
		'/admin' -login with the credentials in 'superuser', I am unsure if this works for other people however. Let me know if it doesn't and I will tell you how to get the info. OR I can add more users.  
		'/book/1'
9) To close the server: CTRL + C