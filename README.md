## Welcome to Halalan Github

Run these commands inside the root(main) folder of halalan (git branch must show fix-docker-setup is the current branch)
1. docker compose build
2. docker compose up -d
3. Check if halalan-legacy container is viewable and running in docker desktop
4. Go to phpMyAdmin page: http://localhost:8081 
5. username: halalan_user, pword: halalan_pass
6. Check if halalan database has contents
7. View login pages 
8. Admin login - user: admin2, pword: admin123



### Note if no database in phpMyAdmin (cannot access login pages)
1. In phpMyAdmin, press import in the top-center of the page
2. Import halalan.sql from the dump folder
3. If successful, retry page


### Login pages for localhost

Admin: http://localhost/index.php/gate/admin
Voter: http://localhost/index.php/gate/voter

