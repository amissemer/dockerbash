A Docker image with Docker, Docker Machine and Docker Compose
===========================================

Purpose
----

Provide a way for Windows users to use Bash scripts along with docker, docker-compose and docker-machine commands.

Usage
----

From a directory under your home directory C:\Users\<userID>\ run:
	
	docker run -it -v %cd%:/home/dockerbash amissemer/dockerbash

You will then be logged into the Bash shell of the container and have visibility on the files of the current directory you started the command from.

Note
----

* With Docker for Windows, you need to enable the sharing of the drive you want to use, in Docker settings (accessible from the system tray).
* The Docker Toolbox tries to share your home directory automatically, but you're limited to subdirectories of your home directory.
