## Instrucciones de instalación

```npm init```

```npm install express```

# Código fuente
Descargar vía git desde el repositorio correspondiente,

# Perform a quick update on your instance:
```sudo yum update -y```
 
# Install git in your EC2 instance
```sudo yum install git -y```
 
# Check git version
```git version```
```Nota: Instalar desde este link https://cloudaffaire.com/how-to-install-git-in-aws-ec2-instance/```

# Ejecución

```node index.js```

# Install nginx
```sudo amazon-linux-extras install -y nginx1```

# Ver archivo nginx.conf
```cat /etc/nginx/nginx.conf```

# Chequear nginx
```nginx -t```

# Recargar nginx
```sudo nginx -s reload``` 

# Qué hacer si no puedo reinicar nginx
https://stackoverflow.com/questions/51402373/i-cant-restart-my-nginx

# Agregar compresión de archivos a nginx
```gzip on;```

```gzip_disable "MSIE [1-6]\.(?!.*SV1)";```

```gzip_vary on;```

```gzip_types text/plain text/css text/javascript image/svg+xml image/x-icon application/javascript application/x-javascript;```

# Servicio nginx activo
```sudo systemctl enable nginx```
