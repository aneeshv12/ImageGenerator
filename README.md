# ImageGenerator
Using the OpenAI API, generate an image based on any text that is inputted

## Getting Started
* Go to (https://beta.openai.com/) and register for a free account. After signing up, create an API key under settings. 

* Next, follow these steps in your command line

``` shell
# Clone the repository using this command:
git clone git@github.com:aneeshv12/ImageGenerator.git

#After cloning, create a .env file using this command:
touch .env
```

* In the .env file, enter the API key that you generated on the OpenAI API website like this:
```
VITE_Open_AI_Key = <API_KEY>
```

### Installing
* Run this to install all the required dependencies
```
npm install
```

### Executing and running the program
* Run this command to start the application:
```
npm run dev
```