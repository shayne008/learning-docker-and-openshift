I decided to learn docker this week. I have noticed a lot people on X Twitter talking about it along with Kubernates.

So I did a little research and found a course on Udemy by Bret Fisher.

I figured I might as well learn OpenShift as well since it is very similar. Just going from docker to podman. 

What is in engrained in my head is build ship run. And honestly it has been as simple as that. As soon as I started the course I was able to get up and running first with the docker playground. Sometimes you just need to see stuff happen.

Next I did get docker installed on my homelab machine. I am running a fedora linux system. When I decided to learn linux I wanted to commit to it and learn it. It has been an interesting process. But not far off from Mac honestly.

Commands I learned this week:
# docker container run
# docker container run -d -p --name
# docker container run -it
# docker container run -d -p -name service bash
# docker container exec
# docker ps -a
# docker container logs
# docker container run -d --name -e
# docker container -rm
# docker pull
# docker image
# docker build

Using the above commands I was about to build containers and start services. I was about to see on localhost. I was about to push to my docker hub. You can find it on https://hub.docker.com/u/hthg02

I start to get familar with dockerfiles:

FROM
COPY
RUN
