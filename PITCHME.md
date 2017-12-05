---

### A Docker az ellen is véd!
<br>
<br>
#### <span class="gold" >Papp Lalyos</span>

 <span class="byline"> I. NetAcademia Webfejlesztő Konferencia </span>

---

## First steps with docker

Dont install it! Just play with it: 

- [PWD trainings](http://training.play-with-docker.com)
- [PWD](http://play-with-docker.com)
- [myPWD](http://pwd.lalyo.sh)

Note:
mention KataCoda: https://www.katacoda.com/learn 
[KataCoda](https://www.katacoda.com/courses/docker/playground)
[Editor](https://www.katacoda.com/courses/golang/playground)
---
 ## Demo
![demo](https://s3.amazonaws.com/media-p.slid.es/uploads/lalyos/images/943459/tenyer-dorzsol.gif)
---

## Container / VM

Containers are similar to VMs but not quite ...

![container-vm](assets/docker-cont-vm.png)
---
## Benefits

- quick/small
- it was working on my machine &#8482;
- security
- reproducible build
- reproducible db
- testing : local env / new software   

---
### Image and Container

Images 
- tar file: filesystem + meta
- immutable!

![img-cont](assets/docker-image-vs-cont.png)
---
## Image workflow

![image-workflow](assets/docker-interactions.png)

--- 
## Volumes

![volumes](assets/volumes.png)
---
## PWD stacks - 1

PWD Stacks:
- [github: pwd/stacks](https://github.com/play-with-docker/stacks/)

DockerHub
- [wordpress](https://hub.docker.com/_/wordpress/)
- [drupal](https://hub.docker.com/_/drupal/)
- [ghost](https://hub.docker.com/_/ghost/)
- [joomla](https://hub.docker.com/_/joomla/)

---
## PWD stacks - 2

Some more ...

- [FaaS](https://raw.githubusercontent.com/openfaas/faas/master/docker-compose.yml)
- [elasticsearch](https://hub.docker.com/_/elasticsearch/)
- [registry](https://hub.docker.com/_/registry/)
- [swarmpit](https://github.com/swarmpit/swarmpit)

Find by name `stack.yml`
- [github-find](https://github.com/docker-library/docs/find/master)

---
## Wordpress

```
docker exec -it \
 $(docker ps -qf expose=3306) \
 mysql -u root -psomewordpress wordpress
```
---

## Multiple Backends

Reverse Proxy
- haproxy
- nginx
- trafik [mutyi](https://docs.traefik.io)

---
# Kerdes?

---

# The End

![virageso](https://gifszinhaz.s3.amazonaws.com/uploads/gif/055_2_anim.gif)

 
- [tarantino](https://i.pinimg.com/originals/22/e2/21/22e221cd7f2e208aa2f08a550ef81471.gif)
- [taps](http://i.imgur.com/OoybIc2.gif)
- [szalad](https://i.makeagif.com/media/5-14-2015/sOnIJG.gif)
- [noormalis](https://i.makeagif.com/media/11-10-2015/SgtFEy.gif)
- [wtf](https://gifszinhaz.s3.amazonaws.com/uploads/gif/015_2_anim.gif)
- [hurra](https://gifszinhaz.s3.amazonaws.com/uploads/gif/038_2_anim.gif)
- [magic](https://i.giphy.com/ujUdrdpX7Ok5W.gif)


# Animgifs
![tarantino](https://i.pinimg.com/originals/22/e2/21/22e221cd7f2e208aa2f08a550ef81471.gif)
![taps](http://i.imgur.com/OoybIc2.gif)
![szalad](https://i.makeagif.com/media/5-14-2015/sOnIJG.gif)
![noormalis](https://i.makeagif.com/media/11-10-2015/SgtFEy.gif)
![wtf](https://gifszinhaz.s3.amazonaws.com/uploads/gif/015_2_anim.gif)
![hurra](https://gifszinhaz.s3.amazonaws.com/uploads/gif/038_2_anim.gif)
![magic](https://i.giphy.com/ujUdrdpX7Ok5W.gif)
