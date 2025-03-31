 ![SoftMakers](https://www.softmakers.com.br/assets/img/logotipo14xxhdpi.png)

# Desafio Estágio Desenvolvedor Fullstack - Concluído ✔️

- Por alguns problemas técnicos, tive que separar o projeto em dois repositórios: `FrontEnd-PetShop` e `BackEnd-PetShop`.
Devido a isso, foi necessário adicionar os repositórios como submódulo desse repositório atual. A respeito da finalidade submódulo do Git, esse funcionalidade permite incluir um repositório dentro de outro, mantendo-os como projetos separados. Isso é útil para gerenciar dependências externas ou reutilizar código entre diferentes projetos sem duplicação. E com isso, os repositórios citados acima são acessíveis para uso e teste.

- Segue abaixo as etapas a serem seguidas para consiguir clonar o repositório atual juntamente com seus submódulos! ⚠️


## 📑 Passo a passo para iniciar e testar o Projeto
-  Faça o clone do repositório, trazendo juntamente seus submódulos utilizando o seguinte comando:
```
git clone --recurse-submodules <LinkDoRepositório>
```

-  Caso tenha clonado sem os submódulos, inicialize-os manualmente:
```
git submodule update --init --recursive
```

  
- Após clonar o repositório e abrir o BackEnd. Primeiramente, é necessário rodar o comando para verificar se as dependênicas já estão instaladas em sua máquina, e após esse processo importantissímo, podemos iniciar o servidor. Segue abaixo os comandos a serem executados em ordem!
> Ao iniciar esse projeto, ele rodará na Porta 3000.
```
npm install
```

```
npm run start:dev 
```

- Em seguida, será necessário fazer o mesmo processo com o FrontEnd, agora dessa vez, utilizaremos um outro comando para iniciar a aplicação:
> Uma vez que o BackEnd já esteja rodando, o FrontEnd rodará na Porta 3001.
```
npm install
```

```
npm run dev
```

- No terminal da IDE que estiver rodando o FrontEnd. Você receberá algumas informações da aplicação iniciando juntamente com o link de acesso ao sistema:
```
Local: [ http://localhost:3000 ]
```


## 💻 Link dos Repositórios
- Clique aqui para acessar o 
[BackEnd-PetShop](https://github.com/lucasptrick/BackEnd-PetShop)

- Clique aqui para acessar o 
[FrontEnd-PetShop](https://github.com/lucasptrick/FrontEnd-Petshop)


## ✉️ Informações de Contato
- Emails (Pessoal e Institucional), respectivamente:
> lucaskmassa44@gmail.com  
> lpro@discente.ifpe.edu.br

- Telefone:
> Lucas Patrick Ramos de Oliveira
> 
> (81) 98667-8022
