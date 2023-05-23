# Public Square 
### Web-based platform to search for Wi-Fi Hotspot throughout NYC

## Home Page 
![Homepage1](https://github.com/ej0306/Public_Square/assets/54604143/3681fc2c-69a0-49db-9a20-481453347cde)
![Homepage2](https://github.com/ej0306/Public_Square/assets/54604143/06b80882-f3ca-414f-9c7d-75b04fdd2e8c)
![Homepage3](https://github.com/ej0306/Public_Square/assets/54604143/6b989511-639f-4e86-9a50-799c20a4edb6)
![Homepage4](https://github.com/ej0306/Public_Square/assets/54604143/6ce71558-b789-42c7-89c3-2f4c67e9c118)
![Homepage5](https://github.com/ej0306/Public_Square/assets/54604143/667558e0-5942-4e95-a61d-cf4e601212d2)
## Search Results
![Search Results](https://github.com/ej0306/Public_Square/assets/54604143/a5436ec2-8a2f-4dfa-a899-5479e1d6deec)
## Lists of Wifi Hotspots
![List of Hotspots](https://github.com/ej0306/Public_Square/assets/54604143/21a8397e-4041-4b43-b0ea-fc839bec244c)
## Information about a specific Wifi Hotspot
![Information about hotspots](https://github.com/ej0306/Public_Square/assets/54604143/b8bfe54e-1174-40e5-9c78-50cd994a82ec)
## User can review a specific Wifi hotspot
![Reviews by user](https://github.com/ej0306/Public_Square/assets/54604143/14403901-1cb8-42a9-bfe4-4228aee954cc)
## Example of a User Profile (Admin logged in)
![Screenshot 2023-05-21 195704](https://github.com/ej0306/Public_Square/assets/54604143/0571adeb-74ab-46fa-ac1c-97199852d2f4)





## Installation

1. Open github and clone '336_Project_2' repository

2. Open terminal/command prompt and go to the path of the repository

3. Go to the directory "NYC_Public_Wifi

4. Type "pyhton -m venv environment-name" on the cmd for WINDOWS
 	"python3 -m venv environment-name" on the terminal for MAC

	*Note: you might not need to install an environment for MAC
	       try to run step 4 for mac before installing the environment.

5. Activate environment by using "source env_name/bin/activate" for MAC
				 "env_name\scripts\activate" for WINDOWS

6. Type "pip install -r requirements.txt"

7. Type "pip install django-bootstrap4" to install bootstrap

8. Type "pip install numpy" to install numpy

9. Make migrations by using "python manage.py migrate"

10. After migration, createsuperuser "python manage.py createsuperuser"

11. After creating super user, run "python manage.py runserver"

12. Copy localhost link (http://127.0.0.1:8000/) and paste it to your browser.
	- By logging in as a superuser, user will be able to see the admin tools
	- By logging in as a normal user, user will be able to see a normal page
	  w/out the admin tools.


#Usage

Admin: 
	Update/Delete Neighborhood List
	Update/Delete Hotspot List
	Update/Delete Provider List

User:
	Search for Wi-Fi Hotspot
	Rate the Hotspot
	Write a review

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
