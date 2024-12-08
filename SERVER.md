## Connect to server
ssh -i my-certificate.pem  botcogno@102.209.118.44

## Send files to server
scp -i my-certificate.pem user_data botcogno@102.209.118.44:/etc/nginx/conf.d/
scp -i my-certificate.pem user_data botcogno@102.209.118.44

## Tag an image
- Tag image: `docker tag freqtradeorg/freqtrade:stable recreationza/freqtrade:stable`