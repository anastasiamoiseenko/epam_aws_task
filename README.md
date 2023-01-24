## EPAM University Programs
### Cloud&DevOps Fundamentals Autumn 2022
## AWS Cloud Basic

1. Review Getting Started with Amazon EC2. Log Into Your AWS Account, Launch, Configure, Connect and Terminate Your Instance. Do not use Amazon Lightsail. It is recommended to use the t2 or t3.micro instance and the CentOS operating system.

![Image alt](https://github.com/anastasiamoiseenko/epam_aws_task/raw/main/screenshots/1.Server_name.png)
![Image alt](https://github.com/anastasiamoiseenko/epam_aws_task/raw/main/screenshots/2.Server_configuration.png)
![Image alt](https://github.com/anastasiamoiseenko/epam_aws_task/raw/main/screenshots/3.Instance_running.png)
2. Create a snapshot of your instance to keep as a backup

![Image alt](https://github.com/anastasiamoiseenko/epam_aws_task/raw/main/screenshots/4.server_snapshot.png)
![Image alt](https://github.com/anastasiamoiseenko/epam_aws_task/raw/main/screenshots/5.snapshot_created.png)

3. Create and attach a Disk_D (EBS) to your instance to add more storage space. Create and save some file on Disk_D

![Image alt](https://github.com/anastasiamoiseenko/epam_aws_task/raw/main/screenshots/7.EBS_created.png)
![Image alt](https://github.com/anastasiamoiseenko/epam_aws_task/raw/main/screenshots/8.attaching_volume.png)
![Image alt](https://github.com/anastasiamoiseenko/epam_aws_task/raw/main/screenshots/6.ssh-connect.png)
![Image alt](https://github.com/anastasiamoiseenko/epam_aws_task/raw/main/screenshots/9.mount_volume.png)
![Image alt](https://github.com/anastasiamoiseenko/epam_aws_task/raw/main/screenshots/10.creat_file.png)

4.  Launch the second instance from backup.

![Image alt](https://github.com/anastasiamoiseenko/epam_aws_task/raw/main/screenshots/11.image.png)
![Image alt](https://github.com/anastasiamoiseenko/epam_aws_task/raw/main/screenshots/12.Web.server.2.png)

5. Detach Disk_D from the 1st instance and attach disk_D to the new instance.

![Image alt](https://github.com/anastasiamoiseenko/epam_aws_task/raw/main/screenshots/13.detach_volume.png)
![Image alt](https://github.com/anastasiamoiseenko/epam_aws_task/raw/main/screenshots/14.attach_to_the_new_inst.png)

6. Review the 10-minute example. Explore the possibilities of creating your own domain and domain name for your site. Note, that Route 53 not free service. Alternatively you can free register the domain name *.PP.UA and use it.

![Image alt](https://github.com/anastasiamoiseenko/epam_aws_task/raw/main/screenshots/33.route53_domains.png)

7. Launch and configure a WordPress instance with Amazon Lightsail

![Image alt](https://github.com/anastasiamoiseenko/epam_aws_task/raw/main/screenshots/15.lightsail_instance.png)
![Image alt](https://github.com/anastasiamoiseenko/epam_aws_task/raw/main/screenshots/16.login_to_lightsail_instance.png)
![Image alt](https://github.com/anastasiamoiseenko/epam_aws_task/raw/main/screenshots/17.wp_working.png)
![Image alt](https://github.com/anastasiamoiseenko/epam_aws_task/raw/main/screenshots/18.staticip.png)

8. Review the 10-minute Store and Retrieve a File. Repeat, creating your own repository

![Image alt](https://github.com/anastasiamoiseenko/epam_aws_task/raw/main/screenshots/19.create_bucket.png)
![Image alt](https://github.com/anastasiamoiseenko/epam_aws_task/raw/main/screenshots/20.upload_file.png)
![Image alt](https://github.com/anastasiamoiseenko/epam_aws_task/raw/main/screenshots/21.download_file.png)

9. Create a user AWS IAM, configure CLI AWS and upload any files to S3

![Image alt](https://github.com/anastasiamoiseenko/epam_aws_task/raw/main/screenshots/22.new_IAM_user.png)
![Image alt](https://github.com/anastasiamoiseenko/epam_aws_task/raw/main/screenshots/23.aws_cli_install.png)
![Image alt](https://github.com/anastasiamoiseenko/epam_aws_task/raw/main/screenshots/24.bucket_cli.png)
![Image alt](https://github.com/anastasiamoiseenko/epam_aws_task/raw/main/screenshots/25.bucket_created.png)
![Image alt](https://github.com/anastasiamoiseenko/epam_aws_task/raw/main/screenshots/26.upload_file.png)
![Image alt](https://github.com/anastasiamoiseenko/epam_aws_task/raw/main/screenshots/27.file_uploaded.png)
![Image alt](https://github.com/anastasiamoiseenko/epam_aws_task/raw/main/screenshots/28.download_file.png)
![Image alt](https://github.com/anastasiamoiseenko/epam_aws_task/raw/main/screenshots/29.remove_the_file.png)

10. Review the 10-minute example Deploy Docker Containers on Amazon Elastic Container Service (Amazon ECS). Repeat, create a cluster, and run the online demo application or better other application with custom settings

![Image alt](https://github.com/anastasiamoiseenko/epam_aws_task/raw/main/screenshots/30.ecs_launch.png)
![Image alt](https://github.com/anastasiamoiseenko/epam_aws_task/raw/main/screenshots/31_sample_app_running.png)

11. Run a Serverless "Hello, World!" with AWS Lambda.

![Image alt](https://github.com/anastasiamoiseenko/epam_aws_task/raw/main/screenshots/32.lambda_func.png)

12. Create a static website on Amazon S3, publicly available (link1 or link2 - using a custom domain registered with Route 53). Post on the page your own photo, the name of the educational program (EPAM Cloud&DevOps Fundamentals Autumn 2022), the list of AWS services with which the student worked within the educational program or earlier and the full list with links of completed labs (based on tutorials or qwiklabs). Provide the link to the website in your report and СV.

![Image alt](https://github.com/anastasiamoiseenko/epam_aws_task/raw/main/screenshots/33.s3_buckets.png)

My website is [here](https://cloudevops.click)
