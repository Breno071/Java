# ===============================
# = DATA SOURCE
# ===============================

# Coloque aqui as configurações para conexão com o banco de dados
spring.datasource.url=jdbc:postgresql://localhost:5432/springbootdb
spring.datasource.username=postgres
spring.datasource.password=senha
spring.datasource.driver-class-name=org.postgresql.Driver

# ===============================
# = JPA / HIBERNATE
# ===============================

# Mostra o log de cada query SQL
spring.jpa.show-sql=true

# schema will be automatically created afresh for every start of application
# schema será automaticamente criado cada vez que a aplicação iniciar 
spring.jpa.hibernate.ddl-auto=create-drop
