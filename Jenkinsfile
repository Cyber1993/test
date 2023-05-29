pipeline 
{
    agent any
    stages 
    {
        stage('Hello') 
        {
            steps 
            {
                echo 'Hello World 2'
            }
        }
        stage('Shell1') 
        {
            steps 
            {
                sh 'ls /etc/netplan'
            }
        }
        stage('Shell2') 
        {
            steps 
            {
                sh 'ls /home/'
            }
        } 
        stage('start install zabbix_____1') 
        {
            steps 
            {
                sh 'mkdir /var/lib/zabbix/
                sh 'cd /var/lib/zabbix/'
                sh 'ln -s /usr/share/zoneinfo/Europe/Kiev localtime'
                sh 'echo 'Europe/Kiev' > timezone''
                sh 'sudo docker network create zabbix-net'
            }
        }       
    }
}
