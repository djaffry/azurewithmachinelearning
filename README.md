# azurewithmachinelearning
Sample project for creating a serverless azure function in combination with a machine learning model

The endpoint will accept an image to be uploaded and will return information about the uploaded image like age, gender, emotions.

## Pre Requisites

To do the live coding efficiently there are some pre-requisites that need to be done prior to your visit (see below)

One of them is creating a free azure account per team. The main reason for doing so is, that even after your visit you can continue experimenting and working on your Azure account and learn even more. 

If there are any obstacles please contact us then we need to find another solution.
Prerequisites for live coding

    Students form teams of 2-3
    each team needs a free azure account https://azure.microsoft.com/free/?ref=microsoft.com&utm_source=microsoft.com&utm_medium=docs&utm_campaign=visualstudio
        if the school is eligble https://azure.microsoft.com/en-gb/free/students/
    each team has to prepare a laptop with the following software:        
        install Python 3.7 https://www.python.org/downloads/release/python-370/
            add python install directory to your PATH variable
            verify with typing python --version
        install following python packages with
            pip install azure.functions 
            pip install opencv-python
            pip install onnxruntime
            pip install numpy
        install Visual Studio Code https://code.visualstudio.com/
        install Python extenstion https://marketplace.visualstudio.com/items?itemName=ms-python.python
        install Azure CLI https://docs.microsoft.com/en-us/cli/azure/install-azure-cli-windows?tabs=azure-cli
        install Azure Function extension https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-azurefunctions 
        install Arzue Function Core Tools https://docs.microsoft.com/en-us/azure/azure-functions/functions-run-local?tabs=v4%2Cwindows%2Ccsharp%2Cportal%2Cbash#install-the-azure-functions-core-tools
        install Postman https://www.postman.com/

## How To

+ Login to Azure in Visual studio code
+ Checkout and open folder 01-echoFunction
+ Continue with 02 and 03

