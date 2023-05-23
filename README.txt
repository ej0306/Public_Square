# Public Square 
### Web-based platform to search for Wi-Fi Hotspot
### throughout NYC

## Home Page 
![Homepage1](https://github.com/ej0306/psquare/assets/54604143/1d83a288-5366-4809-8fac-1adbe6823a2c)
![Homepage2](https://github.com/ej0306/psquare/assets/54604143/a2c2dc3b-9c4f-4848-b672-f5b7fb529595)
![Homepage3](https://github.com/ej0306/psquare/assets/54604143/65559cea-c32b-4afa-a4db-fc2b2d185791)
![Homepage4](https://github.com/ej0306/psquare/assets/54604143/51ad2d3d-8319-4d22-bdd3-b8ea5dd714c5)
![Homepage5](https://github.com/ej0306/psquare/assets/54604143/e4e3fea8-3766-4c1e-b5fb-4b8824afa5b5)
## Search Results
![Search Results](https://github.com/ej0306/psquare/assets/54604143/dbab7d9a-807e-4def-a1ef-7e48562f3a26)
## Lists of Wifi Hotspots
![List of Hotspots](https://github.com/ej0306/psquare/assets/54604143/feb81a56-1d3a-4286-b0a6-1d801472d1e6)
## Information about a specific Wifi Hotspot
![Information about hotspots](https://github.com/ej0306/psquare/assets/54604143/92b17bca-02bd-4cb4-bafd-09a4457451e2)
## User can review a specific Wifi hotspot
![Reviews by user](https://github.com/ej0306/psquare/assets/54604143/0c8e3b7a-6ea2-443f-9863-c464e01dc527)
## Example of a User Profile (This logged in user is an admin)
![Screenshot 2023-05-21 195704](https://github.com/ej0306/psquare/assets/54604143/73c6ad6e-1579-4e17-8f0b-d9fbd0f5918f)






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
