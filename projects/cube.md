# cube portfolio

## managing

docker run -d -w ... -v ... -p 4200:4200 --name cube node:slim npm start

docker logs -f cube

docker stop cube
docker rm cube

 ## general description

a cube is displayed on /main (default route ""). Each face is a page of the portfolio :

  - front - profile : get profile.json in github/api to load profle inside the app
  
  - left - gallery : get images/ in github/api to loads image to display ¹
  
  - right - projects : get projects in from localhost:5555/projects to loads projects descriptions ²
  
  - back - read comment / add comment if auth prompt / get history if auth / exec python script ?
  
  - top - project history + docs
  
  - bottom - more info about me , info about project
  

 ## 


 ## note 

 - ¹ : bug in mini picture logic
 - ² : maybe readme in github ?
 - 
 
