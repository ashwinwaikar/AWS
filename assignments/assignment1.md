**What is cloud computing:**

In the simplest terms, **cloud computing** means storing and accessing data and programs over the Internet instead of your **computer&#39;s** hard drive. The **cloud** is just a metaphor for the Internet. ... The **cloud** is also not about having dedicated network attached storage (NAS) hardware or server in residence.

**Advantages of cloud:**

**1] Pay as you go**

**2] You get on demand resources**

You can scale down or up like we can increase or decrease the RAM

**3] Fast development and deployment**

\&gt;Before some time you had to take the servers on a lease. It takes time to physically transfer the servers. And also for that u have to maintain a temperature also to maintain security as well as the electricity and also the cloud had removed all these things totally

In this, you don&#39;t have need to pay for the upfront like security deposit and all

Just go use the resources if u want u can increase the resources.

If I have a startup, If Today I need 10 GB tomorrow I need 20 gb

Then it is very easy to increase it inside the cloud without any issue.

**4]Outsourced management**

Here administration work is get handled by the aws.

How to maintain the temperature, electricity all these things are get handled by the aws.

\&gt;Provider handles the administration

\&gt;Increased Reliability Means our cloud becomes the trustworthy

It gives 99.99999% surety to provide the resources .But in some cases like the natural disasters , their data center is get affected then to save thereselfs they don&#39;t give the 0.0001% guaranty

\&gt;Security

Security is also get managed by the cloud. Security is not just related to the hacking

Whenever you have the datacenter you have to do many of the things: like cctv,so that no one should come in our data enter and copy our data. Or we have a security guard to protect our data.

It also includes software as well as the network security and many more

So we have to not provide the security as it is already get provided or outsourced by the cloud.

**5] Lower cost**

As the cloud is pay as you go model, how much you use you have to pay only that much and not more than that

**6] No geographical barrier.**

**7] No need of the infrastructure**

**LEVELS OF ABSRTRACTION**

In the cloud you get resources a s a service. They had categorized it, which is known as the level of abstraction.

**1]saas(Software as a service)**

For example- tableau,splunk,storm.Like ms office availability is nothing but a sw as a service.

So whatever sw are get used on the industry level are get provided by the cloud as sw as a service.

**2]paas[Platform as a service]**

It is nothing but a developer facing service means services which are get used by the developer in a day to day life like the hosted database.

You get any of the database installed by just clicking next and again it is get managed by the aws. Also we get hadoop as a service. and also different IDE s by using which we can develop.

**3]Iaas[Infrastructure as a service]**

It includes the raw computing resources.

It includes:

1]Vm -ec2

2]disks(volume)

Vm is nothing but a virtual machine and here you are working in the ec2 so called it as a ec2

When you say I have hard disk instead of that here you say I have volume

**Next service is S3**

If I say s3 service it is the storage engine. Storage engine means, I can store any type of the data

there as an object .It is a kind of Google drive.

Go to services\&gt;type s3(scalable storage in the cloud)\&gt;

Now in s3 we make some things. If I want to store some data then as drive allows it ,but s3 not allows it

So there is the concept under s3, which is known as the BUCKET

**BUCKET:**

Bucket is like a folder .we make folder under that we store file into that .same thing we can make folder inside the bucket .It is on you up to what level you have to go

How to create the Bucket?

Create bucket\&gt;Give any name to bucket suppose I give demo\&gt;Remaining things keep it

by default don&#39;t change anything\&gt;click on create bucket

It gives error as it already exists why is it so?

We had not create bucket before, Then why it is saying that it already exists

When you create bucket ,bucket name is always region wise like global

In global dropdown it will say that s3 does not require the global selection

**So, this name should be unique across the aws**

Now give the name as vita-demo-20 and click on create bucket. Now our bucket is ready

Now click on that vita-dem-20

In that we have different options:

1) create folder

2) Upload

Now let upload some file and then click on the upload

How to make a folder?

click on create folder\&gt;give the folder name as demo \&gt;save

Now when u make the parent bucket it may have some duplicate

Our parent folder top should be the unique across the aws

Again u can create the folder or upload it is totally depends on you that how many folders do u want to create?

Here we can also host our website.

**Firewall** -Filters the network traffic

Os has firewall

**1] Inbound-**you ctrl incoming traffic

**2] Outbound**- you ctrl outgoing traffic

Search for firewall

Click on windows defender firewall security

You have inbound and outbound rules\&gt;click on inbound

In that you give the access to the ports .Now suppose you have a server on the port 80

And if we don&#39;t give access here, then from browser no one could access it

On RHS\&gt;New rule\&gt;click on the port\&gt;Next \&gt;portname-80\&gt;next\&gt;Allow the connection\&gt;Next\&gt;select all\&gt;next\&gt;demp-80-port\&gt;finish

AWS has given the cloud&#39;s firewall. They also provided inbound and outbound

So that I will be easy for the user .No need to learn the networking.

It is known as the **&quot;Security Groups&quot;**

So traffic first goes here then it goes towards the os

In aws educate website on rhs you will see the security groups in that there is a option of vita-demo-20,view inbound rules and view outbound rules

Click on vita-demo-20\&gt;In that inbound rules\&gt;Edit inbound rules\&gt;You can add or delete

What will happen bcz of that?

So in this way cloud make easy for the security purpose.
