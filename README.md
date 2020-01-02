--- seting mysql ---
sudo mysql -u root

CREATE USER 'server'@'localhost' IDENTIFIED BY 'server';

GRANT ALL PRIVILEGES ON *.* TO 'server'@'localhost' WITH GRANT OPTION;

EXIT;
