## source link
[GitLab CI CD Tutorial for Beginners [Crash Course]](https://www.youtube.com/watch?v=qP8kir2GUgo)

# CD
ssh-keygen
key w/ hosting name
copy .pub key to hosting
create ubuntu droplet on hosting w/ added ssh key
ssh -i ~/.ssh/<key-name-without-pub> root@<droplet-public-ip>
yes
apt update  
 apt install docker.io -y
docker ps

Settings > CI/CD > Variables
copy private ssh key
press enter for easy parsing
Type=v'File'
'Add Variables'

delete droplet after demo to not charge the money for hosting
