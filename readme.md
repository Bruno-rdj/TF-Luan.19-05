TF - Este projeto foi desenvolvido como parte da atividade da disciplina de Desenvolvimento Web aula 11

* Nome: Bruno Rocha Rozadas de Jesus
* RA: 6324038

## Como Rodar o Projeto

### **1. Clonar o repositório**

```
git clone https://github.com/Bruno-rdj/TF-Luan.19-05.git

cd TF-Luan.19-05
```

---

### **2. Verifique se o Docker e o Docker Compose estão instalados**

Execute os comandos abaixo para garantir que as ferramentas estão instaladas corretamente:

```bash
docker --version

docker-compose --version
```

Se ainda não tiver o Docker e o Docker Compose instalados, siga as instruções oficiais de instalação:

- [Instalar Docker](https://docs.docker.com/get-docker/)
- [Instalar Docker Compose](https://docs.docker.com/compose/install/)

Após a instalação do Docker, verifique se tudo está funcionando corretamente dando os seguintes comandos: `docker --version` e o `docker-compose -- version`.

---

### **3. Finalize containers existentes (se houver)**

Antes de iniciar o projeto, pare e remova qualquer container em execução:

```bash
docker-compose down
```

---

### **4. Construa e inicie os containers com Docker Compose**

No diretório raiz do projeto, execute:

```bash
docker-compose up --build
```

Esse comando irá **construir as imagens** e iniciar os containers definidos no arquivo `docker-compose.yml`.

