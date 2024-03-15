### Hello World !  <img src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/Earth.gif" width="24px">

<h3>Meu nome é William Coelho. Seja bem-vindo ao meu perfil!<img alt="wave" src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width="30px">  </h3>  <br>

<p align="left">
👨🏽‍💻 Sou formado em <b>Analise e desenvolvimento de sistemas</b> na Universidade de Maringa;<br> 
🪐 Estou cursando <b>Física</b> na Universidade Federal de Goiás;<br> 
💼 Sou Analista de Sistemas na Stone S/A;<br>
Confira meu <a href="https://drive.google.com/file/d/1A51qTvaGNZnyltvUi6-slJYqV3jfX-AV/view?usp=sharing">Curriculo</a>
  
<h3><b>🔦 Visite minhas redes:<b></h3>
<div align="left" style="display: flex">
<a href="https://www.instagram.com/w.coelho.s/" target="_blank"><img src="https://img.shields.io/badge/@w.coelho.s-%23E4405F.svg?&style=for-the-badge&logo=instagram&logoColor=white"></a>
<a href="https://www.linkedin.com/in/williamcoelhoads/" target="_blank"><img src="https://img.shields.io/badge/williamcoelhoads-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white"></a>
## Total de visitas a este perfil Github:detective:

<p align="center" id="visitCount">Carregando...</p>

<script>
  // Função para obter a contagem de visitas do armazenamento local
  function getVisitCount() {
    return localStorage.getItem('githubVisitCount') || 0;
  }

  // Função para atualizar a contagem de visitas
  function updateVisitCount(count) {
    const visitCountElement = document.getElementById('visitCount');
    visitCountElement.textContent = `Total de visitas a este perfil GitHub: ${count}`;
  }

  // Verificar se a contagem já foi feita antes
  if (!localStorage.getItem('githubVisitDone')) {
    // Atualizar a contagem de visitas
    fetch('https://profile-counter.glitch.me/wyllamcoelhoads/count.svg')
      .then(response => response.text())
      .then(data => {
        const visitCount = parseInt(data.match(/\d+/)[0], 10);
        updateVisitCount(visitCount);

        // Salvar a contagem no armazenamento local
        localStorage.setItem('githubVisitCount', visitCount);
        localStorage.setItem('githubVisitDone', true);
      })
      .catch(error => console.error('Erro ao obter a contagem de visitas:', error));
  } else {
    // Obter a contagem de visitas do armazenamento local e atualizar
    const visitCount = getVisitCount();
    updateVisitCount(visitCount);
  }
</script>

</div>
<br>
<div>
<a href="https://github.com/seu-usuário-aqui">
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=wyllamcoelhoads&layout=compact&langs_count=7&theme=dracula"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api?username=wyllamcoelhoads&show_icons=true&theme=dracula&include_all_commits=true&count_private=true"/>
</div>
<br>
<div style="display: inline_block"><br>
<h3><b>👽👾 Linguagens e Tecnologias:<b></h3>
<p align="center">
<img title="Python"  align="center" alt="Python" height="40" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">
&nbsp;&nbsp;
<img title="Bash" align="center" alt="Bash" height="40" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bash/bash-original.svg">
&nbsp;&nbsp;
<img title="Java" align="center" alt="Java" height="40" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-plain.svg">
&nbsp;&nbsp;
<img title="Postgres" align="center" alt="Postgres" height="40" width="40" src="https://profilinator.rishav.dev/skills-assets/postgresql-original-wordmark.svg">
&nbsp;&nbsp;
<img title="MySQL" align="center" alt="MySQL" height="40" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg">
&nbsp;&nbsp;
<img title="Mariadb" align="center" alt="Mariadb" height="40" width="40" src="https://www.vectorlogo.zone/logos/mariadb/mariadb-icon.svg">
&nbsp;&nbsp;
<img title="Docker" align="center" alt="Docker" height="40" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-plain.svg">
&nbsp;&nbsp;
<img title="Mongodb" align="center" alt="Mongodb" height="40" width="40" src="https://profilinator.rishav.dev/skills-assets/mongodb-original-wordmark.svg">
&nbsp;&nbsp;
<img title="JavaScript" align="center" alt="Js" height="40" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg">
&nbsp;&nbsp;
<img title="CSS" align="center" alt="CSS" height="40" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
&nbsp;&nbsp;
</p>
</div>

<h3><b>🛠️ IDEs, Dev e Ferramentas:<b></h3>
<p align="center">
<img title="Linux" align="center" alt="Linux" height="40" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg">
&nbsp;&nbsp;
<img title="VScode" align="center" alt="VScode" height="40" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg">
&nbsp;&nbsp;
<img title="Git" align="center" alt="Git" height="40" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-plain.svg">
&nbsp;&nbsp;
<img title="Jira" align="center" alt="Jira" height="40" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jira/jira-original.svg">
&nbsp;&nbsp;
<img title="Chrome" align="center" alt="Chrome" height="40" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/chrome/chrome-original-wordmark.svg">
&nbsp;&nbsp;
<img title="Jupyter" align="center" alt="Jupyter" height="40" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original-wordmark.svg">
&nbsp;&nbsp;
<img title="Ubuntu" align="center" alt="Ubuntu" height="40" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/ubuntu/ubuntu-plain-wordmark.svg">
&nbsp;&nbsp;
</p>

<br>

 
                                                                                                         
