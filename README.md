# docker_commands

1. For start the docker container use this commands.
   ``` docker run <Image_name> ```
2. Port maping in the docker.[maping post of linux and nginx]
   ``` docker run -p 80:80 nginx ```   
3. For running docker container ```docker run -d -p 80:80 nginx```.
   
5. Checking the status of the docker container ```docker ps```.

6. For stop the running image ```docker stop <Image_id>```.

7. List all docker images```docker ps -a```.

8. Allow 5000 port for runnig image ```ufw allow 5000```[Risk command].

9. Delete image ```docker rm <Image_Id>```.

10. Stop all the Images ``` docker system prune ```.

11. Stop docker forcefully ```docker rm -f <Image_Id>```.

12. For enter to inside the docker container using this command ```docker exec -it <Image_id> bash ```[ use ```exit``` command to exit from the container]

13. For copy files from one container to another container ```docker cp <source> <dest> ```.

14. To commit data inside the container using this commands , run this command from outside the container ```docker commit <Image_Id>```.

15. List docker Images ``` docker images ```.

16. Pull from docker ``` https://chat.openai.com/share/64251e61-e061-422b-8965-870642d02626 ```.

17. Push to the docker hub ``` https://chat.openai.com/share/a786f56b-e614-4372-878d-103a8ebc5a2f ```.

![image](https://github.com/VaibhavDabral11/docker_commands/assets/116658648/b8acfcd5-debb-43d9-85bf-c95bdd74dc8c)

For commands in more details ```docs.docker.com```
