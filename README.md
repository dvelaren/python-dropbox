# Dropbox API Download

This is a simple script to download files from Dropbox using the Dropbox API.

## Setup

1. Create a Dropbox app at https://www.dropbox.com/developers/apps
2. Generate an access token for your app
3. Create a `.env` file in the root of the project with the following contents:

    ```sh
    DROPBOX_ACCESS_TOKEN=<your access token>
    ```
4. Create a folder named out in the root of the project:
    ```sh
    mkdir out
    ```
5. Install requirements:
    ```sh
    pip install -r requirements.txt
    ```

6. Run the notebook
