# crud_angular_spring
Curso CRUD Angular + Spring por Loiane Groner

https://www.youtube.com/watch?v=qJnjz8FIs6Q

https://github.com/loiane/curso-angular/tree/master/crud-angular-spring/

Using Lubuntu:
sudo apt-get -y update
sudo apt-get -y upgrade
sudo apt-get -y autoremove

Github Desktop
wget -qO - https://packagecloud.io/shiftkey/desktop/gpgkey | sudo tee /etc/apt/trusted.gpg.d/shiftkey-desktop.asc > /dev/null
sudo sh -c 'echo "deb [arch=amd64] https://packagecloud.io/shiftkey/desktop/any/ any main" > /etc/apt/sources.list.d/packagecloud-shiftky-desktop.list'
sudo apt-get -y update
sudo apt install -y github-desktop

curl -fsSL https://deb.nodesource.com/setup_16.x | sudo -E bash -

sudo apt-get install -y nodejs gcc g++ make

curl -sL https://dl.yarnpkg.com/debian/pubkey.gpg | gpg --dearmor | sudo tee /usr/share/keyrings/yarnkey.gpg >/dev/null

echo "deb [signed-by=/usr/share/keyrings/yarnkey.gpg] https://dl.yarnpkg.com/debian stable main" | sudo tee /etc/apt/sources.list.d/yarn.list

sudo apt-get update && sudo apt-get install yarn

npm install -g @angular/cli

ng new crud-angular

