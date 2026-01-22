
# Binance Asset Recovery SAPI postman setting

Using this method could submit the request for retrieving the unlisted coins that deposit to your Binance Account.

## How to import and configure

- Download the `Asset-Recovery-SAPI-Postmand-collection` repository.

- Click the `Import` button. On Postman for Mac, for example, the button is at the top left:

<img width="75%" height="75%" alt="image1" src="https://github.com/user-attachments/assets/a3b7c75d-e00b-408a-a377-bb51abb95c82" />

- On the `Import` pop-up page, select the `Folder` tab. Click the `Choose folder from your computer` button and choose the root folder of the downloaded repository.

<img width="40%" height="40%" alt="image2" src="https://github.com/user-attachments/assets/a9297faa-7cf8-4552-92e0-90e592439dac" />

- With the same step import the environments you would like to import and click the `Import` button.

<img width="75%" height="75%" alt="image3" src="https://github.com/user-attachments/assets/aee4d750-756b-44f8-982d-fd02ed09db69" />

- Select the `Environments` tab on the left, choose an environment, and set your Api Key and Secret Key by changing the `Current Value` column (see screenshot);
(The `Timestamp`, `nonce`, `Signature`, `Initial Value` fields can be left empty as they’ll be automatically filled by Postman when sending a request.)

<img width="75%" height="75%" alt="image4" src="https://github.com/user-attachments/assets/2fa1c44b-dcd9-4366-8a68-289bba55f2a8" />

- Select your newly-added environment from the environment dropdown menu. On Mac, this is at top right, to the left of the eye icon.

<img width="60%" height="60%" alt="image5" src="https://github.com/user-attachments/assets/e4d2a1e6-a9cf-4b8f-ac27-dc0fa7bb7b0e" />


## How to get the api key and secret key of Binance

Binance API key and secret key could get from the api management page in your Binance Account.

## Postman safety practices
The following practices are advised to secure your account's safety:

- Don't use Collections obtained from an unknown source.
- Review the environment JSON file before its usage.
- Don't use any code that you don't understand.
- Make sure that the withdrawal permission **is not enabled** for your API keys.
- When you finish trying out the API, delete your API keys.
