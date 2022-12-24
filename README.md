# ai

npx create-react-app my-app
npm start

sudo docker build -t my-app .
sudo docker run -p 3000:3000 my-app

sudo docker login
sudo docker tag my-app canada/standup-listing
sudo docker push canada/standup-listing
