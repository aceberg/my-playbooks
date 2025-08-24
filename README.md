# my-playbooks
Short Ansible playbooks I created to automate my work

## Add `apt` repos

| Name | Description | Source |
| ------ | ------ | ------ | 
| [firefox-nightly.yml](repo/firefox-nightly.yml) | Firefox Nightly | [mozilla.org](https://blog.nightly.mozilla.org/2023/10/30/introducing-mozillas-firefox-nightly-deb-packages-for-debian-based-linux-distributions/) |

## Install apps in `Docker` containers

| Name | Description | Source |
| ------ | ------ | ------ | 
| [AnyAppStart.yml](docker/AnyAppStart.yml) | Start/Stop/View Logs for apps in Docker, Systemd, VMs or anything else | [AnyAppStart](https://github.com/aceberg/AnyAppStart) |
| [BookTr.yml](docker/BookTr.yml) | Translate text side-by-side using LibreTranslate API | [BookTr](https://github.com/aceberg/BookTr) |
| [gitea.yml](docker/gitea.yml) | Gitea: Git with a cup of tea - A painless self-hosted Git service | [Gitea](https://docs.gitea.com/installation/install-with-docker) |
| [watchtower.yml](docker/watchtower.yml) | Automate Docker container image updates | [watchtower](https://github.com/nicholas-fedor/watchtower) |
| [wikidocs.yml](docker/wikidocs.yml) | Just a databaseless markdown flat-file wiki engine | [WikiDocs](https://github.com/Zavy86/WikiDocs) |

## Install and configure `Server` software

| Name | Description | Source |
| ------ | ------ | ------ | 
| [Incus](server/Incus) | Install Incus (fork of LXD) | [linuxcontainers.org](https://linuxcontainers.org/incus/) [wiki.debian.org](https://wiki.debian.org/Incus)|

    
<br>
<hr>

### Outdated playbooks moved to branch [old_2022](https://github.com/aceberg/my-playbooks/tree/old_2022):

| Name | Description | Link |
| ------ | ------ | ------ | 
| ELK | Basic installation of ElasticSearch, Logstash, Kibana | [ELK](https://github.com/aceberg/my-playbooks/blob/old_2022/ELK) |
| Jenkins | Install Jenkins | [jenkins.yml](https://github.com/aceberg/my-playbooks/blob/old_2022/jenkins/jenkins.yml) |
| K3s | Install K3s, Helm and Kuberneres Dashboard | [k3s.yml](https://github.com/aceberg/my-playbooks/blob/old_2022/k3s/k3s.yml) |
| OpenProject | Install OpenProject | [openproject](https://github.com/aceberg/my-playbooks/blob/old_2022/openproject) |
| Terraform | Install terraform and configure qemu/libvirt to work with it | [terraform.yml](https://github.com/aceberg/my-playbooks/blob/old_2022/terraform/terraform.yml)|
| **User config** | 
| Apt | Add additional PPA and apt repositories | [apt.yml](https://github.com/aceberg/my-playbooks/blob/old_2022/repo/apt.yml) |
| Beep | Enable beep | [beep.yml](https://github.com/aceberg/my-playbooks/blob/old_2022/beep/beep.yml) |
| Tmux | Install and configure tmux for user | [tmux](https://github.com/aceberg/my-playbooks/blob/old_2022/tmux) |
| WiFi | Restart hostapd and DHCP-server | [wifi.yml](https://github.com/aceberg/my-playbooks/blob/old_2022/wifi/wifi.yml) |
