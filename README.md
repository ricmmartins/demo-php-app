# simple-php-app
Simple PHP app used with OpenShift demo

## Usage
1. Clone this repo ```git clone https://github.com/ricmmartins/demo-php-app.git```
2. Go to the app folder ```cd demo-php-app```
2. Build ``` podman build . -t demo-php-app```
3. Run ```podman run -d -p 8080:80 --name demo demo-php-app```
4. Check opening http://127.0.0.1:8080

## Publish to Quay.io
1. ```podman login quay.io```
2. ```podman tag demo-php-app quay.io/rmmartins/demo-php-app ```
3. ```podman push demo-php-app quay.io/rmmartins/demo-php-app ```

## Checking at Quay.io
1. Look at https://quay.io/repository/rmmartins/demo-php-app





