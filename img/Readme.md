## _The Development of a Static Website_

### _AWS instance_
![](./1.%20Creation-AWS-Instance.png)

A debian ubuntu linux distribution was spined up on AWS cloud platform for our practice.

### _Allow ports_
![](./2.%20port-80-allow.png)

As seen in the image, port 80 was allowed in security group and this is due to the fact that nginx listen on port 80. So attempt to make it reachable, we have to allow port 80 in the security group.

### _nginx webserver_
![](./3.%20nginx-webserver-status.png)

It's important to know if the nginx is up and running after installation and the command " systemctl status nginx" tells us if the installed nginx webserver is active and running as seen in the output.


### _html file content_
![](./4.%20html-file-content.png)
The code provided is written in html to create and design documents displayed in web browser.This structure allows browsers to interpret and display the web page correctly. 


### _The landing page_
![](./5.%20static-website-page.png)

This shows the landing page of the static website and the expected content served by the nginx webserver.

Thank you