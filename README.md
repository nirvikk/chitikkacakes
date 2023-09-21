# Chitikka Cakes

Welcome to the Chitikka Cakes project! This is a Node.js service called `chitikka-node-service` that allows you to explore a world of delicious cakes.

## Getting Started

To get started with the Chitikka Cakes project, follow these simple steps:

1. **Clone the Project**: First, clone this repository to your local machine using the following command:

   ```shell
   git clone https://github.com/nirvikk/chitikkacakes.git
   ```

2. **Navigate to the Project Directory**: Change your current directory to the `chitikka-node-service` directory:

   ```shell
   cd chitikka-node-service
   ```

3. **Install NPM Dependencies**: Make sure you have Node.js and NPM (Node Package Manager) installed on your system. If not, you can download and install them from [nodejs.org](https://nodejs.org/). Then, install the project's dependencies by running:

   ```shell
   npm install
   ```

4. **Start the NPM Server**: Once the dependencies are installed, start the NPM server by running:

   ```shell
   npm start
   ```

5. **Browse the Application**: Open your web browser and navigate to [http://localhost:8080](http://localhost:8080) to access the Chitikka Cakes application.

# Alternatively

## Build the Image using Dockerfile

1. Navigate to your project directory where the Dockerfile is located.

   ```bash
   $ cd chitikka-node-service

2. Run the following command to build the Docker image. Replace `chitikka-node-app` with your desired image name.

   ```bash
   $ docker build -t chitikka-node-app .
3. Now that we've created the Docker image, let's run our image on port `8000` 

   ```bash
   $ docker run --name chitikka-api -d -p 8000:8000 chitikka-node-app
   ```
   Where `chitikka-api` is the container name and `chitikka-node-app` is the docker image

4. You can verify that the container is running by checking the list of running containers:

   ```bash
   $ docker ps

5. Stop/Start the Instance
   ```bash
   $ docker stop chitikka-api```
   ```bash
   $ docker start chitikka-api```


You can now explore and interact with the Chitikka Cakes website. Enjoy browsing through a mouthwatering collection of cakes and desserts.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Happy Cake Hunting! 🍰🎂
