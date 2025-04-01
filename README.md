## Bem-vindo(a) ao perfil da Karolanne 😁

<div>
   <a href="https://github.com/lkaroolanne">
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=lkaroolanne&layout=compact&langs_count=8&theme=tokyonight&custom_title=Linguagens%20mais%20usadas&card_width=320&count_private=true"/>
    
<div style="display: inline_block"><br>
  <img align="center" alt="JavaScript" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg">
  <img align="center" alt="Python" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">
  <img align="center" alt="HTML" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg">
  <img align="center" alt="CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
  <img align="center" alt="Banco de Dados" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original.svg">
</div>
 
<br>

### Sobre Mim
Sou desenvolvedora com experiência em diversas tecnologias e áreas, incluindo:  
- **Programação**: Proficiência em **JavaScript** e **Python**.  
- **Visualização de Dados**: Habilidade com **Power BI** para criar dashboards e relatórios interativos.  
- **Banco de Dados**: Experiência em **MySQL** e outros sistemas de gerenciamento de banco de dados.  
- **Desenvolvimento Web**: Conhecimentos sólidos em **HTML** e **CSS**.  

Estou sempre em busca de novos desafios e aprendizados no universo da tecnologia.

<br>
 
### Entre em contato ou acompanhe meus conteúdos nas redes abaixo!

<div> 
  <a href="https://www.instagram.com/lkaroolanne/" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
  <a href="https://x.com/lkaroolanne" target="_blank"><img src="https://img.shields.io/badge/-X-%231DA1F2?style=for-the-badge&logo=twitter&logoColor=white" target="_blank"></a>
  <a href="https://www.facebook.com/profile.php?id=61571543497374" target="_blank"><img src="https://img.shields.io/badge/-Facebook-%234267B2?style=for-the-badge&logo=facebook&logoColor=white" target="_blank"></a>
  <a href="https://www.linkedin.com/in/karolanne-lima-santos-348628341/?trk=opento_sprofile_details" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>
  <a href="https://www.youtube.com/@lkaroolanne" target="_blank"><img src="https://img.shields.io/badge/-YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" target="_blank"></a>
  <a href="mailto:karolanne.developer@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
  <a href="https://t.me/+5511915700707" target="_blank"><img src="https://img.shields.io/badge/-Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" target="_blank"></a>
  <a href="https://wa.me/5511915700707" target="_blank"><img src="https://img.shields.io/badge/-WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" target="_blank"></a>
  <a href="https://discord.com" target="_blank"><img src="https://img.shields.io/badge/-Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" target="_blank"></a>
</div>

---

### 📌 Atualização Automática
Para garantir que seu perfil sempre exiba os dados mais recentes, crie um **GitHub Actions** para atualizar automaticamente as estatísticas a cada novo commit:

1. No seu repositório do GitHub, vá para `Actions`.
2. Crie um novo **workflow**.
3. Adicione o seguinte código no arquivo `.github/workflows/update-readme.yml`:

```yaml
name: Update README
on:
  push:
    branches:
      - main
  schedule:
    - cron: "0 0 * * *"

jobs:
  update-readme:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - name: Update README stats
        uses: anuraghazra/github-readme-stats@master
      - name: Commit and push if changed
        run: |
          git config --global user.name 'github-actions'
          git config --global user.email 'github-actions@github.com'
          git add README.md
          git commit -m 'Atualizando estatísticas do perfil' || exit 0
          git push
```

Agora, sempre que você subir um commit, seu perfil será atualizado automaticamente! 🚀
