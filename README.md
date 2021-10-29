docker build --tag cryptin .
docker run -it -e coinmarketcap=MYKEY -e bootstrapserver=MyKafkaBootStrap -t cryptin /bin/bash