# F1 SAW
Web App with the aim of grouping everything useful about Formula 1

*keys.ini* file with setup keys inside is required 
to work properly with the DB (MySQL) and the [AWS-S3](https://aws.amazon.com/it/s3/) storage

For a proper presentation we suggest to view [F1 SAW](./F1_SAW.pdf)

**NB**: **ACADEMIC** purposes only
<hr>

### What you can do
- virtually buy products in the **STORE**
- keep yourself updated with the most recent **NEWS** 
- navigate in different **STATISTICS**, such as Drivers, Teams, Calendar and GP results (from 1950 to today).
- if you are an **ADMIN**, you can manage the store and users data, and email the users who subscribed to the newsletter

The news, teams and drivers lists are fetched through **web-scraping**
<hr>

### How
Back-end: PHP (and PHPMailer) / AWS-S3 / MySQL
<br>
Front-end: JS / CSS / Bootstrap / HTML
<hr>

### USAGE
- ```git clone --recursive-submodule {.git}```
- ```git submodule update --init --recursive```
- ```git submodule update --remote```


### SOURCES:
- [Formula 1](https://www.formula1.com/)
- [Open Weather Map](https://openweathermap.org/api)
- [AWS-S3](https://aws.amazon.com/it/s3/)

<hr>

#### Home
![Home page](./f1_project/assets/images/readme/home.png)

![Home page](./f1_project/assets/images/readme/home1.png)
<hr>

#### Circuits
![Circuits page](./f1_project/assets/images/readme/circuits_page.png)
<hr>

#### Store
![Store page](./f1_project/assets/images/readme/store_user.png)
<hr>

#### Admin dashboard
![Admin page](./f1_project/assets/images/readme/store_admin.png)


# F1-DATA
Dashboard to Analyze data about Formula 1.
For a proper presentation we suggest to view <a href="https://github.com/f1saw/f1-data/blob/main/F1-ARD.pdf">F1-ARD</a>

<hr>

### How
Python<br>
[f1db](https://github.com/f1db/f1db) (dataset)

### USAGE
- ```pip install pandas plotly dash dash_bootstrap_components```
- ```git clone https://github.com/f1saw/f1-data.git```
- ```cd f1-data```
- ```python dashboard.py```
- Go to ```http://127.0.0.1:8050/```

<hr>

#### SEASONS
![Seasons](./f1-data/assets/images/seasons.PNG)

#### CIRCUITS
![Circuits](./f1-data/assets/images/circuits.PNG)

#### DRIVERS
![Drivers](./f1-data/assets/images/drivers.PNG)

#### TEAMS
![Teams](./f1-data/assets/images/teams.PNG)
