<h1 align="center" style="font-weight: bold;">MedAgenda</h1>

<p align="center">
 <a href="#introdução">Intodução</a> • 
 <a href="#tecnologia">Tecnologias</a> • 
  <a href="#desenvolvimento">Desenvolvimento</a> •
 <a href="#colab">Colaboladores</a> •
 <a href="#</a>
</p>

<p align="center">
    <b>
</p>

<h2 id="Introdução"> Introdução</h2>

O objetivo é fornecer uma ferramenta simples e prática que conecta médicos e pacientes via aplicativo WEB. Com um sistema intuitivo, ele permite que os pacientes agendem consultas utilizando seus convênios de maneira facilitada, reduzindo burocracias e melhorando a experiência de atendimento médico. 

<h2 id="Tecnologias"> Tecnologias</h2>

- Lista de tecnologias utilizadas:
- 
- 
- 



<h3>Desenvolvimento</h3>

O uso da ferramenta visa otimizar o processo de agendamento e acesso a informações de saúde, facilitando a comunicação e o acompanhamento tanto para pacientes quanto para profissionais da saúde, com foco em conveniência e praticidade, oferecendo as seguintes funcionalidades:

Para Pacientes:

- Marcação Simplificada de Consultas: Agendamento online intuitivo, com visualização de horários disponíveis e escolha de profissionais/especialidades.
- Acesso ao Histórico de Exames: Visualização rápida e segura de resultados de exames realizados.
- Notificações Inteligentes: Lembretes de consultas agendadas para evitar esquecimentos.

Para Médicos:

- Gestão de Agenda: Visualização e organização eficiente da agenda de consultas.
- Acesso ao Histórico de Exames de Pacientes: Consulta rápida e segura do histórico de exames de seus pacientes para acompanhamento.

Here you list all prerequisites necessary for running your project. For example:

- [NodeJS](https://github.com/)
- [Git 2](https://github.com)

<h3>Cloning</h3>

How to clone your project

```bash
git clone your-project-url-in-github
```

<h3>Config .env variables</h2>

Use the `.env.example` as reference to create your configuration file `.env` with your AWS Credentials

```yaml
NODE_AWS_REGION=us-east-1
NODE_AWS_KEY_ID={YOUR_AWS_KEY_ID}
NODE_AWS_SECRET={YOUR_AWS_SECRET}
```

<h3>Starting</h3>

How to start your project

```bash
cd project-name
npm some-command-to-run
```

<h2 id="routes">📍 API Endpoints</h2>

Here you can list the main routes of your API, and what are their expected request bodies.
​
| route               | description                                          
|----------------------|-----------------------------------------------------
| <kbd>GET /authenticate</kbd>     | retrieves user info see [response details](#get-auth-detail)
| <kbd>POST /authenticate</kbd>     | authenticate user into the api see [request details](#post-auth-detail)

<h3 id="get-auth-detail">GET /authenticate</h3>

**RESPONSE**
```json
{
  "name": "Fernanda Kipper",
  "age": 20,
  "email": "her-email@gmail.com"
}
```

<h3 id="post-auth-detail">POST /authenticate</h3>

**REQUEST**
```json
{
  "username": "fernandakipper",
  "password": "4444444"
}
```

**RESPONSE**
```json
{
  "token": "OwoMRHsaQwyAgVoc3OXmL1JhMVUYXGGBbCTK0GBgiYitwQwjf0gVoBmkbuyy0pSi"
}
```

<h2 id="colab"> Colaboradores</h2>

* [Danielle Rossetti Rodrigues](https://github.com/danieller)

Special thank you for all people that contributed for this project.

<table>
  <tr>
    <td align="center">
      <a href="#">
        <img src="https://avatars.githubusercontent.com/u/61896274?v=4" width="100px;" alt="Fernanda Kipper Profile Picture"/><br>
        <sub>
          <b>Fernanda Kipper</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="#">
        <img src="https://t.ctcdn.com.br/n7eZ74KAcU3iYwnQ89-ul9txVxc=/400x400/smart/filters:format(webp)/i490769.jpeg" width="100px;" alt="Elon Musk Picture"/><br>
        <sub>
          <b>Elon Musk</b>
        </sub>
      </a>
    </td>
    <td align="center">
      <a href="#">
        <img src="https://miro.medium.com/max/360/0*1SkS3mSorArvY9kS.jpg" width="100px;" alt="Foto do Steve Jobs"/><br>
        <sub>
          <b>Steve Jobs</b>
        </sub>
      </a>
    </td>
  </tr>
</table>

<h2 id="contribute">📫 Contribute</h2>

Here you will explain how other developers can contribute to your project. For example, explaining how can create their branches, which patterns to follow and how to open an pull request

1. `git clone https://github.com/Fernanda-Kipper/text-editor.git`
2. `git checkout -b feature/NAME`
3. Follow commit patterns
4. Open a Pull Request explaining the problem solved or feature made, if exists, append screenshot of visual modifications and wait for the review!

<h3>Documentations that might help</h3>

[📝 How to create a Pull Request](https://www.atlassian.com/br/git/tutorials/making-a-pull-request)

[💾 Commit pattern](https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716)
