1 - Talvez precise adcionar as duas entradas de hosts ao seu arquivo host na sua máquina host. 
	no Windows, edite C:\Windows\System32\drivers\etc\hosts
	1.1 - Abrir o notepad como Administrador

	127.0.0.1 fiplan-struts.localhost fiplan-spring.localhost

	PS: Testar só no caso de não funcionar!

Iniciar o container
	docker-compose up -d

Parar o container:
	docker-compose down

Acessar os dois:
	http://fiplan-struts.localhost:8080 e http://fiplan-spring.localhost:8080


Comandos 
	docker exec {CONTAINER_ID} nginx -s reload