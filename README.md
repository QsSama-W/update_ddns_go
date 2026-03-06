# update_ddns_go
## 一键安装/升级ddns-go
- 自动从GitHub拉取最新版本
- 自动解压并执行安装任务
- 适用于Linux-x86设备

- 命令①
- ```(command -v curl >/dev/null && curl -skL || wget -q --no-check-certificate -O-) https://raw.githubusercontent.com/QsSama-W/update_ddns_go/main/update_ddns_go.sh | bash```

- 命令②
- ```bash -c "$(curl -skL https://raw.githubusercontent.com/QsSama-W/update_ddns_go/main/update_ddns_go.sh)"```
