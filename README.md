# DPU_CT519_LAB4
วิธีใช้งาน  
sudo git clone https://github.com/645162010014/DPU_CT519_LAB4.git  
cd DPU_CT519_LAB4 
sudo docker-compose up -d  
sudo docker exec -i db sh -c 'exec mysql -uroot -p"$MYSQL_ROOT_PASSWORD"' < mysql-backup/my_data_645162010014.sql  
เข้า browser พิมพ์ ip ของเครื่อง vm  
