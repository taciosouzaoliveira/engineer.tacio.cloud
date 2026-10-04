# engineer.tacio.cloud

> Site do meu laboratório DevOps, publicado com domínio próprio, HTTPS e deploy automatizado pelo GitHub. A consultoria da Kurumin Tecnologia agora tem site próprio em [kurumintecnologia.com.br](https://kurumintecnologia.com.br).

**No ar:** [engineer.tacio.cloud](https://engineer.tacio.cloud) · [Kurumin Tecnologia](https://kurumintecnologia.com.br)

## O problema

Eu precisava de um lugar para documentar o laboratório em público e apresentar a consultoria, sem depender de construtor de site, sem mensalidade de plataforma e sem passo manual a cada atualização.

## O que este projeto faz

- Site estático em HTML e CSS, leve e rápido no celular
- Domínio próprio com HTTPS
- Publicação automática com GitHub Pages: cada commit na branch principal atualiza o site
- A antiga página `/consultoria/` redireciona para o site da Kurumin

## Por que isso importa

Este repositório é o primeiro case do serviço **Presença Web** da Kurumin: o mesmo processo que eu aplico em clientes (domínio, HTTPS, publicação versionada e documentada), aplicado no meu próprio site.

## Estrutura

```
.
├── index.html            # Laboratório
├── consultoria/
│   └── index.html        # Redireciona para kurumintecnologia.com.br
└── README.md
```

## Como atualizar

```bash
git clone https://github.com/taciosouzaoliveira/engineer.tacio.cloud.git
cd engineer.tacio.cloud
# editar os arquivos
git add .
git commit -m "docs: atualiza conteúdo"
git push
```

Depois do push, o GitHub Pages publica a nova versão automaticamente.

---

Feito por [Tácio Souza](https://tacio.cloud) · [Kurumin Tecnologia](https://kurumintecnologia.com.br)
