### :star: Implementação simples de uma arquitetura de Micro Serviço

- Laravel e NGINX

#### :zap: Como Intalar

- 1: cd example-company && composer install / cd example-user && composer install
- 2: cd nginx/
- 3: docker build -t example-nginx .
- 4: docker run -d --name example-nginx -p 80:80 -v $(pwd)/../example-user/:/var/www/example-user/ -v $(pwd)/../example-company/:/var/www/example-company/ example-nginx
- 5: acessar http://localhost/api/v1/company/profile ou http://localhost/api/v1/user/profile

