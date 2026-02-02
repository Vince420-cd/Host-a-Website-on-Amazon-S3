[README.md](https://github.com/user-attachments/files/25001431/README.md)
<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Host a Website on Amazon S3

**Project Link:** [View Project](http://learn.nextwork.org/projects/aws-host-a-website-on-s3)

**Author:** Vince Gayatgay  
**Email:** vincegayatgay132@gmail.com

---

![Image](http://learn.nextwork.org/curious_teal_bold_lulo/uploads/aws-host-a-website-on-s3_5d4474f9)

---

## Introducing Today's Project!

### Project overview

In this project, I will demonstrate how amazon S3 store and retrieve any amount of data at any time from anywhere on the web. I'm doing this project to learn about amazon S3 

### Tools and concepts

Services I used is amazon S3 only and the key concepts I learnt include S3 buckets and storing objects. Static website hosting on Amazon S3. Bucket website endpoints. Making objects publicly accessible using ACLs. Fixing the error 403 related to S3 object permissons. And lastly is the purpose of bucket versioning for data protection. 

### Time, challenges, and wins

This project took me approximately 40 mins The most challenging part was resolving the error but with the given instructions I resolve it very easily.

---

## How I Set Up an S3 Bucket

### What I did in this step

In this step I open Amazon s3 service, I will create a storage space for website files

### How long it took to create the bucket

Creating an S3 bucket took me like 3 mins to create it's very easy.

### Region selection

The Region I picked for my S3 bucket was Singapore because it is the closest region on my side.

### Understanding bucket name uniqueness

S3 bucket names are globally unique! So that other users in the world can't access it.

![Image](http://learn.nextwork.org/curious_teal_bold_lulo/uploads/aws-host-a-website-on-s3_ba6d42ad)

---

## Upload Website Files to S3

### What I did in this step

In this step, I will upload a website content in my bucket. 

### Files I uploaded

I uploaded two files to my S3 bucket - they were index.html and a zip file called NextWork - Everyone should be in a job they love_files and I extracted the folder to put it to my bucket. 

### How the files work together

Both files are necessary for this project as they serve as design and functionality for the website that I will upload in my bucket. 

![Image](http://learn.nextwork.org/curious_teal_bold_lulo/uploads/aws-host-a-website-on-s3_a265af88)

---

## Static Website Hosting on S3

### What I did in this step

In this step, I will configure a static website on Amazon S3 because it is the process of making my website publicly available on the internet.

### Understanding website hosting

Website hosting means is what makes your website public on the internet. It means storing your HTML file on a web server, so it's accessible online. Without hosting, your HTML file would only be visible as a local file on your computer.

### How I enabled website hosting

To enable website hosting with my S3 bucket, I simply select my object and set to make public using acl in actions tab.

### Access Control Lists (ACLs)

An ACL is a set of rules that decides who can get access to a resource. I disabled my acl to simply access to this bucket and its objects that can be specified using ACLs.

![Image](http://learn.nextwork.org/curious_teal_bold_lulo/uploads/aws-host-a-website-on-s3_c22c54c0)

---

## Bucket Endpoints

### Understanding bucket endpoint URLs

Once static website is enabled, S3 produces a bucket endpoint URL, which is a bucket website endpoint is just like a regular website URL. It lets people visit S3 bucket's files as a website.

### What I saw when I tested the endpoint

When I first visited the bucket endpoint URL, I saw an 403 Forbidden error message The reason for this error was the web server recognizes my request but refuses to authorize access to the requested resource. In other words, My static website is being hosted by amazon S3, but the actual HTML/image files I've uploaded are still private. 

![Image](http://learn.nextwork.org/curious_teal_bold_lulo/uploads/aws-host-a-website-on-s3_22ce4daf)

---

## Success!

### What I did in this step

In this step, I will make my objects in my S3 bucket public, to make my website files in S3 publicly accessible and to see my website live on the internet. 

### How I resolved the 403 error

To resolve this 403 Forbidden error, I simply just select the two objects in my bucket and set the actions to make public using acl

![Image](http://learn.nextwork.org/curious_teal_bold_lulo/uploads/aws-host-a-website-on-s3_5d4474f9)

---

## Bucket Policies

### What I did in this extension

### Understanding bucket policies

### What my bucket policy does

---

---
