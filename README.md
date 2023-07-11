# Login Page
Simple login page

## Build Image
docker build -t my-loginpage .

## Run Container
docker run -dit --name my-loginpage -p 8080:80 my-loginpage