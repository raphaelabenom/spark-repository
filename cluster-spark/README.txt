
# Instalação e Configuração do Cluster Spark

# Abra o terminal ou prompt de comando e acesse a pasta onde estão os arquivos no seu computador

# Execute o comando abaixo para criar e inicializar o Cluster
docker-compose -f docker-compose.yml up -d --scale spark-worker=2

# Spark Master
http://localhost:9090

# History Server
http://localhost:18080

# Para desligar o Cluster
docker-compose -f docker-compose.yml down