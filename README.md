# polywc-parallel-coordinates
Web-Component that embeds and reuses D3 parallel coordinates. It is a pure Javascript Web-component implementation. It is based on ECMAScript v6 and D3js v4.7.

## How to install and use the web component

## How to extend the web component
There are many ways to setup the environment in order to make changes to the web component. Here I describe one that uses the bower link command. 

1. Clone the project from github

    > git clone https://github.com/polywc/polywc-parallel-coordinates.git
  
2. Link the project 

    > cd polywc-parallel-coordinates
    > bower link
    
Bower link will create a linking to the project directory.
    
3. Create a new directory everywhere on your computer

    > mkdir polywc-develop
    
4. Create a new bower.json file as follows:

    ```json
    { 
        "name": "polywc-develop",
        "version": "1.0.0",
        "dependencies": {
            "polywc-parallel-coordinates": "^0"
        }
    }
    ```

    

