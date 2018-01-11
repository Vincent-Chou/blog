#Docker 入门


##镜像操作
	
	获取镜像
	docker pull 
	
	列出镜像
	docker image ls
	
	镜像体积
	docker system df
	
	虚悬镜像删除
	docker image prune
	
	删除本地镜像
	docker image rm
	
	搜索镜像
	docker search 
	

##容器操作

	启动容器
	docker run 
		 * -t 选项让docker分配一个伪终端并绑定到容易起的标准输入上
		 * -i 则让容器的标准输入保持打开
	
	启动已终止的容器
	docker container start
	
	后台运行 -d 
	如果不使用-d直接运行容器，会将输出打印到宿主机，使用后将在后台运行
	
	获取容器日志信息
	docker container logs [container ID or NAME]
	
	终止容器
	docker container stop
	
	查看容器
	docker ps -a
	
	进入容器
	docker attach -- 不推荐，当attach从容器退出时，会导致容器停止
	
	docker exec -i -t
	
	删除容器
	docker container rm
	
	清理所有处于终止状态的容器
	docker container prune
	
	