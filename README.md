# SAPractica8_201404268

# Comando para realizar exportación

docker exec -i sapractica8_201404268_db_1 pg_dump --username postgres --password postgres > dump.sql

# Comando para realizar importación
docker exec -i sapractica8_201404268_db_1 psql --username postgres --password postgres postgres < dump.sql

# Video demostrativo 
https://youtu.be/joVSRNhmXlA