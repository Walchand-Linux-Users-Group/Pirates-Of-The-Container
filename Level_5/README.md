# Level 5
This time captain cargo don't want you to interact with the container, though he has given the path of the flag file.

## TASK

**Image Name**: docker pull ghcr.io/walchand-linux-users-group/meta/5:1.0

**Path to flag file**: /first_level/second_level/third_level/fourth_level

## HINT

**Topics Required**: Volumes

**Commands Used**: 

-
        docker volume create <VOLUME_NAME>
-
        docker run -v <VOLUME_NAME>:<PATH_IN_CONTAINER> <IMAGE_NAME>
-
        docker volume inspect <VOLUME_NAME>
