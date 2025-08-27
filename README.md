#  CRUD de Funcionários com JPA

Este é um projeto de estudo que implementa um **CRUD (Create, Read, Update, Delete)** para a entidade **Funcionário**, utilizando:

- **Java Persistence API (JPA)**
- **PostgreSQL**
- **Apache Tomcat**
- **NetBeans IDE**

---

##  Descrição

O projeto consiste em um exercício para praticar o uso de **JPA** integrado ao banco de dados **PostgreSQL**, realizando operações básicas em uma tabela de funcionários.

A tabela utilizada é a seguinte:

```sql
CREATE TABLE func (
  codigo SERIAL PRIMARY KEY,
  nome   VARCHAR(50),
  peso   FLOAT
);
