#chefsolo

curl -s https://omnitruck.chef.io/install.sh | sudo bash -s -- -P chefdk
(= curl -L https://www.opscode.com/chef/install.sh | sudo bash )

sudo chef generate cookbook nginx
sudo knife cookbook create nginx