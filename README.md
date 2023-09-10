CREATE USER 'mecanica_user'@'%' IDENTIFIED BY 'mecanica_pass';
GRANT ALL PRIVILEGES ON mecanica_db.* TO 'mecanica_user'@'%';