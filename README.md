# traefik
此为 traefik 2.1 版本的编写的基础yaml文件


crd.yaml: 创建的k8s CRD 
dashboard.yaml： 给traefik 2.0 界面做的域名指向
deployment.yaml：包含traefik的serviceaccount和deployment的设置，静态信息采用cli方式写入
rbac.yaml：授权文件
service.yaml：服务映射的端口，可以直接采用node端口访问
