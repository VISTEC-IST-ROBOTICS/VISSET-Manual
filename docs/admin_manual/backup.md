1. You need to backup 2 volumns of two docker (snipeit, mariadb)
2. access to container,
    - snipeit

            docker exec -it snipeit bash
            cd /var/lib
            tar cvf web_backup.tar snipeit/
     
            # exit from container
            docker cp snipeit:/var/lib/web_backup.tar .


    - mariadb

            docker exec -it mariadb bash
            cd /var/lib
            tar cvf db_backup.tar mysql/

            # exit from container
            docker cp mariadb:/var/lib/db_backup.tar .
