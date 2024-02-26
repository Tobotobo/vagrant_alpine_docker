# vagrant_docker_provisioning


[Vagrant - Docker Provisioner](https://developer.hashicorp.com/vagrant/docs/provisioning/docker)
[DockerイメージからGitLab環境を構築(GitLab&Runner)](https://qiita.com/Nats72/items/ca80b0bfede4d8e10158)

```ruby
Vagrant.configure("2") do |config|
  config.vm.box = "hashicorp/bionic64"
  config.vm.box_version = "1.0.282"
  config.vm.provision "docker" do |d|
    # 
  end
end
```