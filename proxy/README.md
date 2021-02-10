If you want to add a custom configuration, add it to custom_config.conf. If not, I'd delete it and line 18 in docker-compose.yml

For example, in my config, I allow files up to 10mb to be uploaded with "client_max_body_size 10m;"
