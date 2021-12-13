Ran the Application locally on my Mac using docker compose instructions:

Used the website to get a License Key to run the application:

LaunchInstanceID=FBFE823F-0DF2-42A3-8CF8-FF384DB4297E

- docker compose pull
- docker compuse up --detach (to run the containers in the background)
- docker ps -a (to verify if the containers are up)
- navigated to http://localhost:8080 to see the application.

- screenshot in robot-shop-orig.png

I was able to merge directly into the master branch by switching my clone to the maser branch instead of satish

This can be prevented in Github by modifying the Repo Settings:

Settings -> Branches -> Branch Protection Rule -> Require a pull request before merging

In order to change the logo:

-- looked at the web page via Inspect to find the file name: web/static/media/stan.png
-- made a copy of the original
-- copied the new logo PNG file web/static/media/stan.png
-- modified the web/static/index.html and added "Satish Kaushik" the Footer.
-- new screenshot  robot-shop-logo-sign.png

I had to do a "docker compose build" to rebuild the containers.

