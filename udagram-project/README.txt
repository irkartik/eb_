Github Link : https://github.com/rajujha373/eb_

ElasticBeanstalk URL : http://udacity-udagram-dev.us-east-1.elasticbeanstalk.com
                     : http://udacity-udagram-dev.us-east-1.elasticbeanstalk.com/filteredimage?image_url=https://raw.githubusercontent.com/rajujha373/static/master/404.jpg


Note:

1. Github repository has two branches i.e dev and master.
2. I have modified the /src/server.ts to support /filteredimage?image_url={{}} route.
3. program has been made to throw 400 error if image_url is passed blank.
4. try catch block has been implemented to handle any errors that comes while processing the image and throws 422. But there is some bug in /src/util/util.ts due to which Jimp throws exception and crashes. However, I didn't modify the starter code.
