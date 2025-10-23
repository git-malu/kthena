# 已经成为legacy，感觉可以淘汰了
https://cert-manager.io/docs/installation/helm/#installing-from-the-legacy-helm-repository
![alt text](assets/image.png)



# 日落
全面迁移到 OCI
https://community.broadcom.com/tanzu/blogs/carlos-rodriguez-hernandez/2025/01/14/bitnami-helm-charts-moving-to-oci?CommunityKey=56a49fa1-c592-460c-aa05-019446f8102f

为了保证向后兼容性，重定向到OCI。
因为老用户的老代码可能还在用这种方式安装。
我们的项目比较新，一开始就不让用户用这种老方式安装，也就不存在这种迁移问题了。
![alt text](assets/image-1.png)