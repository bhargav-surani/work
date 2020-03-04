## Stastic website hostnig on S3 bucket.

1. Sing-in to AWS management console and open S3 service.

2. Now, click on `create bucket` to create new bucket for website content files and folders. Give unique name to bucket name while creating a bucket and choose region.

3. click on `bucket name` to open it. for web hosting, we have to change properties of bucket. so, click on `properties`.

4. we can see several properties of bucket. for web hosting click on `static web hosting`.for initial condition it is disable. Now choose `use this bucket to host a website`.

5. To choosing option `use this bucket to a host a website`. It will ask for name of our index and error document and click `save`.

6. By default, Amazon S3 does not allow public access to your buckets. so, to change permission of bucket click on permissions. 

7. By clicking on `permission`, it will open new page and click on `Block public access`. By default all block access is on. so click on edit to change permission and un-check `Block all public access` and click `save`. To confirm changes type confirm and click on `confirm`.

8. Due to giving bucket to public access, public can read, write and execute content of bucket. So, We have to give bucket to read only permission to others. So, In `Permission` tab click on `Bucket Poliocy`. and give read only policy to bucket.

9. Now upload index and error document on bucket.

10. Now click on `index.html`. it shows information of index.html. In overview we can see Object URL , open URL to see and confirm our static website is successfully hosted.

