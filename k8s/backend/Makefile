.PHONE: gen
gen:
	@echo "#THIS FILE WAS GENERATED, DO NOT EDIT MANUALLY\n" > cluster/nginx_conf.yaml 
	@kubectl create configmap backend-nginx --from-file=nginx/default.conf --dry-run	-o yaml >> cluster/nginx_conf.yaml