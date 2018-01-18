https://docs.chef.io/ctl_chef_solo.html

https://github.com/chef
---
#chefsolo

curl -s https://omnitruck.chef.io/install.sh | sudo bash -s -- -P chefdk
(= curl -L https://www.opscode.com/chef/install.sh | sudo bash )

sudo chef generate cookbook nginx
sudo knife cookbook create nginx



https://docs.chef.io/ctl_chef.html
chef generate cookbook ruby-env
#GUI recommened
chef generate attribute /home/vagrant/shared/ruby-env default
chef generate template /home/vagrant/shared/ruby-env .bash_profile.erb
