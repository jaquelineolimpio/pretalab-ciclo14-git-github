# Oficina de Git e GitHub da Pretalab | Ciclo 14 | Ano 2025

## Primeira Aula Introdutória sobre Git
### Verificar versão do Git

```bash
git --version
```
- Verificar se a configuração está feita
```bash
git config --list
```
- Se não estiver precisa configurar

limpa o terminal
```bash
Clear
```
```bash
git init
```   

depois para ver se tem a chave 

```bash
ls ~/.ssh (Windows)
```

`eval "$(ssh-agent -s)"` → inicia o `ssh-agent` e exporta as variáveis de ambiente necessárias para o shell atual.
`ssh-add ~/.ssh/id_ed25519` → adiciona sua chave privada (fica dentro da pasta `.ssh` do seu usuário).
    - `~` equivale a sua pasta de usuário
    **para aparecer a chave pública**

cat ~/.ssh/id_ed25519.pub→ copia a chave completa
• **No GitHub:** Icone do perfil → Settings → SSH and GPG keys → New SSH key → Colar a a chave e adicionar um titulo (security_pub-key) → Salvar chave

copia somente a chave que é a partir do ssh